<div align="center">
  <br />
    <a href="shushi-themed-website-gold.vercel.app" target="_blank">
      <img src="" alt="Project Banner">
    </a>
  <br />

  <div>
    <img src="https://img.shields.io/badge/-HTML_5-black?style=for-the-badge&logoColor=white&logo=html5&color=E34F26" alt="html5" />
    <img src="https://img.shields.io/badge/-css3-black?style=for-the-badge&logoColor=white&logo=css3&color=1572B6" alt="css3" />
  </div>

  <h3 align="center">Sushi Website</h3>
    <div align="center">
     Welcome to the source code of this sushi website — refer to <a href="" ><b>code snippets</b></a> if you find it difficult to navigate or copy specific CSS sections.
     </div>

</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Snippets](#snippets)
6. 🔗 [Links](#links)
7. 🚀 [More](#more)

## <a name="introduction">🤖 Introduction</a>

Develop a sushi website showcasing popular food, trending sushi, and drinks using HTML and CSS with smooth subtle animations. 

<a href="https://developer-ronnie.hashnode.dev" target="_blank">
  <img src="https://www.svgrepo.com/show/353856/hashnode.svg" width="20" style="vertical-align:middle; margin-right:8px;" />
  <strong>Read my blog on Hashnode</strong>
</a>

## <a name="tech-stack">⚙️ Tech Stack</a>

- HTML 5
- CSS 3
- Vite

## <a name="features">🔋 Features</a>

👉 **CSS Variables**: Utilize CSS variables to maintain a consistent and easily adjustable styling approach throughout the project

👉 **Importing CSS Files**: Import CSS files into others, promoting modularity and organization in styling.

👉 **Flex and Position Properties**: Use of flex and position properties in CSS to create responsive and well-structured layouts.

👉 **Rendering HTML through JavaScript**: Rendering HTML through JavaScript using reusable functions, enhancing code efficiency.

👉 **Smooth Animations**: Smooth and subtle animations to enhance the overall user experience, focusing on fluid transitions.

👉 **BEM Method**: Follow the Block Element Modifier (BEM) methodology for naming classes, promoting a clear and maintainable structure.

👉 **Organized File and Folder Structure**: Maintain a well-organized file and folder structure for easy navigation and management of project assets.

👉 **Responsive Design**: The application is completely responsive across all devices, employing responsive design techniques such as media queries and fluid layouts.

all these while creating the sushi website with,
* Navigation Bar
* Creative Hero Section
* About Us Section
* Popular Food, Trending Sushi, and Drinks Sections
* Newsletter Signup and Footer

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/Developer-RONNIE/Shushi-Themed-Website.git
cd project_html_css_website
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the project.

## <a name="snippets">🕸️ Snippets</a>

<details>
<summary><code>index.html</code></summary>

```html 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="icon" type="image/png" href="sushi.png" />
  <link rel="stylesheet" href="css/style.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css">
  <title>ShushiWorld</title>
</head>
<body>
  <!-- Navbar  -->
  <header>
    <nav class="header__nav">
      <div class="header__logo">
        <h4 data-aos="fade-down" >Sushi World</h4>
        <div class="header__logo-overlay"></div>
      </div>

      <ul class="header__menu" data-aos="fade-down">
        <li>
          <a href="#menu">Menu</a>
        </li>
        <li>
          <a href="#food">Food</a>
        </li>
        <li>
          <a href="#services">Services</a>
        </li>
        <li>
          <a href="#about-us">About Us</a>
        </li>
        <li>
          <img src="assets/search.svg" alt="search">
        </li>
      </ul>

      <ul class="header__menu-mobile" data-aos="fade-down">
        <li>
          <img src="assets/menu.svg" alt="menu">
        </li>
      </ul>
    </nav>
    
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-image">
      <img 
      src = "assets/sushi-1.png"
      alt = "sushi"
      data-aos="fade-up"
      />

      <h2 data-aos="fade-up">
        日  <br/>
        本  <br/>
        食   
      </h2>

      <div class="hero-image__overlay"></div>
    </div>

    <div class="hero-content">
      <div class="hero-content-info" data-aos="fade-left">
        <h1>Feel the taste of Japanese food</h1>
        <p>Feel the taste of the most popular Japanese food from anywhere and anytime.</p>

        <div class="hero-content__buttons">
          <button class="hero-content__order-button">
            Order Now 
          </button>
          <button class="hero-content__play-button">
            <img src="assets/play-circle.svg" alt="play"/>
            How to Order
          </button>
        </div> 
      </div>

      <div class="hero-content__testimonial" data-aos="fade-up">
        <div class="hero-content__customer flex-center">
          <h4>24<span>k+</span></h4>
          <p>Happy Customers</p>
        </div>

        <div class="hero-content__review">
          <img src="assets/user.png" alt="user" />
          <p>This is the best Japanese food delivery service that ever existed.</p>
        </div>
      </div>

      

    </div>

    
  </section>

  <!-- About Us Section -->
  <section class="about-us" id="about-us">
    <div class="about-us__image">
      <div class="about-us__image-sushi3">
        <img src="assets/sushi-3.png" alt="sushi" data-aos="fade-right"/>
      </div>

      <button class="about-us__button">
        Learn More

        <img src="assets/arrow-up-right.svg" alt="learn more"/>
      </button>

      <div class="about-us__image-sushi2">
        <img src="assets/sushi-2.png" alt="sushi" data-aos="fade-right"/>
      </div>

    </div>

    <div class="about-us__content" data-aos="fade-left">
      <p class="sushi__subtitle">
        About Us / 私たちに関しましては
      </p>
      <h3 class="sushi__title">
        Our mission is to bring true Japanese flavours to you.
      </h3>
      <p class="sushi__description">
        We will continue to provide the experince of Omotenashi, the Japanese mindset of hospitality, with our shopping and dinning for our customers.
      </p>

    </div>
  </section>

  <!-- Popular Foods Section -->
  <section class="popular-foods" id="menu">
    <h2 class="popular-foods__title" data-aos="flip-up">
      Popular Foods/ 人気 
    </h2>

    <div class="popular-foods__filters sushi__hide-scrollbar" data-aos="fade-up">
      <button class="popular-foods__filter-btn active">All</button>
      <button class="popular-foods__filter-btn">
        <img src="assets/sushi-9.png" alt="sushi 9">
        Sushi
      </button>
      <button class="popular-foods__filter-btn">
        <img src="assets/sushi-8.png" alt="sushi 8">
        Ramen
      </button>
      <button class="popular-foods__filter-btn">
        <img src="assets/sushi-7.png" alt="sushi 7">
        Udon
      </button>
      <button class="popular-foods__filter-btn">
        <img src="assets/sushi-6.png" alt="sushi 6">
        Danggo
      </button>
      <button class="popular-foods__filter-btn ">All</button>

    </div>

    <div class="popular-foods__catalogue" data-aos="fade-up">
      <article class="popular-foods__card">
        <img class="popular-foods__card-image" src="assets/sushi-12.png" alt="sushi-12">

        <h4 class="popular-foods__card-title">Chezu Shushi</h4>

        <div class="popular-foods__card-details flex-between">
          <div class="popular-foods__card-rating">
            <img src="assets/star.svg" alt="star">
            <p>4.9</p>
          </div>

          <p class="popular-foods__card-price">$21.00</p>
        </div>
      </article>
      <article class="popular-foods__card active-card">
        <img class="popular-foods__card-image" src="assets/sushi-11.png" alt="sushi-11">

        <h4 class="popular-foods__card-title">Original Shushi</h4>

        <div class="popular-foods__card-details flex-between">
          <div class="popular-foods__card-rating">
            <img src="assets/star.svg" alt="star">
            <p>5.0</p>
          </div>

          <p class="popular-foods__card-price">$19.00</p>
        </div>
      </article>
      <article class="popular-foods__card">
        <img class="popular-foods__card-image" src="assets/sushi-10.png" alt="sushi-10">

        <h4 class="popular-foods__card-title">Ramen Legendo</h4>

        <div class="popular-foods__card-details flex-between">
          <div class="popular-foods__card-rating">
            <img src="assets/star.svg" alt="star">
            <p>4.7</p>
          </div>

          <p class="popular-foods__card-price">$13.00</p>
        </div>
      </article>

    </div>

    <button class="popular-foods__button">
      Explore Food 
      <img src="assets/arrow-right.svg" alt="arrow-right">
    </button>
  </section>

  <!-- Trending Section -->
  <section class="trending" id="food">
    <section class="trending-sushi">

      <div class="trending__content" data-aos="fade-right">
        <p class="sushi__subtitle">Whats's Trending / トレンド </p>

        <h3 class="sushi__title">Japanese Sushi</h3>
        <p class="sushi__description">Feel the taste of the most delicious Sushi here.</p>

        <ul class="trending__list flex-between">
          <li>
            <div class="trending__icon flex-center">
              <img src="assets/check.svg" alt="check">
            </div>
            <p>Make Sushi</p>
          </li>
          <li>
            <div class="trending__icon flex-center">
              <img src="assets/check.svg" alt="check">
            </div>
            <p>Oshizushi</p>
          </li>
          <li>
            <div class="trending__icon flex-center">
              <img src="assets/check.svg" alt="check">
            </div>
            <p>Uramaki Sushi</p>
          </li>
          <li>
            <div class="trending__icon flex-center">
              <img src="assets/check.svg" alt="check">
            </div>
            <p>Nigiri Sushi</p>
          </li>
          <li>
            <div class="trending__icon flex-center">
              <img src="assets/check.svg" alt="check">
            </div>
            <p>Temaki Sushi</p>
          </li>
          <li>
            <div class="trending__icon flex-center">
              <img src="assets/check.svg" alt="check">
            </div>
            <p>Inari Sushi</p>
          </li>
        </ul>
      </div>
      
      <div class="trending__image flex-center">
        <img src="assets/sushi-5.png" alt="sushi-5" data-aos="fade-left">

        <div class="trending__arrow trending__arrow-left">
          <img src="assets/arrow-vertical.svg" alt="arrow vertical">
        </div>
        
        <div class="trending__arrow trending__arrow-bottom">
          <img src="assets/arrow-horizontal.svg" alt="arrow arrow-horizontal">
        </div>
      </div>

    </section>

    <div class="trending__discover" data-aos="zoom-in">
      <p>Discover</p>
    </div>

    <section class="trending-drinks">

      <div class="trending__image flex-center">
        <img src="assets/sushi-4.png" alt="sushi-4" data-aos="fade-right">

        <div class="trending__arrow trending__arrow-top">
          <img src="assets/arrow-horizontal.svg" alt="arrow horizontal">
        </div>
        
        <div class="trending__arrow trending__arrow-right">
          <img src="assets/arrow-vertical.svg" alt="arrow arrow-vertical">
        </div>
      </div>

      <div class="trending__content" data-aos="fade-left">
        <p class="sushi__subtitle">Whats's Trending / トレンド </p>

        <h3 class="sushi__title">Japanese Drinks</h3>
        <p class="sushi__description">Feel the taste of the most delicious Japanese Drinks here.</p>

        <ul class="trending__list flex-between">
          <li>
            <div class="trending__icon flex-center">
              <img src="assets/check.svg" alt="check">
            </div>
            <p>Oruncha</p>
          </li>
          <li>
            <div class="trending__icon flex-center">
              <img src="assets/check.svg" alt="check">
            </div>
            <p>Sakura Tea</p>
          </li>
          <li>
            <div class="trending__icon flex-center">
              <img src="assets/check.svg" alt="check">
            </div>
            <p>Aojiru</p>
          </li>
          <li>
            <div class="trending__icon flex-center">
              <img src="assets/check.svg" alt="check">
            </div>
            <p>Ofukucha</p>
          </li>
          <li>
            <div class="trending__icon flex-center">
              <img src="assets/check.svg" alt="check">
            </div>
            <p>Kombu-cha</p>
          </li>
          <li>
            <div class="trending__icon flex-center">
              <img src="assets/check.svg" alt="check">
            </div>
            <p>Mugicha</p>
          </li>
        </ul>
      </div>

    </section>

  </section>

  <!-- Subscription Section -->
  <section class="subscription flex-center" id="services">
    <h2 data-aos="flip-down">
      Get offers stright <br/>
      to your inbox
    </h2>
    <p data-aos="fade-up">Sign up for the Sushiman newsletter </p>

    <div class="subscription__form" data-aos= "fade-up">
      <input type="text" placeholder="Enter your email address"/>
      <button>Get Started</button>
    </div>
  </section>

  <!-- Footer Section -->
  <footer class="footer flex-between">
    <h3 class="footer__logo">
      <span>Sushi</span>World
    </h3>

    <ul class="footer__nav">
      <li><a href="#menu">Menu</a></li>
      <li><a href="#food">Food</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#about-us">About Us</a></li>
    </ul>

    <ul class="footer__social">
      <li class="flex-center">
        <img src="assets/facebook.svg" alt="facebook">
      </li>
      <li class="flex-center">
        <img src="assets/instagram.svg" alt="instagram">
      </li>
      <li class="flex-center">
        <img src="assets/twitter.svg" alt="twitter">
      </li>
    </ul>
  </footer>
  
  <script type="module" src="js/script.js"></script>
</body>
</html>
```
</details>

<details>
<summary><code>style.css</code></summary>

```css
@import url("https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700;800;900&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@200;300;400;500;600;700;800&display=swap");

/* other css file imports */
@import url("sections/header.css");
 @import url("sections/hero.css");
@import url("sections/about.css");
@import url("sections/popular.css");
@import url("sections/trending.css");
@import url("sections/subscribe.css");
@import url("sections/footer.css"); 

/* CSS variables for reusablity across all files (including above imported) */
:root {
  --playfair-display: "Playfair Display", serif;
  --plus-jakarta-sans: "Plus Jakarta Sans", sans-serif;

  --primary-color: #b1454a;
  --secondary-color: #121212;

  --black-200: #020202;
  --black-300: #333333;
  --black-400: #1f1e31;
  --black-500: #555555;
  --gray-100: #888888;

  --color-white: #fff;
  --color-creamson: #fff0de;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  max-width: 1280px;
  margin: 0 auto;
  background-color: var(--color-creamson);
}

a {
  text-decoration: none;
  color: inherit;
}


.flex-center {
  display: flex;
  justify-content: center;
  align-items: center;
}

.flex-between {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.sushi__subtitle {
  font-size: 18px;
  font-weight: 400;
  font-family: var(--plus-jakarta-sans);

  color: var(--primary-color);
  opacity: 0.8;

  letter-spacing: -0.01em;
}

.sushi__title {
  font-size: 64px;
  font-weight: 600;
  font-family: var(--playfair-display);

  color: var(--secondary-color);

  margin-top: 16px;
}

.sushi__description {
  font-size: 18px;
  font-weight: 400;
  font-family: var(--plus-jakarta-sans);

  line-height: 36px;
  letter-spacing: -0.01em;

  color: var(--secondary-color);
  opacity: 0.8;

  margin: 32px 0px;
}

/* Hide scrollbar for Chrome, Safari and Opera */
.sushi__hide-scrollbar::-webkit-scrollbar {
  display: none;
}

/* Hide scrollbar for IE, Edge and Firefox */
.sushi__hide-scrollbar {
  -ms-overflow-style: none; /* IE and Edge */
  scrollbar-width: none; /* Firefox */
}

/* START: about us media queries */
@media screen and (max-width: 1024px) {
  .about-us {
    flex-direction: column;
  }

  .about-us__image {
    flex-direction: row;
  }

  .about-us__image-sushi3 {
    border-bottom: none;
    border-right: 8px solid var(--color-creamson);
  }

  .about-us__button {
    display: none;
  }
}

@media screen and (max-width: 750px) {
  .about-us__image {
    flex-direction: column;
  }

  .about-us__image-sushi3 {
    border-bottom: 8px solid var(--color-creamson);
    border-right: none;
  }

  .about-us__button {
    display: block;
    top: 47%;
  }
}

@media screen and (max-width: 550px) {
  .about-us__image-sushi2 img,
  .about-us__image-sushi3 img {
    width: 50%;
    height: 160px;

    object-fit: contain;
  }

  .about-us__image div {
    padding: 32px;
  }

  .about-us__button {
    top: 44%;
  }

  .about-us__content {
    padding: 32px;
  }
}
/* END: about us media queries */


/* START: header media querie */
@media screen and (max-width: 900px) {
  .header__nav {
    background: var(--primary-color);
  }

  .header__menu {
    display: none;
  }

  .header__menu-mobile {
    display: flex;
  }
}

@media screen and (max-width: 550px) {
  .header__logo {
    padding-left: 0;
  }
}
/* END: header media queries */

/* START: hero media queries */
@media screen and (max-width: 1060px) {
  .hero {
    flex-direction: column;
  }

  .hero-image img {
    width: 100%;

    transform: matrix(1, 0.05, 0, 1.25, 0, 0) !important;
  }
}

@media screen and (max-width: 750px) {
  .hero-image h2 {
    font-size: 70px;
    line-height: 90px;
  }
}

@media screen and (max-width: 550px) {
  .hero-image h2 {
    font-size: 40px;
    line-height: 60px;
  }

  .hero-content-info {
    padding: 32px;
  }

  .hero-content-info h1 {
    font-size: 60px;
  }

  .hero-content-info p {
    margin: 32px 0;
  }

  .hero-content__buttons {
    margin: 41px 0;
  }

  .hero-content__testimonial {
    padding: 32px;
  }
}
/* END: hero media queries */

/* START: popular media queries */
@media screen and (max-width: 550px) {
  .popular-foods {
    padding: 64px 32px;
  }

  .popular-foods__card,
  .popular-foods__card.active-card {
    min-width: 100%;
  }
}
/* END: popular media queries */

/* START: subscribe media queries */
@media screen and (max-width: 550px) {
  .subscription {
    padding: 64px 32px;
  }

  .subscription h2 {
    font-size: 68px;
    line-height: 100px;
  }

  .subscription__form {
    flex-direction: column;
    gap: 20px;

    min-width: 100%;
    border-radius: 20px;
    padding: 0;

    border: none;
  }

  .subscription__form input {
    min-height: 50px;

    border: 1px solid rgba(255, 255, 255, 0.5);
    padding: 10px 20px;
    border-radius: 30px;
  }

  .subscription__form button {
    min-width: 100%;
  }
}
/* END: subscribe media queries */

/* START: trending media queries */
@media screen and (max-width: 1024px) {
  .trending-sushi {
    flex-direction: column;
  }

  .trending-drinks {
    flex-direction: column-reverse;
  }

  .trending__image {
    width: 100%;
    background-size: cover;
  }

  .trending__discover {
    display: none;
  }

  .trending__arrow {
    display: none;
  }
}

@media screen and (max-width: 550px) {
  .trending__image img {
    width: 70%;
    height: 70%;
  }

  .trending__content {
    padding: 32px;
  }
}
/* END: trending media queries */
```
</details>

<details>
<summary><code>script.js</code></summary>

```javascript
// import images as relative image path won't work with vite/vercel.
import check from '../assets/check.svg'
import star from '../assets/star.svg'
import sushi12 from '../assets/sushi-12.png'
import sushi11 from '../assets/sushi-11.png'
import sushi10 from '../assets/sushi-10.png'

import AOS from "aos";
import "aos/dist/aos.css";

AOS.init({
    duration: 1000,
    offset: 100,
    once: false, // Animates every time it enters viewport
});

const trendingSushis = [
    'Make Sushi',
    'Nigiri Sushi',
    'Oshizushi',
    'Temaki Sushi',
    'Uramaki Sushi',
    'Inari Sushi'
];

const trendingDrinks = [
    "Oruncha",
    "Ofukucha",
    "Sakura Tea",
    "Kombu-cha",
    "Aojiru",
    "Mugicha",
]

const cards = [
    {
        imgSrc: sushi12,
        alt: "sushi-12",
        title: "Chezu Sushi",
        rating: "4.8",
        price: "$21.00"
    },
    {
        imgSrc: sushi11,
        alt: "sushi-11",
        title: "Originale Sushi",
        rating: "4.8",
        price: "$21.00",
        active: true
    },
    {
        imgSrc: sushi10,
        alt: "sushi-10",
        title: "Ramen Legendo",
        rating: "4.8",
        price: "$21.00"
    }
];
```
</details>



## <a name="links">🔗 Links</a>

Assets used in the project are [here](https://drive.google.com/file/d/1feqXd1mPKjdQDjd3l4hV_JcX-l1mJRor/view)

## <a name="more">🚀 More</a>

**Build more clean and creative HTML & CSS projects like this**

Enjoyed creating this project? Dive deeper into more projects for a richer learning adventure. They're packed with detailed cool features, and exercises to boost your skills. Give it a go!

[![GitHub - HTML-CSS Projects](https://img.shields.io/badge/HTML--CSS--Projects-on%20GitHub-black?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Developer-RONNIE/)


