# Sujeet-Sharma-landing-page

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Responsive Landing Page using HTML, CSS & Javascript</title>

    <!-- ==== STYLE.CSS ==== -->
    <link rel="stylesheet" href="style.css" />

    <!-- ====  REMIXICON CDN ==== -->
    <link
      href="https://cdn.jsdelivr.net/npm/remixicon@2.5.0/fonts/remixicon.css"
      rel="stylesheet"
    />

    <!-- ==== ANIMATE ON SCROLL CSS CDN  ==== -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
  </head>
  <body>
    <!-- ==== HEADER ==== -->
    <header class="container header">
      <!-- ==== NAVBAR ==== -->
      <nav class="nav">
        <div class="logo">
          <h2>꧁•⊹٭𝚂𝚄𝙹𝙴𝙴𝚃 𝚂𝙷𝙰𝚁𝙼𝙰٭⊹•꧂</h2>
        </div>

        <div class="nav_menu" id="nav_menu">
          <button class="close_btn" id="close_btn">
            <i class="ri-close-fill"></i>
          </button>

          <ul class="nav_menu_list">
            <li class="nav_menu_item">
              <a href="#" class="nav_menu_link">account</a>
            </li>
            <li class="nav_menu_item">
              <a href="#" class="nav_menu_link">about</a>
            </li>
            <li class="nav_menu_item">
              <a href="#" class="nav_menu_link">service</a>
            </li>
            <li class="nav_menu_item">
              <a href="#" class="nav_menu_link">contact</a>
            </li>
          </ul>
        </div>

        <button class="toggle_btn" id="toggle_btn">
          <i class="ri-menu-line"></i>
        </button>
      </nav>
    </header>

    <section class="wrapper">
      <div class="container">
        <div class="grid-cols-2">
          <div class="grid-item-1">
            <h1 class="main-heading">
              Welcome to=><BR>&hearts;<span>𝓢𝓤𝓙𝓔𝓔𝓣 𝓢𝓗𝓐𝓡𝓜𝓐</span>&hearts;
              <br />
              Develop anything.
            </h1>
            <p class="info-text">
              Build a beautiful, modern website with flexible components built
              from scratch.If you like my Landing page or need for future please contact me-Email: sujeetsharma7081@gmail.com | Phone: +91 7081263050, +91 9161531042
            </p>

            <div class="btn_wrapper">
              <button class="btn view_more_btn">
                view all pages <i class="ri-arrow-right-line"></i>
              </button>

              <button class="btn documentation_btn">documentation</button>
            </div>
          </div>
          <div class="grid-item-2">
            <div class="team_img_wrapper">
              <img src="Sujeet Sharma.jpg" alt="team-img" />
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="wrapper">
      <div class="container" data-aos="fade-up" data-aos-duration="1000">
        <div class="grid-cols-3">
          <div class="grid-col-item">
            <div class="icon">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
                />
              </svg>
            </div>
            <div class="featured_info">
              <span class="title">Built for developers </span>
              <p> Sujeet Sharma is a dedicated full-stack developer with a strong foundation in JavaScript, Node.js, React.js, MongoDB, SQL, and Express.js, complemented by a passion for front-end design using HTML, CSS, Tailwind CSS, and Bootstrap. Currently pursuing a B.Tech in Information Technology from Bansal Institute of Engineering and Technology, Sujeet has developed various web applications, including a Resume Builder Site and Digital Clock Application.</p>
            </div>
          </div>
          <div class="grid-col-item">
            <div class="icon">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M17 14v6m-3-3h6M6 10h2a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v2a2 2 0 002 2zm10 0h2a2 2 0 002-2V6a2 2 0 00-2-2h-2a2 2 0 00-2 2v2a2 2 0 002 2zM6 20h2a2 2 0 002-2v-2a2 2 0 00-2-2H6a2 2 0 00-2 2v2a2 2 0 002 2z"
                />
              </svg>
            </div>
            <div class="featured_info">
              <span class="title">Designed to be modern</span>
              <p>
                With hands-on experience in both front-end and back-end technologies, Sujeet has honed his skills during a two-month Frontend Developer Internship at Octa Net Services Pvt Ltd, where he worked with HTML, CSS, and JavaScript to create interactive user interfaces. His problem-solving abilities and expertise in data structures further enhance his technical acumen.
              </p>
            </div>
          </div>

          <div class="grid-col-item">
            <div class="icon">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"
                />
              </svg>
            </div>
            <div class="featured_info">
              <span class="title">Documentation for everything</span>
              <p>
                Sujeet is fluent in both English and Hindi and holds certifications in Full-Stack Development and Core Java. His interests include problem-solving, learning new technologies, and reading non-fiction.Outside of tech projects, Sujeet has demonstrated leadership and customer service skills during his tenure as a Lead Service Advisor at Bajaj Agency and a Financer at Hero MotoCorp. Additionally, he offers personalized tutoring services to help students succeed academically.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <footer></footer>

    <!-- ==== ANIMATE ON SCROLL JS CDN -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <!-- ==== GSAP CDN ==== -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.8.0/gsap.min.js"></script>
    <!-- ==== SCRIPT.JS ==== -->
    <script src="script.js"></script>
  </body>
</html>



// css code for this projet------

/* ==== "Inter" FONT-FAMILY FROM FONTS.GOOGLE.COM  ==== */
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@400;500&display=swap");
/* ==== ROOT RESET ==== */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Inter", sans-serif;
}
*,
*::before,
*::after {
  box-sizing: border-box;
}

/* ==== CSS VARIABLES ==== */
:root {
  --primary-color: #335eea;
  --link-color: #506690;
  --btn-hover-color: #2b50c7;
  --lg-heading: #161c2d;
  --text-content: #869ab8;
  --fixed-header-height: 4.5rem;
  --font-size-body-text: clamp(14px, 1.6vw, 16px);
  --h1-font-size: calc(var(--font-size-body-text) * 2.4);
  --h2-font-size: calc(var(--h1-font-size) - 15px);
  --h3-font-size: calc(var(var(--h2-font-size)) - 8px);
}

/* ==== RESET HTML ==== */
body {
  width: 100%;
  height: 100vh;
  overflow-x: hidden;
  background-color: #fafbfb;
}
ul li {
  list-style-type: none;
}
a {
  text-decoration: none;
}
button {
  background-color: transparent;
  border: none;
  outline: none;
  cursor: pointer;
}
/* ==== CONTAINER ==== */
.container {
  width: 100%;
}
@media screen and (min-width: 1040px) {
  .container {
    width: 1040px;
    margin: 0 auto;
  }
}
/* ==== HEADER ==== */
.header {
  height: var(--fixed-header-height);
  padding: 0 1.7rem;
}

/* ==== NAV ==== */
.nav {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
/* ==== LOGO ==== */
.logo h2 {
  font-size: var(--h2-font-size);
  color: var(--primary-color);
}
/* ====  NAV-MENU  ==== */
.nav_menu_list {
  display: flex;
  align-items: center;
}
.nav_menu_list .nav_menu_item {
  margin: 0 2rem;
}
.nav_menu_item .nav_menu_link {
  font-size: 16.5px;
  line-height: 27px;
  color: var(--link-color);
  text-transform: capitalize;
  letter-spacing: 0.5px;
}
.nav_menu_link:hover {
  color: var(--primary-color);
}
.toggle_btn {
  font-size: 20px;
  font-weight: 600;
  color: var(--lg-heading);
  z-index: 4;
}
.nav_menu,
.close_btn {
  display: none;
}
.show {
  right: 3% !important;
}
/* ====  WRAPPER ==== */
.wrapper {
  width: 100%;
  padding-left: 1.7rem;
  padding-right: 1.7rem;
  padding-top: 5rem;
  margin-bottom: 5rem;
}

.wrapper .title {
  font-size: var(--h2-font-size);
}

.grid-cols-2 {
  width: 100%;
  height: 100%;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 4rem;
}
.grid-item-1 {
  padding-top: 5rem;
  padding-left: 1.5rem;
}
.main-heading {
  font-weight: 300;
  font-size: var(--h1-font-size);
  line-height: 1.1;
}
.main-heading span {
  color: var(--primary-color);
}
.info-text {
  margin-top: 1.5rem;
  font-size: 19px;
  line-height: 28px;
  color: #334157;
}
.btn_wrapper {
  margin-top: 3.5rem;
  display: flex;
  width: 100%;
}
.btn {
  width: 110px;
  height: 50px;
  background-color: var(--primary-color);
  display: block;
  font-size: 16px;
  color: #fff;
  text-transform: capitalize;
  border-radius: 7px;
  letter-spacing: 1px;
  transition: 0.4s;
}
.btn:hover {
  transform: translateY(-3px);
  background-color: var(--btn-hover-color);
}
.view_more_btn {
  width: 180px;
  height: 55px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 16px;
  letter-spacing: 0;
  color: #fff;
  font-weight: 500;
  margin-right: 10px;
  box-shadow: 0 0.5rem 1.5rem rgba(22, 28, 45, 0.1);
}
.view_more_btn i {
  margin-left: 0.7rem;
}
.view_more_btn:hover {
  transition: box-shadow 0.25s ease, transform 0.25s ease;
}
.documentation_btn {
  width: 150px;
  height: 55px;
  font-size: 16px;
  font-weight: 500;
  color: #fff;
  letter-spacing: 0;
  background-color: #e1e7fc;
  color: #0e2a86;
  box-shadow: 0 0.5rem 1.5rem rgba(22, 28, 45, 0.1);
}
.documentation_btn:hover {
  background-color: #d7ddf1;
  transition: box-shadow 0.25s ease, transform 0.25s ease;
}
.grid-item-2 {
  width: 100%;
  height: 100%;
}
.team_img_wrapper {
  width: 500px;
  max-width: 100%;
  height: 440px;
}
.team_img_wrapper img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}
.grid-cols-3 {
  width: 100%;
  height: 100%;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  column-gap: 3rem;
  row-gap: 2rem;
  padding: 1rem;
}
.grid-col-item {
  height: 100%;
}
.icon {
  width: 100%;
  line-height: 40px;
}
.icon svg {
  width: 30px;
  height: 30px;
  color: #6b85d8;
}
.featured_info {
  width: 100%;
}
.featured_info span {
  width: 100%;
  display: block;
  font-size: 21px;
  line-height: 33px;
  color: var(--lg-heading);
}
.featured_info p {
  display: block;
  width: 100%;
  margin-top: 7px;
  font-weight: 400;
  color: #334157;
  line-height: 25px;
  font-size: 15.5px;
}
footer {
  width: 100%;
  background-color: var(--primary-color);
  height: 12px;
  margin-top: 8rem;
}

/* ==== MEDIA QURIES FOR RESPONSIVE DESIGN ==== */
@media screen and (min-width: 768px) {
  .toggle_btn {
    display: none;
  }
  .nav_menu {
    display: block;
  }
}

@media screen and (max-width: 768px) {
  .logo h2 {
    font-size: var(--h2-font-size);
  }
  .nav_menu {
    position: fixed;
    width: 93%;
    height: 100%;
    display: block;
    top: 2.5%;
    right: -100%;
    background-color: #fff;
    padding: 3rem;
    border-radius: 10px;
    box-shadow: 0 0.5rem 1.5rem rgba(22, 28, 45, 0.1);
    z-index: 50;
    transition: 0.4s;
  }
  .nav_menu_list {
    flex-direction: column;
    align-items: flex-start;
    margin-top: 4rem;
  }
  .nav_menu_list .nav_menu_item {
    margin: 1rem 0;
  }
  .nav_menu_item .nav_menu_link {
    font-size: 18px;
  }
  .close_btn {
    display: block;
    position: absolute;
    right: 10%;
    font-size: 25px;
    color: #50689e;
  }
  .close_btn:hover {
    color: #000;
  }
  .wrapper {
    padding: 0 0.7rem;
  }
  .grid-item-1 {
    padding-left: 0rem;
  }
  .main-heading {
    font-size: var(--h1-font-size);
    line-height: 1.1;
  }
  .view_more_btn {
    width: 140px;
    height: 55px;
    font-size: 13.5px;
    margin-right: 1rem;
  }
  .grid-cols-3 {
    grid-template-columns: repeat(auto-fit, minmax(100%, 1fr));
  }
  .featured_info p {
    line-height: 23px;
    font-size: 14px;
  }
}

@media screen and (max-width: 991px) {
  .wrapper {
    padding-top: 3rem;
  }
  .grid-cols-2 {
    grid-template-columns: repeat(auto-fit, minmax(100%, 1fr));
  }
  .grid-item-1 {
    order: 2;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding-top: 0;
  }
  .main-heading {
    font-size: var(--h1-font-size);
    text-align: center;
    line-height: 1.1;
  }
  .info-text {
    font-size: 16px;
    text-align: center;
    padding: 0.7rem;
  }
  .btn_wrapper {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .grid-item-2 {
    order: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  .team_img_wrapper {
    width: 350px;
    height: 350px;
  }
  .featured_info span {
    font-size: 19px;
  }
}


/// js program ---

const navId = document.getElementById("nav_menu"),
  ToggleBtnId = document.getElementById("toggle_btn"),
  CloseBtnId = document.getElementById("close_btn");

// ==== SHOW MENU ==== //
ToggleBtnId.addEventListener("click", () => {
  navId.classList.add("show");
});

// ==== HIDE MENU ==== //
CloseBtnId.addEventListener("click", () => {
  navId.classList.remove("show");
});

// ==== Animate on Scroll Initialize  ==== //
AOS.init();

// ==== GSAP Animations ==== //
// ==== LOGO  ==== //
gsap.from(".logo", {
  opacity: 0,
  y: -10,
  delay: 1,
  duration: 0.5,
});
// ==== NAV-MENU ==== //
gsap.from(".nav_menu_list .nav_menu_item", {
  opacity: 0,
  y: -10,
  delay: 1.4,
  duration: 0.5,
  stagger: 0.3,
});
// ==== TOGGLE BTN ==== //
gsap.from(".toggle_btn", {
  opacity: 0,
  y: -10,
  delay: 1.4,
  duration: 0.5,
});
// ==== MAIN HEADING  ==== //
gsap.from(".main-heading", {
  opacity: 0,
  y: 20,
  delay: 2.4,
  duration: 1,
});
// ==== INFO TEXT ==== //
gsap.from(".info-text", {
  opacity: 0,
  y: 20,
  delay: 2.8,
  duration: 1,
});
// ==== CTA BUTTONS ==== //
gsap.from(".btn_wrapper", {
  opacity: 0,
  y: 20,
  delay: 2.8,
  duration: 1,
});
// ==== TEAM IMAGE ==== //
gsap.from(".team_img_wrapper img", {
  opacity: 0,
  y: 20,
  delay: 3,
  duration: 1,
});
