/* Importing Google fonts - Inter */
@import url("https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,100..900&display=swap");
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Inter", sans-serif;
}
body {
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
  background: linear-gradient(#eceffe, #c5cffc);
}
.card-wrapper {
  max-width: 1100px;
  margin: 0 60px 35px;
  padding: 20px 10px;
  overflow: hidden;
}
.card-list .card-item {
  list-style: none;
}
.card-list .card-item .card-link {
  display: block;
  background: #fff;
  padding: 18px;
  user-select: none;
  border-radius: 12px;
  text-decoration: none;
  border: 2px solid transparent;
  box-shadow: 0 10px 10px rgba(0, 0, 0, 0.05);
  transition: 0.2s ease;
}
.card-list .card-item .card-link:active {
  cursor: grabbing;
}
.card-list .card-item .card-link:hover {
  border-color: #5372f0;
}
.card-list .card-link .card-image {
  width: 100%;
  border-radius: 10px;
  aspect-ratio: 16 / 9;
  object-fit: cover;
}
.card-list .card-link .badge {
  color: #5372f0;
  width: fit-content;
  padding: 8px 16px;
  font-size: 0.95rem;
  border-radius: 50px;
  font-weight: 500;
  background: #dde4ff;
  margin: 16px 0 18px;
}
.card-list .card-link .badge-designer {
  color: #b22485;
  background: #f7dff5;
}
.card-list .card-link .badge-marketer {
  color: #b25a2b;
  background: #ffe3d2;
}
.card-list .card-link .badge-gamer {
  color: #205c20;
  background: #d6f8d6;
}
.card-list .card-link .badge-editor {
  color: #856404;
  background: #fff3cd;
}
.card-list .card-link .card-title {
  color: #000;
  font-size: 1.19rem;
  font-weight: 600;
}
.card-list .card-link .card-button {
  height: 35px;
  width: 35px;
  color: #5372f0;
  margin: 30px 0 5px;
  background: none;
  cursor: pointer;
  border-radius: 50%;
  border: 2px solid #5372f0;
  transform: rotate(-45deg);
  transition: 0.4s ease;
}
.card-list .card-link:hover .card-button {
  color: #fff;
  background: #5372f0;
}
.card-wrapper .swiper-pagination-bullet {
  height: 13px;
  width: 13px;
  opacity: 0.5;
  background: #5372f0;
}
.card-wrapper .swiper-pagination-bullet-active {
  opacity: 1;
}
.card-wrapper .swiper-slide-button {
  color: #5372f0;
  margin-top: -35px;
}
/* Responsive media query code for small screens */
@media (max-width: 768px) {
  .card-wrapper {
    margin: 0 10px 25px;
  }
  .card-wrapper .swiper-slide-button {
    display: none;
  }
}
