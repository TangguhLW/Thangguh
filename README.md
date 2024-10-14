<!DOCTYPE html>
<html lang="en">

  <head>

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&display=swap" rel="stylesheet">

    <title>Tangguh Lambang Wibawa XI RPL 1</title>

    <!-- Bootstrap core CSS -->
    <link href="vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">


    <!-- Additional CSS Files -->
    <link rel="stylesheet" href="assets/css/fontawesome.css">
    <link rel="stylesheet" href="assets/css/templatemo-lugx-gaming.css">
    <link rel="stylesheet" href="assets/css/owl.css">
    <link rel="stylesheet" href="assets/css/animate.css">
    <link rel="stylesheet"href="https://unpkg.com/swiper@7/swiper-bundle.min.css"/>
<!--
    <style>
    
/*

TemplateMo 589 lugx gaming

https://templatemo.com/tm-589-lugx-gaming

*/

/* ---------------------------------------------
Table of contents
------------------------------------------------
01. font & reset css
02. reset
03. global styles
04. header
05. banner
06. features
07. testimonials
08. contact
09. footer

--------------------------------------------- */
/* 
---------------------------------------------
font & reset css
--------------------------------------------- 
*/
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900");
/* 
---------------------------------------------
reset
--------------------------------------------- 
*/
html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, div
pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, font, img, ins, kbd, q,
s, samp, small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li,
figure, header, nav, section, article, aside, footer, figcaption {
  margin: 0;
  padding: 0;
  border: 0;
  outline: 0;
}

.clearfix:after {
  content: ".";
  display: block;
  clear: both;
  visibility: hidden;
  line-height: 0;
  height: 0;
}

.clearfix {
  display: inline-block;
}

html[xmlns] .clearfix {
  display: block;
}

* html .clearfix {
  height: 1%;
}

ul, li {
  padding: 0;
  margin: 0;
  list-style: none;
}

header, nav, section, article, aside, footer, hgroup {
  display: block;
}

* {
  box-sizing: border-box;
}

html, body {
  font-family: 'Poppins', sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

a {
  text-decoration: none !important;
}

h1, h2, h3, h4, h5, h6 {
  color: #1e1e1e;
  margin-top: 0px;
  margin-bottom: 0px;
  font-weight: 700;
}

ul {
  margin-bottom: 0px;
}

p {
  font-size: 14px;
  line-height: 28px;
  color: #4a4a4a;
}

img {
  width: 100%;
  overflow: hidden;
}

/* 
---------------------------------------------
Global Styles
--------------------------------------------- 
*/
html,
body {
  font-family: 'Poppins', sans-serif;
}

::selection {
  background: #0071f8;
  color: #fff;
}

::-moz-selection {
  background: #0071f8;
  color: #fff;
}

.section {
  margin-top: 120px;
}

.section-heading {
  margin-bottom: 70px;
}

.section-heading h2 {
  font-size: 36px;
  font-weight: 700;
  text-transform: capitalize;
  margin-top: 20px;
  line-height: 44px;
}

.section-heading h2 em {
  font-style: normal;
  color: #0071f8;
}

.section-heading h6 {
  color: #ee626b;
  font-size: 15px;
  text-transform: uppercase;
  font-weight: 700;
}

.main-button a {
  display: inline-block;
  background-color: transparent;
  text-transform: uppercase;
  color: transparent;
  font-size: 14px;
  font-weight: 600;
  height: 50px;
  line-height: 50px;
  padding: 0px 30px;
  border-radius: 25px;
  transition: all .3s;
}

.main-button a:hover {
  background-color: transparent;
  color: transparent;
}

/* 
---------------------------------------------
Pre-loader Style
--------------------------------------------- 
*/

.js-preloader {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba(0,0,0,0.99);
  display: -webkit-box;
  display: flex;
  -webkit-box-align: center;
  align-items: center;
  -webkit-box-pack: center;
  justify-content: center;
  opacity: 1;
  visibility: visible;
  z-index: 9999;
  -webkit-transition: opacity 0.25s ease;
  transition: opacity 0.25s ease;
}

.js-preloader.loaded {
  opacity: 0;
  visibility: hidden;
  pointer-events: none;
}

@-webkit-keyframes dot {
  50% {
      -webkit-transform: translateX(96px);
      transform: translateX(96px);
  }
}

@keyframes dot {
  50% {
      -webkit-transform: translateX(96px);
      transform: translateX(96px);
  }
}

@-webkit-keyframes dots {
  50% {
      -webkit-transform: translateX(-31px);
      transform: translateX(-31px);
  }
}

@keyframes dots {
  50% {
      -webkit-transform: translateX(-31px);
      transform: translateX(-31px);
  }
}

.preloader-inner {
  position: relative;
  width: 142px;
  height: 40px;
  background: transparent;
}

.preloader-inner .dot {
  position: absolute;
  width: 16px;
  height: 16px;
  top: 12px;
  left: 15px;
  background: #0071f8;
  border-radius: 50%;
  -webkit-transform: translateX(0);
  transform: translateX(0);
  -webkit-animation: dot 2.8s infinite;
  animation: dot 2.8s infinite;
}

.preloader-inner .dots {
  -webkit-transform: translateX(0);
  transform: translateX(0);
  margin-top: 12px;
  margin-left: 31px;
  -webkit-animation: dots 2.8s infinite;
  animation: dots 2.8s infinite;
}

.preloader-inner .dots span {
  display: block;
  float: left;
  width: 16px;
  height: 16px;
  margin-left: 16px;
  background: #0071f8;
  border-radius: 50%;
}



/* 
---------------------------------------------
Header Style
--------------------------------------------- 
*/

.background-header {
  background-color: #0071f8 !important;
  border-radius: 0px 0px 25px 25px;
  height: 80px!important;
  position: fixed!important;
  top: 0!important;
  left: 0;
  right: 0;
  box-shadow: 0px 0px 10px rgba(0,0,0,0.15)!important;
  -webkit-transition: all .5s ease 0s;
  -moz-transition: all .5s ease 0s;
  -o-transition: all .5s ease 0s;
  transition: all .5s ease 0s;
}

.background-header .logo img {
  max-width: 110px;
}

.header-area {
  position: absolute;
  background-color: transparent;
  top: 40px;
  left: 0;
  right: 0;
  z-index: 100;
  -webkit-transition: all .5s ease 0s;
  -moz-transition: all .5s ease 0s;
  -o-transition: all .5s ease 0s;
  transition: all .5s ease 0s;
}

.header-area .main-nav {
  background: transparent;
  display: flex;
}

.logo {
  margin-top: 15px;
}

.header-area .main-nav .logo {
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
  display: inline-block;
}

.header-area .main-nav .logo h1 {
  font-size: 36px;
  text-transform: uppercase;
  color: #fff;
  font-weight: 600;
  margin-right: 30px;
  padding-right: 30px;
  border-right: 1px solid rgba(250, 250, 250, 0.3);
}

.background-header .main-nav .logo{
  margin-top: 30px;
}

.header-area .main-nav ul.nav {
  border-radius: 0px 0px 25px 25px;
  flex-basis: 100%;
  margin-top: 10px;
  justify-content: right;
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
  position: relative;
  z-index: 999;
}

.header-area .main-nav .nav li:last-child {
  padding-right: 0px;
}

.header-area .main-nav .nav li {
  padding-left: 10px;
  padding-right: 10px;
  height: 40px;
  line-height: 40px;
}

.header-area .main-nav .nav li a {
  display: block;
  padding-left: 20px;
  padding-right: 20px;
  border-radius: 20px;
  font-weight: 300;
  font-size: 15px;
  height: 40px;
  line-height: 40px;
  text-transform: capitalize;
  color: #fff;
  -webkit-transition: all 0.4s ease 0s;
  -moz-transition: all 0.4s ease 0s;
  -o-transition: all 0.4s ease 0s;
  transition: all 0.4s ease 0s;
  border: transparent;
  letter-spacing: .25px;
}

/* .header-area .main-nav .nav li:last-child a {
  background-color: #000000;
  text-transform: uppercase;
  font-weight: 500;
} */

/* .header-area .main-nav .nav li:last-child:hover a {
  background-color: #ee626b;
} */

.header-area .main-nav .nav li:hover a {
  background-color: rgba(255, 255, 255, 0.10);
}

.header-area .main-nav .nav li a.active {
  color: #fff;
  background-color: #ee626b;
}

.background-header .main-nav .nav li a.active {
  color: #fff;
  background-color: #ee626b;
}

.header-area .main-nav .menu-trigger {
  cursor: pointer;
  position: absolute;
  top: 33px;
  width: 32px;
  height: 40px;
  text-indent: -9999em;
  z-index: 99;
  right: 20px;
  display: none;
}

.background-header .main-nav .menu-trigger {
  top: 22px;
}

.background-header .main-nav ul.nav {
  margin-top: 20px;
}

.header-area .main-nav .menu-trigger span,
.header-area .main-nav .menu-trigger span:before,
.header-area .main-nav .menu-trigger span:after {
  -moz-transition: all 0.4s;
  -o-transition: all 0.4s;
  -webkit-transition: all 0.4s;
  transition: all 0.4s;
  background-color: #fff;
  display: block;
  position: absolute;
  width: 30px;
  height: 2px;
  left: 0;
}

.header-area .main-nav .menu-trigger span:before,
.header-area .main-nav .menu-trigger span:after {
  -moz-transition: all 0.4s;
  -o-transition: all 0.4s;
  -webkit-transition: all 0.4s;
  transition: all 0.4s;
  background-color: #fff;
  display: block;
  position: absolute;
  width: 30px;
  height: 2px;
  left: 0;
  width: 75%;
}

.header-area .main-nav .menu-trigger span:before,
.header-area .main-nav .menu-trigger span:after {
  content: "";
}

.header-area .main-nav .menu-trigger span {
  top: 16px;
}

.header-area .main-nav .menu-trigger span:before {
  -moz-transform-origin: 33% 100%;
  -ms-transform-origin: 33% 100%;
  -webkit-transform-origin: 33% 100%;
  transform-origin: 33% 100%;
  top: -10px;
  z-index: 10;
}

.header-area .main-nav .menu-trigger span:after {
  -moz-transform-origin: 33% 0;
  -ms-transform-origin: 33% 0;
  -webkit-transform-origin: 33% 0;
  transform-origin: 33% 0;
  top: 10px;
}

.header-area .main-nav .menu-trigger.active span,
.header-area .main-nav .menu-trigger.active span:before,
.header-area .main-nav .menu-trigger.active span:after {
  background-color: transparent;
  width: 100%;
}

.header-area .main-nav .menu-trigger.active span:before {
  -moz-transform: translateY(6px) translateX(1px) rotate(45deg);
  -ms-transform: translateY(6px) translateX(1px) rotate(45deg);
  -webkit-transform: translateY(6px) translateX(1px) rotate(45deg);
  transform: translateY(6px) translateX(1px) rotate(45deg);
  background-color: #fff;
}

.background-header .main-nav .menu-trigger.active span:before {
  background-color: #fff;
}

.header-area .main-nav .menu-trigger.active span:after {
  -moz-transform: translateY(-6px) translateX(1px) rotate(-45deg);
  -ms-transform: translateY(-6px) translateX(1px) rotate(-45deg);
  -webkit-transform: translateY(-6px) translateX(1px) rotate(-45deg);
  transform: translateY(-6px) translateX(1px) rotate(-45deg);
  background-color: #fff;
}

.background-header .main-nav .menu-trigger.active span:after {
  background-color: #fff;
}

.header-area.header-sticky .nav li a.active {
  color: #fff;
}

.visible{
  display:inline !important;
}

@media (max-width: 1200px) {
  .header-area .main-nav .nav li {
    padding-left: 5px;
    padding-right: 5px;
  }

}

@media (max-width: 767px) {
  .background-header .main-nav {
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.15);
    border-radius: 0px 0px 25px 25px;
    width: 100%;
  }
  .background-header .main-nav .nav,
  .header-area .main-nav .nav {
    background-color: #fff;
  }
  .background-header .main-nav .nav li a,
  .header-area .main-nav .nav li a {
    line-height: 50px;
    height: 50px;
    font-weight: 400;
    color: #1e1e1e;
    background-color: #fff;
     border-radius: 0px 0px 25px 25px;
  }
  .background-header .main-nav .nav li,
  .header-area .main-nav .nav li {
    border-top: 1px solid #ddd;
    background-color: #f1f0fe;
    height: 50px;
    border-radius: 0px 0px 25px 25px;
  }
  .background-header .main-nav .nav li:last-child,
  .header-area .main-nav .nav li:last-child {
    border-radius: 0px 0px 25px 25px;
  }
  .header-area .main-nav .nav {
    height: auto;
    flex-basis: 100%;
  }
  .header-area .main-nav .logo {
    position: absolute;
    left: 30px;
    top: 0px;
  }
  .background-header .main-nav .logo {
    top: 0px;
  }
  .background-header .main-nav .border-button {
    top: 0px !important;
  }
  .header-area .main-nav .border-button {
    position: absolute;
    top: 15px;
    right: 70px;
  }
  .header-area.header-sticky .nav li a:hover,
  .header-area.header-sticky .nav li a.active {
    color: #000000!important;
    opacity: 1;
  }
  .header-area.header-sticky .nav li.search-icon a {
    width: 100%;
  }
  .header-area .nav li:last-child a {
    background-color: transparent !important;
    font-weight: 300 !important;
    text-transform: capitalize !important;
  }
  .header-area {
    background-color: transparent;
    padding: 0px 15px;
    height: 80px;
    box-shadow: none;
    text-align: center;
  }
  .header-area .container {
    padding: 0px;
  }
  .header-area .logo {
    margin-left: 0px;
    margin-top: 30px;
  }
  .header-area .menu-trigger {
    display: block !important;
  }
  .header-area .main-nav {
    overflow: hidden;
  }
  .header-area .main-nav .nav {
    float: none;
    width: 100%;
    display: none;
    -webkit-transition: all 0s ease 0s;
    -moz-transition: all 0s ease 0s;
    -o-transition: all 0s ease 0s;
    transition: all 0s ease 0s;
    margin-left: 0px;
  }
  .header-area .main-nav .nav li:first-child {
    border-top: 1px solid #eee;
  }
  .header-area.header-sticky .nav {
    margin-top: 100px !important;
  }
  .background-header.header-sticky .nav {
    margin-top: 80px !important;
  }
  .header-area .main-nav .nav li {
    width: 100%;
    background: #fff;
    padding-left: 0px !important;
    padding-right: 0px !important;
  }
  
}

/* 
---------------------------------------------
Banner Style
--------------------------------------------- 
*/

.main-banner {
  background-image: url(../images/banner-bg.jpg);
  border-radius: 0px 0px 150px 150px;
  background-position: center bottom;
  background-repeat: no-repeat;
  background-size: cover;
  padding: 225px 0px;
}

.main-banner .caption h6 {
  font-size: 20px;
  text-transform: uppercase;
  color: #fff;
  font-weight: 500;
  letter-spacing: 0.5px;
}

.main-banner .caption h2 {
  font-size: 48px;
  color: #fff;
  margin-top: 20px;
  position: relative;
  padding-bottom: 5px;
  margin-bottom: 40px;
}

.main-banner .caption h2:after {
  position: absolute;
  background-image: url(../images/caption-dec.png);
  width: 202px;
  height: 12px;
  content: '';
  left: 125px;
  bottom: 0;
}

.main-banner .caption p {
  color: #fff;
  margin-bottom: 70px;
}

.main-banner .caption form {
  position: relative;
  max-width: 450px;
}

.main-banner .caption form input {
  max-width: 450px;
  width: 100%;
  height: 50px;
  outline: none;
  border-radius: 25px;
  background-color: #fff;
  border: none;
  padding: 0px 25px;
  font-size: 14px;
  color: #7a7a7a;
}

.main-banner .caption form button {
  display: inline-block;
  height: 50px;
  line-height: 50px;
  background-color: #ee626b;
  color: #fff;
  font-size: 15px;
  text-transform: uppercase;
  font-weight: 500;
  padding: 0px 25px;
  border: none;
  border-radius: 25px;
  position: absolute;
  right: 0;
  top: 0;
  transition: all .3s;
}

.main-banner .caption form button:hover {
  background-color: #0071f8;
}

.main-banner .right-image {
  position: relative;
}

.main-banner .right-image img {
  border-radius: 25px;
}

.main-banner .right-image span.price {
  position: absolute;
  right: 20px;
  top: 20px;
  border-radius: 25px;
  background-color: #008af8;
  font-size: 22px;
  text-transform: uppercase;
  font-weight: 700;
  color: #fff;
  padding: 4px 15px;
}

.main-banner .right-image span.offer {
  position: absolute;
  left: -25px;
  bottom: -25px;
  border-radius: 50%;
  background-color: #ee626b;
  font-size: 28px;
  text-transform: uppercase;
  font-weight: 700;
  color: #fff;
  display: inline-block;
  width: 100px;
  height: 100px;
  text-align: center;
  line-height: 100px;
}



/* 
---------------------------------------------
Services Style
--------------------------------------------- 
*/

.features {
  margin-top: -80px;
}

.features .item {
  padding: 35px;
  box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.15);
  border-radius: 25px;
  background-color: #fff;
  text-align: center;
}

.features .item h4 {
  font-size: 17px;
  margin-top: 25px;
  text-transform: uppercase;
}

.features .item .image {
  width: 90px;
  height: 90px;
  display: inline-block;
  text-align: center;
  line-height: 90px;
  background-color: #0071f8;
  border-radius: 50%;
  transition: all .3s;
}

.features .item:hover .image {
  background-color: #ee626b;
}



/* 
---------------------------------------------
Trending Style
--------------------------------------------- 
*/

.trending .main-button {
  margin-top: 32px;
  text-align: right;
}

.trending .item  {
  background-color: #eeeeee;
  position: relative;
  overflow: hidden;
  border-radius: 25px;
  margin-bottom: 30px;
}

.trending .item .thumb {
  position: relative;
  border-radius: 25px;
  overflow: hidden;
}

.trending .item span.price em {
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  text-decoration: line-through;
  display: block;
}

.trending .item span.price {
  text-align: right;
  position: absolute;
  right: 20px;
  top: 20px;
  border-radius: 10px;
  background-color: #008af8;
  font-size: 17px;
  text-transform: uppercase;
  font-weight: 600;
  color: #fff;
  padding: 8px 15px 6px 15px;
}

.trending .item .down-content {
  padding: 25px;
}

.trending .item .down-content span.category {
  font-size: 14px;
  color: #7a7a7a;
  margin-bottom: 5px;
  display: inline-block;
}

.trending .item .down-content h4 {
  font-size: 17px;
  font-weight: 600;
  transition: all .3s;
}

.trending .item .down-content a {
  position: absolute;
  display: inline-block;
  text-align: center;
  line-height: 40px;
  width: 40px;
  height: 40px;
  background-color: #ee626b;
  color: #fff;
  border-radius: 50%;
  right: 25px;
  bottom: 25px;
  transition: all .3s;
}

.trending .item:hover .down-content h4 {
  color: #0071f8;
}

.trending .item:hover .down-content a {
  background-color: #0071f8;
}


/* 
---------------------------------------------
Most Played Style
--------------------------------------------- 
*/

.most-played {
  background-color: #f7f7f7;
  padding: 100px 0px;
  border-radius: 150px;
}

.most-played .main-button {
  margin-top: 32px;
  text-align: right;
}

.most-played .item  {
  background-color: #fff;
  position: relative;
  border-radius: 25px;
  text-align: center;
  margin-bottom: 40px;
}

.most-played .item .thumb {
  position: relative;
  border-radius: 25px;
  overflow: hidden;
}

.most-played .item .down-content {
  padding: 20px 15px 40px 15px;
}

.most-played .item .down-content span.category {
  font-size: 14px;
  color: #7a7a7a;
  margin-bottom: 5px;
  display: inline-block;
}

.most-played .item .down-content h4 {
  font-size: 17px;
  font-weight: 600;
  transition: all .3s;
}

.most-played .item .down-content a {
  position: absolute;
  display: inline-block;
  text-align: center;
  line-height: 40px;
  height: 40px;
  padding: 0px 15px;
  background-color: #ee626b;
  color: #fff;
  border-radius: 20px;
  font-size: 15px;
  text-transform: uppercase;
  font-weight: 600;
  left: 50%;
  transform: translateX(-50%);
  bottom: -20px;
  transition: all .3s;
}

.most-played .item:hover .down-content h4 {
  color: #0071f8;
}

.most-played .item:hover .down-content a {
  background-color: #0071f8;
}


/* 
---------------------------------------------
Categories Style
--------------------------------------------- 
*/

.categories .main-button {
  margin-top: 30px;
}

.categories .item  {
  background-color: #0071f8;
  position: relative;
  border-radius: 25px;
  text-align: center;
  margin-bottom: 30px;
}

.categories .item .thumb {
  position: relative;
  border-radius: 25px;
  overflow: hidden;
}

.categories .item h4 {
  font-size: 17px;
  font-weight: 600;
  color: #fff;
  padding: 22px;
  margin-bottom: 0px;
}

/* 
---------------------------------------------
CTA Style
--------------------------------------------- 
*/

.cta {
  position: relative;
}

.cta::after {
  background-image: url(../images/);
  max-width: 550px;
  max-height: 510px;
  width: 100%;
  height: 100%;
  position: absolute;
  content: '';
  border-radius: 25px;
  left: 50%;
  transform: translateX(-275px);
  top: 0;
  z-index: -1;
}

.cta .shop {
  margin-top: 80px;
  background-color: #f7f7f7;
  border-radius: 25px;
  padding: 80px;
}

.cta .shop .section-heading {
  margin-right: 30px;
  margin-bottom: 50px;
}

.cta .shop p {
  font-weight: 600;
  font-size: 16px;
}

.cta .shop .main-button {
  margin-top: 50px;
}

.cta .subscribe {
  background-color: #f7f7f7;
  border-radius: 25px;
  padding: 80px 60px;
}

.cta .subscribe .section-heading {
  margin-bottom: 50px;
}

.cta .subscribe form {
  position: relative;
  max-width: 100%;
}

.cta .subscribe form input {
  max-width: 100%;
  width: 100%;
  height: 50px;
  outline: none;
  border-radius: 25px;
  background-color: #fff;
  border: none;
  padding: 0px 25px;
  font-size: 14px;
  color: #7a7a7a;
}

.cta .subscribe form button {
  display: inline-block;
  height: 50px;
  line-height: 50px;
  background-color: #ee626b;
  color: #fff;
  font-size: 15px;
  text-transform: uppercase;
  font-weight: 500;
  padding: 0px 25px;
  border: none;
  border-radius: 25px;
  position: absolute;
  right: 0;
  top: 0;
  transition: all .3s;
}

.cta .subscribe form button:hover {
  background-color: #0071f8;
}


/* 
---------------------------------------------
Footer Style
--------------------------------------------- 
*/

footer {
  margin-top: 300px;
  background-color: #0071f8;
  background-repeat: no-repeat;
  background-size: cover;
  background-image: url(../images/footer-bg.jpg);
  min-height: 150px;
  border-radius: 150px 150px 0px 0px;
}

footer p {
  text-align: center;
  line-height: 90px;
  color: #fff;
  font-size: 16px;
  font-weight: 400;
}

footer p a {
  color: #fff;
  transition: all .3s;
  position: relative;
  z-index: 3;
}

footer p a:hover {
  opacity: 0.75;
}


/* 
---------------------------------------------
Page Header Style
--------------------------------------------- 
*/

.page-heading {
  background-image: url(../images/page-heading-bg.jpg);
  border-radius: 0px 0px 150px 150px;
  background-position: center bottom;
  background-repeat: no-repeat;
  background-size: cover;
  padding: 200px 0px 100px 0px;
  text-align: center;
}

.page-heading span {
  display: inline-block;
  font-size: 16px;
  color: #fff;
}

.page-heading span a {
  color: #fff;
}

.page-heading h3 {
  font-size: 48px;
  text-transform: uppercase;
  color: #fff;
  margin-top: 20px;
  position: relative;
  margin-bottom: 20px;
}


/* 
---------------------------------------------
Shop Page Style
--------------------------------------------- 
*/

.trending ul.trending-filter {
  list-style: none;
  text-align: center;
  margin-bottom: 70px;
}

.trending ul.trending-filter li {
  display: inline-block;
  margin: 5px 8px;
}

.trending ul.trending-filter li a {
  display: inline-block;
  text-align: center;
  font-size: 15px;
  text-transform: uppercase;
  font-weight: 600;
  color: #1e1e1e;
  background-color: #eee;
  padding: 8px 20px;
  border-radius: 25px;
  transition: all .3s;
}

.trending ul.trending-filter li a.is_active {
  background-color: #ee626b;
  color: #fff;
}

.trending ul.trending-filter li a.is_active:hover {
  color: #fff;
}

.trending ul.trending-filter li a:hover {
  color: #ee626b;
}

.trending-box .item  {
  background-color: #eeeeee;
  position: relative;
  overflow: hidden;
  border-radius: 25px;
  margin-bottom: 30px;
}

.trending-box .item .thumb {
  position: relative;
  border-radius: 25px;
  overflow: hidden;
}

.trending-box .item span.price em {
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  text-decoration: line-through;
  display: block;
}

.trending-box .item span.price {
  text-align: right;
  position: absolute;
  right: 20px;
  top: 20px;
  border-radius: 10px;
  background-color: #008af8;
  font-size: 17px;
  text-transform: uppercase;
  font-weight: 600;
  color: #fff;
  padding: 8px 15px 6px 15px;
}

.trending-box .item .down-content {
  padding: 25px;
}

.trending-box .item .down-content span.category {
  font-size: 14px;
  color: #7a7a7a;
  margin-bottom: 5px;
  display: inline-block;
}

.trending-box .item .down-content h4 {
  font-size: 17px;
  font-weight: 600;
  transition: all .3s;
}

.trending-box .item .down-content a {
  position: absolute;
  display: inline-block;
  text-align: center;
  line-height: 40px;
  width: 40px;
  height: 40px;
  background-color: #ee626b;
  color: #fff;
  border-radius: 50%;
  right: 25px;
  bottom: 25px;
  transition: all .3s;
}

.trending-box .item:hover .down-content h4 {
  color: #0071f8;
}

.trending-box .item:hover .down-content a {
  background-color: #0071f8;
}

.trending ul.pagination {
  margin-top: 50px;
  text-align: center;
  width: 100%;
  display: inline-block;
}

.trending ul.pagination li {
  display: inline-block;
  margin: 0px 5px;
}

.trending ul.pagination li a {
  display: inline-block;
  width: 40px;
  height: 40px;
  line-height: 40px;
  text-align: center;
  background-color: #eee;
  color: #1e1e1e;
  font-size: 15px;
  font-weight: 600;
  border-radius: 50%;
  transition: all .3s;
}

.trending ul.pagination li a:hover,
.trending ul.pagination li a.is_active {
  background-color: #0071f8;
  color: #fff;
}


/* 
---------------------------------------------
Single Page Style
--------------------------------------------- 
*/

.single-product .sep {
  width: 100%;
  height: 1px;
  background-color: #eee;
  margin: 80px 0px;
}

.single-product .left-image {
  margin-right: 80px;
}

.single-product .left-image img {
  border-radius: 25px;
}

.single-product h4 {
  font-size: 27px;
  margin-bottom: 20px;
}

.single-product span.price {
  font-size: 27px;
  font-weight: 700;
  color: #0071f8;
}

.single-product span.price em {
  font-style: normal;
  color: #c8c8c8;
  font-size: 17px;
  text-decoration: line-through;
  font-weight: 500;
  margin-right: 5px;
}

.single-product p {
  margin-top: 50px;
  margin-bottom: 60px;
}

.single-product form input {
  width: 80px;
  height: 50px;
  background-color: #f7f7f7;
  border: 1px solid #e7e7e7;
  border-radius: 25px;
  text-align: center;
  float: left;
  margin-right: 15px;
}

.single-product form {
  display: inline;
}

.single-product form button {
  display: inline-block;
  height: 50px;
  line-height: 50px;
  background-color: #ee626b;
  color: #fff;
  font-size: 15px;
  text-transform: uppercase;
  font-weight: 500;
  padding: 0px 25px;
  border: none;
  border-radius: 25px;
  transition: all .3s;
}

.single-product form button i {
  margin-right: 5px;
}

.single-product form button:hover {
  background-color: #0071f8;
}

.single-product ul {
  margin-top: 60px;
}

.single-product ul li {
  display: block;
  margin: 20px 0px;
  font-size: 14px;
  color: #0071f8;
}

.single-product ul li:last-child {
  margin-bottom: 0px;
}

.single-product ul li span {
  width: 120px;
  display: inline-block;
  color: #aaa;
}

.tabs-content {
  background-color: #f7f7f7;
  border-radius: 25px;
  padding: 60px;
  transition: all 0.3s;
}

.tabs-content .nav-link {
  border: none;
  border-radius: 0px;
  background-color: transparent !important;
  font-size: 20px;
  font-weight: 600;
  color: #1e1e1e;
  padding: 0px;
}

.tabs-content ul.nav-tabs {
  border-bottom: none;
}

.tabs-content ul.nav-tabs li {
  border-right: 1px solid #d7d7d7;
  margin-right: 30px;
  padding-right: 30px;
}

.tabs-content ul.nav-tabs li:last-child {
  border-right: none;
  margin-right: 0px;
  padding-right: 0px;
}

.tabs-content .nav-tabs .nav-link.active {
  color: #0071f8;
}

.tabs-content .tab-content {
  margin-top: 30px;
}

.related-games .main-button {
  text-align: right;
  margin-top: 32px;
}


/* 
---------------------------------------------
Contact PAge Style
--------------------------------------------- 
*/

.contact-page .left-text {
  background-color: #f7f7f7;
  border-radius: 25px;
  padding: 60px;
}

.contact-page .left-text .section-heading {
  margin-bottom: 50px;
}

.contact-page .left-text p {
  margin-bottom: 50px;
}

.contact-page .left-text ul li {
  display: block;
  font-size: 16px;
  color: #aaaaaa;
  font-size: 300;
  margin-bottom: 30px;
}

.contact-page .left-text ul li:last-child {
  margin-bottom: 0px;
}

.contact-page .left-text ul li span {
  display: block;
  font-size: 14px;
  font-weight: 600;
  color: #4a4a4a;
  margin-bottom: 5px;
}

.contact-page .right-content {
  margin-left: 50px;
}

.contact-page .right-content #map {
  margin-bottom: 60px;
}

.contact-page .right-content form input {
  width: 100%;
  height: 50px;
  border-radius: 25px;
  padding: 0px 20px;
  background-color: #f7f7f7;
  border: 1px solid #e7e7e7;
  font-size: 14px;
  color: #4a4a4a;
  margin-bottom: 30px;
}

.contact-page .right-content form textarea {
  width: 100%;
  height: 130px;
  border-radius: 25px;
  padding: 20px 20px;
  background-color: #f7f7f7;
  border: 1px solid #e7e7e7;
  font-size: 14px;
  color: #4a4a4a;
  margin-bottom: 30px;
}

.contact-page .right-content form button {
  display: inline-block;
  height: 50px;
  line-height: 50px;
  background-color: #ee626b;
  color: #fff;
  font-size: 15px;
  text-transform: uppercase;
  font-weight: 500;
  padding: 0px 25px;
  border: none;
  border-radius: 25px;
  transition: all .3s;
}

.contact-page .right-content form button:hover {
  background-color: #0071f8;
}

/* 
---------------------------------------------
Responsive Style
--------------------------------------------- 
*/

body {
  overflow-x: hidden;
}

@media (max-width: 767px) {
  .header-area {
    top: 0;
  }
  .main-banner .right-image span.offer {
    left: 20px;
    bottom: 20px;
  }
  .cta .subscribe form button {
    position: relative;
    width: 100%;
    margin-top: 15px;
  }
}

@media (max-width: 992px) {
  .header-area .main-nav .logo img {
    max-width: 110px;
  }
  .header-area .main-nav .nav li a {
    padding-left: 10px;
    padding-right: 10px;
  }
  .header-area .main-nav ul.nav {
    margin-top: 0px;
  }
  .background-header .main-nav ul.nav {
    margin-top: 20px;
  }
  .main-banner .caption {
    margin-bottom: 45px;
    text-align: center;
  }
  .main-banner .caption form,
  .main-banner .caption form input {
    max-width: 100%;
  }
  .features .item {
    margin-bottom: 30px;
  }
  .trending .main-button,
  .cta::after,
  .most-played .main-button,
  .related-games .main-button {
    display: none;
  }
  .most-played .section-heading {
    text-align: center;
  }
  .cta .shop {
    padding: 30px;
    margin-bottom: 30px;
  }
  .cta .subscribe {
    padding: 30px;
  }
  .cta .shop .section-heading {
    margin-right: 0px;
  }
  .trending ul.trending-filter li a {
    font-size: 13px;
    padding: 8px 10px;
  }
  .trending ul.trending-filter li {
    margin: 5px 2px;
  }
  .single-product .left-image {
    margin-right: 0px;
    margin-bottom: 45px;
  }
  .tabs-content .nav-link {
    font-size: 16px;
  }
  .tabs-content ul.nav-tabs li {
    margin-right: 15px;
    padding-right: 15px;
  }
  .page-heading {
    padding: 140px 0px 100px 0px;
  }
  .contact-page .right-content {
    margin-left: 0px;
    margin-top: 45px;
  }
}

@media (max-width: 1200px) {
  
}

html {
  box-sizing: border-box;
  background: #f3f3f3;
}

*,
*:after,
*:before {
  box-sizing: inherit;
}

.clip {
  border: 0;
  clip: rect(0 0 0 0);
  height: 1px;
  margin: -1px;
  overflow: hidden;
  padding: 0;
  position: absolute;
  width: 1px;
}

.svg--source {
  display: none
}

.svg--icon {
  width: 100%;
  max-width: 5rem;
  height: 100%;
  max-height: 5rem;
  display: block;
  margin: 0 auto;
  fill: currentColor
}

.wrapper {
  width: 100%;
  height: 100vh;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
  padding: 1rem;
}

.share {
  width: 5rem;
  height: 5rem;
  float: left;
  margin: .5rem 1rem .5rem 0;
  color: #353c4a;
  border: .125rem solid #f3f3f3;
  box-shadow: 0 0 8px 0 rgba(50, 50, 50, 0.15);
  border-radius: 50%;
  transition: 250ms;
  
  &:last-child {
    margin-right: 0
  }
  
  &:hover,
  &:focus {
    //background: #f1f1f1;
  }
  
  &:focus {
    outline-color: inherit;
  }
}

.twitter {
  &:hover,
  &:focus {
    color: #00ACED;
    box-shadow: 0 0 24px 0 #00ACED
  }
}

.github {
  &:hover,
  &:focus {
    color: #4183c4;
    box-shadow: 0 0 24px 0 #4183c4
  }
}

.pinterest {
  &:hover,
  &:focus {
    color: #bd081c;
    box-shadow: 0 0 24px 0 #bd081c
  }
}

.youtube {
  &:hover,
  &:focus {
    color: #cd201f;
    box-shadow: 0 0 24px 0 #cd201f
  }
}

.facebook {
  &:hover,
  &:focus {
    color: #3b5998;
    box-shadow: 0 0 24px 0 #3b5998
  }
}

.google {
  &:hover,
  &:focus {
    color: #dd4b39;
    box-shadow: 0 0 24px 0 #dd4b39
  }
}

    </style>



-->
  </head>

<body>

  <!-- ***** Preloader Start ***** -->
  <div id="js-preloader" class="js-preloader">
    <div class="preloader-inner">
      <span class="dot"></span>
      <div class="dots">
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div>
  </div>
  <!-- ***** Preloader End ***** -->

  <!-- ***** Header Area Start ***** -->
  <header class="header-area header-sticky">
    <div class="container">
        <div class="row">
            <div class="col-12">
                <nav class="main-nav">
                    <!-- ***** Logo Start ***** -->
                    <a href="index.html" class="logo">
                        <img src="assets/images/logo.png" alt="" style="width: 158px;">
                    </a>
                    <!-- ***** Logo End ***** -->
                    <!-- ***** Menu Start ***** -->
                    <ul class="nav">
                      <li><a href="index.html" class="active">Home</a></li>
                      <li><a href="about.html">About</a></li>
                      <li><a href="project.html">Project</a></li>
                      <li><a href="contact.html">Contact</a></li>
                      <!-- <li><a href="#">Sign In</a></li> -->
                  </ul>   
                    <a class='menu-trigger'>
                        <span>Menu</span>
                    </a>
                    <!-- ***** Menu End ***** -->
                </nav>
            </div>
        </div>
    </div>
  </header>
  <!-- ***** Header Area End ***** -->

  <div class="main-banner">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 align-self-center">
          <div class="caption header-text">
            <h6>Welcome to my website</h6>
            <h2>About my self</h2>
            <p>Hello my name is <span style="font-weight: bold; color: black;">Tangguh Lambang Wibawa</span>, i was born in the city of South Tangerang in 2008 August 18th, i am the 2nd child of 3 siblings, my favorite food is meat, my favorite drink is milk, my hobby is sports, but not all sports I like, the ones I like are <span style="color: black; font-weight: bold;">ArmWrestling</span>, Calisthenic, Swimming and Weight lifting.</p>
            <div class="search-input">
              <form id="search" action="#">
                <!-- <input type="text" placeholder="Type Something" id='searchText' name="searchKeyword" onkeypress="handle" /> -->
                <button role="button" style="margin-right: 300px;"><a href="contact.html" style="color: white;">My Contact</a></button>
              </form>
            </div>
          </div>
        </div>
        <div class="col-lg-4 offset-lg-2">
          <div class="right-image">
            <img src="assets/images/Tangguh12.jpg" alt="">
            <span class="price">Tangguh</span>
            <span class="offer">16 y.o</span>
          </div>
        </div>
      </div>
    </div>
  </div>
  <h6 style="margin-left: 110px; margin-top: 60px; color: #ee626b;">My Daily</h6>
<h1 style="margin-left: 110px; margin-top: 20px;">Activity & Principle </h1>
<br>
<br>
<br><br><br><br><br>
  <div class="features">
    <div class="container">
      <div class="row">
        <div class="col-lg-3 col-md-6">
          <a href="https://id.wikipedia.org/wiki/Pacaran#:~:text=Pacaran%20%28bahasa%20Inggris%20%3A%20courtship%29%20adalah%20periode%20perkenalan,dimulai%20setelah%20pertunangan%20dan%20dapat%20berakhir%20dengan%20perkawinan.">
            <div class="item">
              <div class="image">
                <img src="assets/images/love1.webp" alt="" style="max-width: 44px;">
              </div>
              <h4>Relationship</h4>
            </div>
          </a>
        </div>
        <div class="col-lg-3 col-md-6">
          <a href="https://www.kompasiana.com/nursyamsir/6294f94abb44861e09018bf2/opini-memahami-privat-life-dalam-lingkup-hermeneutika-sosial">
            <div class="item">
              <div class="image">
                <img src="assets/images/lock1.webp" alt="" style="max-width: 44px;">
              </div>
              <h4>Private Life</h4>
            </div>
          </a>
        </div>
        <div class="col-lg-3 col-md-6">
          <a href="https://daftarkampus.spmb.teknokrat.ac.id/apa-itu-belajar-pengertian-proses-dan-pentingnya-dalam-kehidupan/#:~:text=Belajar%20dapat%20didefinisikan%20sebagai%20proses%20memperoleh%20pengetahuan%2C%20keterampilan%2C,di%20sekolah%2C%20tetapi%20juga%20berlangsung%20sepanjang%20hidup%20kita.">
            <div class="item">
              <div class="image">
                <img src="assets/images/book1.webp" alt="" style="max-width: 44px;">
              </div>
              <h4>Studying</h4>
            </div>
          </a>
        </div>
        <div class="col-lg-3 col-md-6">
          <a href="https://health.detik.com/kebugaran/d-6905113/workout-adalah-definisi-jenis-jenis-dan-cara-melakukannya">
            <div class="item">
              <div class="image">
                <img src="assets/images/dumble1.webp" alt="" style="max-width: 44px;">
              </div>
              <h4>Workout</h4>
            </div>
          </a>
        </div>
      </div>
    </div>
  </div>

  <div class="section trending">
    <div class="container">
      <div class="row">
        <div class="col-lg-6">
          <div class="section-heading">
            <h6> My Hobby</h6>
            <h2>Many Picture of My Hobby</h2>
          </div>
        </div>
        <div class="col-lg-6">
          <div class="main-button">
            <a href="https://en-m-wikipedia-org.translate.goog/wiki/Arm_wrestling?_x_tr_sl=en&_x_tr_tl=id&_x_tr_hl=id&_x_tr_pto=tc" style="font-size: 50px; font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif; letter-spacing: 10px; background: url(assets/images/fireGif.gif); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-position: bottom; -webkit-text-stroke: 0.2px black;">ArmWrestling</a>
          </div>
        </div>
        <div class="col-lg-3 col-md-6">
          <div class="item">
            <div class="thumb">
              <a href=""><img src="assets/images/zBSD2.jpg" alt=""></a>
              <!-- <span class="price"><em>$28</em>$20</span> -->
            </div>
            <div class="down-content">
              <span class="category">WillFitness BSD</span>
              <h4> Got 2nd Place ArmWrestling Event</h4>
              <br>
              <!-- <a href=""><i class="fa fa-shopping-bag"></i></a> -->
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6">
          <div class="item">
            <div class="thumb">
              <a href=""><img src="assets/images/zDepok3.jpg" alt=""></a>
              <!-- <span class="price">$44</span> -->
            </div>
            <div class="down-content">
              <span class="category">Red Steak Cafe Depok</span>
              <h4>Photo With 2 Seniors ArmWrestler</h4>
              <br>
              <!-- <a href=""><i class="fa fa-shopping-bag"></i></a> -->
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6">
          <div class="item">
            <div class="thumb">
              <a href=""><img src="assets/images/zDepok4.jpg" alt=""></a>
              <!-- <span class="price"><em>$64</em>$44</span> -->
            </div>
            <div class="down-content">
              <span class="category">Red Steak Cafe Depok</span>
              <h4>Photo With My Idol Class -63kg</h4>
              <br>
              <!-- <a href="product-details.html"><i class="fa fa-shopping-bag"></i></a> -->
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6">
          <div class="item">
            <div class="thumb">
              <a href=""><img src="assets/images/zRefit1.jpg" alt=""></a>
              <!-- <span class="price">$32</span> -->
            </div>
            <div class="down-content">
              <span class="category">Refit Gym Cimone</span>
              <h4> My First ArmWrestling Competition And Got 3rd Place</h4>
              <!-- <a href="product-details.html"><i class="fa fa-shopping-bag"></i></a> -->
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- <div class="section most-played">
    <div class="container">
      <div class="row">
        <div class="col-lg-6">
          <div class="section-heading">
            <h6>TOP GAMES</h6>
            <h2>Most Played</h2>
          </div>
        </div>
        <div class="col-lg-6">
          <div class="main-button">
            <a href="shop.html">View All</a>
          </div>
        </div>
        <div class="col-lg-2 col-md-6 col-sm-6">
          <div class="item">
            <div class="thumb">
              <a href="product-details.html"><img src="assets/images/top-game-01.jpg" alt=""></a>
            </div>
            <div class="down-content">
                <span class="category">Adventure</span>
                <h4>Assasin Creed</h4>
                <a href="product-details.html">Explore</a>
            </div>
          </div>
        </div>
        <div class="col-lg-2 col-md-6 col-sm-6">
          <div class="item">
            <div class="thumb">
              <a href="product-details.html"><img src="assets/images/top-game-02.jpg" alt=""></a>
            </div>
            <div class="down-content">
                <span class="category">Adventure</span>
                <h4>Assasin Creed</h4>
                <a href="product-details.html">Explore</a>
            </div>
          </div>
        </div>
        <div class="col-lg-2 col-md-6 col-sm-6">
          <div class="item">
            <div class="thumb">
              <a href="product-details.html"><img src="assets/images/top-game-03.jpg" alt=""></a>
            </div>
            <div class="down-content">
                <span class="category">Adventure</span>
                <h4>Assasin Creed</h4>
                <a href="product-details.html">Explore</a>
            </div>
          </div>
        </div>
        <div class="col-lg-2 col-md-6 col-sm-6">
          <div class="item">
            <div class="thumb">
              <a href="product-details.html"><img src="assets/images/top-game-04.jpg" alt=""></a>
            </div>
            <div class="down-content">
                <span class="category">Adventure</span>
                <h4>Assasin Creed</h4>
                <a href="product-details.html">Explore</a>
            </div>
          </div>
        </div>
        <div class="col-lg-2 col-md-6 col-sm-6">
          <div class="item">
            <div class="thumb">
              <a href="product-details.html"><img src="assets/images/top-game-05.jpg" alt=""></a>
            </div>
            <div class="down-content">
                <span class="category">Adventure</span>
                <h4>Assasin Creed</h4>
                <a href="product-details.html">Explore</a>
            </div>
          </div>
        </div>
        <div class="col-lg-2 col-md-6 col-sm-6">
          <div class="item">
            <div class="thumb">
              <a href="product-details.html"><img src="assets/images/top-game-06.jpg" alt=""></a>
            </div>
            <div class="down-content">
                <span class="category">Adventure</span>
                <h4>Assasin Creed</h4>
                <a href="product-details.html">Explore</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div> -->

  <!-- <div class="section categories">
    <div class="container">
      <div class="row">
        <div class="col-lg-12 text-center">
          <div class="section-heading">
            <h6>Categories</h6>
            <h2>Top Categories</h2>
          </div>
        </div>
        <div class="col-lg col-sm-6 col-xs-12">
          <div class="item">
            <h4>Action</h4>
            <div class="thumb">
              <a href="product-details.html"><img src="assets/images/categories-01.jpg" alt=""></a>
            </div>
          </div>
        </div>
        <div class="col-lg col-sm-6 col-xs-12">
          <div class="item">
            <h4>Action</h4>
            <div class="thumb">
              <a href="product-details.html"><img src="assets/images/categories-05.jpg" alt=""></a>
            </div>
          </div>
        </div>
        <div class="col-lg col-sm-6 col-xs-12">
          <div class="item">
            <h4>Action</h4>
            <div class="thumb">
              <a href="product-details.html"><img src="assets/images/categories-03.jpg" alt=""></a>
            </div>
          </div>
        </div>
        <div class="col-lg col-sm-6 col-xs-12">
          <div class="item">
            <h4>Action</h4>
            <div class="thumb">
              <a href="product-details.html"><img src="assets/images/categories-04.jpg" alt=""></a>
            </div>
          </div>
        </div>
        <div class="col-lg col-sm-6 col-xs-12">
          <div class="item">
            <h4>Action</h4>
            <div class="thumb">
              <a href="product-details.html"><img src="assets/images/categories-05.jpg" alt=""></a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div> -->
  
  <!-- <div class="section cta">
    <div class="container">
      <div class="row">
        <div class="col-lg-5">
          <div class="shop">
            <div class="row">
              <div class="col-lg-12">
                <div class="section-heading">
                  <h6>Our Shop</h6>
                  <h2>Go Pre-Order Buy & Get Best <em>Prices</em> For You!</h2>
                </div>
                <p>Lorem ipsum dolor consectetur adipiscing, sed do eiusmod tempor incididunt.</p>
                <div class="main-button">
                  <a href="shop.html">Shop Now</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-5 offset-lg-2 align-self-end">
          <div class="subscribe">
            <div class="row">
              <div class="col-lg-12">
                <div class="section-heading">
                  <h6>NEWSLETTER</h6>
                  <h2>Get Up To $100 Off Just Buy <em>Subscribe</em> Newsletter!</h2>
                </div>
                <div class="search-input">
                  <form id="subscribe" action="#">
                    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Your email...">
                    <button type="submit">Subscribe Now</button>
                  </form>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div> -->
  <h1 style="text-align: center; font-size: small; background-color: #ee626b; color: rgb(255, 255, 255); margin-top: 120px; padding: 30px;">*Better Open This Web Using Dekstop, For Phone Using Dekstop Mode*</h1>

  <footer>
    <div class="container" style="margin-top: -100px;">
      <div class="col-lg-12">
        <p>Copyright © Tangguh. All rights reserved.</p>
      </div>
    </div>
  </footer>

  <!-- Scripts -->
  <!-- Bootstrap core JavaScript -->
  <script src="vendor/jquery/jquery.min.js"></script>
  <script src="vendor/bootstrap/js/bootstrap.min.js"></script>
  <script src="assets/js/isotope.min.js"></script>
  <script src="assets/js/owl-carousel.js"></script>
  <script src="assets/js/counter.js"></script>
  <script src="assets/js/custom.js"></script>

  </body>
</html>
