# electrochip.github.io
css code
body {
  font-family: "Poppins", sans-serif;
  color: #0c0c0c;
  background-color: #ffffff;
}

.layout_padding {
  padding-top: 90px;
  padding-bottom: 90px;
}

.layout_padding2 {
  padding-top: 45px;
  padding-bottom: 45px;
}

.layout_padding2-top {
  padding-top: 45px;
}

.layout_padding2-bottom {
  padding-bottom: 45px;
}

.layout_padding-top {
  padding-top: 90px;
}

.layout_padding-bottom {
  padding-bottom: 90px;
}

.heading_container {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: start;
      -ms-flex-pack: start;
          justify-content: flex-start;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  text-align: center;
}

.heading_container h2 {
  position: relative;
  font-weight: bold;
  margin-right: 10px;
}

.heading_container img {
  width: 30px;
}

/*header section*/
.hero_area {
  height: 98vh;
  position: relative;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  background-color: #eae6f5;
}

.sub_page .hero_area {
  height: auto;
}

.header_section .container {
  padding: 0;
}

.header_section .nav_container {
  margin: 0 auto;
}

.custom_nav-container .navbar-nav .nav-item .nav-link {
  padding: 7px 20px;
  margin: 10px 15px;
  color: #000000;
  text-align: center;
  border-radius: 35px;
  text-transform: uppercase;
  font-size: 15px;
}

.custom_nav-container .navbar-nav .nav-item.active .nav-link, .custom_nav-container .navbar-nav .nav-item:hover .nav-link {
  background-color: #4b208c;
  color: #ffffff;
}

a,
a:hover,
a:focus {
  text-decoration: none;
}

a:hover,
a:focus {
  color: initial;
}

.btn,
.btn:focus {
  outline: none !important;
  -webkit-box-shadow: none;
          box-shadow: none;
}

.custom_nav-container .nav_search-btn {
  background-image: url(../images/search-icon.png);
  background-size: 22px;
  background-repeat: no-repeat;
  background-position-y: 7px;
  width: 35px;
  height: 35px;
  padding: 0;
  border: none;
}

.navbar-brand {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}

.navbar-brand img {
  margin-right: 5px;
  width: 35px;
}

.navbar-brand span {
  font-size: 22px;
  font-weight: 700;
  color: #4b208c;
}

.custom_nav-container {
  z-index: 99999;
}

.navbar-expand-lg .navbar-collapse {
  -webkit-box-align: end;
      -ms-flex-align: end;
          align-items: flex-end;
}

.custom_nav-container .navbar-toggler {
  outline: none;
}

.custom_nav-container .navbar-toggler {
  padding: 0;
  width: 37px;
  height: 42px;
}

.custom_nav-container .navbar-toggler span {
  display: block;
  width: 35px;
  height: 4px;
  background-color: #190734;
  margin: 7px 0;
  -webkit-transition: all .3s;
  transition: all .3s;
}

.custom_nav-container .navbar-toggler[aria-expanded="true"] .s-1 {
  -webkit-transform: rotate(45deg);
          transform: rotate(45deg);
  margin: 0;
  margin-bottom: -4px;
}

.custom_nav-container .navbar-toggler[aria-expanded="true"] .s-2 {
  display: none;
}

.custom_nav-container .navbar-toggler[aria-expanded="true"] .s-3 {
  -webkit-transform: rotate(-45deg);
          transform: rotate(-45deg);
  margin: 0;
  margin-top: -4px;
}

.custom_nav-container .navbar-toggler[aria-expanded="false"] .s-1,
.custom_nav-container .navbar-toggler[aria-expanded="false"] .s-2,
.custom_nav-container .navbar-toggler[aria-expanded="false"] .s-3 {
  -webkit-transform: none;
          transform: none;
}

/*end header section*/
/* slider section */
.slider_section {
  -webkit-box-flex: 1;
      -ms-flex: 1;
          flex: 1;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  position: relative;
  z-index: 2;
  color: #3b3a3a;
  padding-bottom: 90px;
}

.slider_section .row {
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}

.slider_section .detail_box {
  color: #000000;
}

.slider_section .detail_box h1 {
  text-transform: uppercase;
  font-weight: bold;
}

.slider_section .detail_box p {
  margin-top: 20px;
}

.slider_section .detail_box a {
  display: inline-block;
  padding: 10px 40px;
  background-color: #4b208c;
  color: #ffffff;
  border-radius: 35px;
  margin-top: 35px;
}

.slider_section .detail_box a:hover {
  background-color: #5625a1;
}

.slider_section .img_container {
  border: 7px solid #7b57b2;
  border-radius: 100%;
  overflow: hidden;
}

.slider_section .img_container div#carouselExampleContarols {
  width: 100%;
  position: unset;
}

.slider_section .img_container .img-box img {
  width: 100%;
}

.slider_section .carousel-control-prev,
.slider_section .carousel-control-next {
  top: initial;
  left: initial;
  bottom: 5%;
  right: 10%;
  width: 45px;
  height: 45px;
  border: none;
  border-radius: 100%;
  opacity: 1;
  background-repeat: no-repeat;
  background-size: 8px;
  background-position: center;
}

.slider_section .carousel-control-prev {
  background-image: url(../images/prev.png);
  background-color: #ffffff;
  -webkit-transform: translate(-85px, 30px);
          transform: translate(-85px, 30px);
}

.slider_section .carousel-control-next {
  background-image: url(../images/next.png);
  background-color: #4b208c;
  -webkit-transform: translate(-45px, 0);
          transform: translate(-45px, 0);
}

.service_section {
  text-align: center;
}

.service_section .heading_container {
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
}

.service_section .service_container {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
  padding: 35px 0;
  -ms-flex-wrap: wrap;
      flex-wrap: wrap;
}

.service_section .service_container .box {
  margin: 25px 1%;
  -ms-flex-preferred-size: 31%;
      flex-basis: 31%;
  padding: 35px 25px 25px;
  border-radius: 15px;
  -webkit-box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.15);
          box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.15);
  border-top: 15px solid transparent;
  overflow: hidden;
  -webkit-transition: all .1s;
  transition: all .1s;
}

.service_section .service_container .box .img-box {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  height: 125px;
}

.service_section .service_container .box .img-box img {
  width: 90px;
}

.service_section .service_container .box .detail-box {
  margin-top: 25px;
}

.service_section .service_container .box .detail-box h5 {
  color: #2e0e5f;
  font-weight: 600;
  position: relative;
}

.service_section .service_container .box:hover, .service_section .service_container .box.active {
  border-top: 15px solid #512a97;
}

.service_section .btn-box {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
  margin-top: 25px;
}

.service_section .btn-box a {
  display: inline-block;
  padding: 10px 35px;
  background-color: #4b208c;
  color: #ffffff;
  border-radius: 35px;
}

.service_section .btn-box a:hover {
  background-color: #5625a1;
}

.about_section {
  background-color: #f3f0f6;
}

.about_section .row {
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}

.about_section .img_container {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
}

.about_section .img_container .img-box {
  border: 5px solid #7b57b2;
  border-radius: 100%;
  overflow: hidden;
}

.about_section .img_container .img-box.b1 {
  width: 70%;
}

.about_section .img_container .img-box.b2 {
  width: 50%;
  margin-left: auto;
  margin-top: -12%;
}

.about_section .img_container .img-box img {
  width: 100%;
}

.about_section .detail-box {
  margin-right: 15%;
}

.about_section .detail-box p {
  margin-top: 25px;
}

.about_section .detail-box a {
  display: inline-block;
  padding: 10px 35px;
  background-color: #4b208c;
  color: #ffffff;
  border-radius: 5px;
  margin: 25px 0 45px 0;
}

.about_section .detail-box a:hover {
  background-color: #5625a1;
}

.blog_section .heading_container {
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
}

.blog_section .heading_container h2::before {
  background-color: #ffffff;
}

.blog_section .box {
  margin-top: 55px;
  background-color: #ffffff;
  -webkit-box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.15);
          box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.15);
}

.blog_section .box .img-box {
  position: relative;
}

.blog_section .box .img-box img {
  width: 100%;
}

.blog_section .box .detail-box {
  padding: 25px 25px 15px;
}

.blog_section .box .detail-box h5 {
  font-weight: bold;
}

.contact_section {
  position: relative;
}

.contact_section form {
  margin-top: 45px;
  padding-right: 35px;
}

.contact_section input {
  width: 100%;
  border: none;
  height: 50px;
  margin-bottom: 25px;
  padding-left: 25px;
  background-color: transparent;
  outline: none;
  color: #101010;
  -webkit-box-shadow: 0px 2px 5px 0px rgba(0, 0, 0, 0.16);
  box-shadow: 0px 2px 5px 0px rgba(0, 0, 0, 0.16);
}

.contact_section input::-webkit-input-placeholder {
  color: #737272;
}

.contact_section input:-ms-input-placeholder {
  color: #737272;
}

.contact_section input::-ms-input-placeholder {
  color: #737272;
}

.contact_section input::placeholder {
  color: #737272;
}

.contact_section input.message-box {
  height: 120px;
}

.contact_section button {
  border: none;
  display: inline-block;
  padding: 12px 45px;
  background-color: #4b208c;
  color: #ffffff;
  border-radius: 0px;
  margin-top: 35px;
}

.contact_section button:hover {
  background-color: #5625a1;
}

.contact_section .map_container {
  height: 100%;
  min-height: 325px;
}

.contact_section .map_container .map-responsive {
  height: 100%;
}

.footer_bg {
  background-image: url(../images/footer-bg.png);
  background-size: cover;
  background-position: top;
}

/* info section */
.info_section {
  background-color: #190734;
  color: #ffffff;
}

.info_section h6 {
  font-weight: bold;
}

.info_section .info_contact {
  margin-top: 60px;
  margin-bottom: 45px;
}

.info_section .info_contact .col-md-4 {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
}

.info_section .info_contact a {
  color: #ffffff;
}

.info_section .info_contact img {
  max-width: 100%;
  margin-right: 10px;
}

.info_section .info_form {
  margin: 0 auto;
  margin-bottom: 45px;
}

.info_section .info_form h4 {
  text-transform: uppercase;
  text-align: center;
  margin-bottom: 20px;
}

.info_section .info_form form {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}

.info_section .info_form form input {
  background-color: #ffffff;
  border: none;
  -webkit-box-flex: 2.5;
      -ms-flex: 2.5;
          flex: 2.5;
  outline: none;
  color: #000000;
  min-height: 42.4px;
  padding-left: 15px;
}

.info_section .info_form form input ::-webkit-input-placeholder {
  color: #ffffff;
  opacity: 0.2;
}

.info_section .info_form form input :-ms-input-placeholder {
  color: #ffffff;
  opacity: 0.2;
}

.info_section .info_form form input ::-ms-input-placeholder {
  color: #ffffff;
  opacity: 0.2;
}

.info_section .info_form form input ::placeholder {
  color: #ffffff;
  opacity: 0.2;
}

.info_section .info_form form button {
  -webkit-box-flex: 1;
      -ms-flex: 1;
          flex: 1;
  border: none;
  display: inline-block;
  padding: 10px 30px;
  background-color: #4b208c;
  color: #ffffff;
  border-radius: 0;
  font-size: 15px;
  text-transform: uppercase;
}

.info_section .info_form form button:hover {
  background-color: #5625a1;
}

.info_section .box {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
}

.info_section .info_social {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
}

.info_section .info_social img {
  width: 35px;
  margin-right: 8px;
}

/* end info section */
/* footer section*/
.footer_section {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
  position: relative;
}

.footer_section p {
  color: #222222;
  margin: 0 auto;
  text-align: center;
  padding: 20px;
}

.footer_section p a {
  color: #222222;
}
/*# sourceMappingURL=style.css.map */
