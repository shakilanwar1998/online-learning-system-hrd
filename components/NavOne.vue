<template>
    <div>
      <div class="topbar-one">
          <div class="container">
              <div class="topbar-one__left">
                  <a href="#">needhelp@hrdi.com</a>
                  <a href="#">444 888 0000</a>
              </div><!-- /.topbar-one__left -->
              <div class="topbar-one__right">
                  <a href="#">Login</a>
                  <a href="#">Register</a>
              </div><!-- /.topbar-one__right -->
          </div><!-- /.container -->
      </div><!-- /.topbar-one -->
<header class="site-header site-header__header-one ">
          <nav class="navbar navbar-expand-lg navbar-light header-navigation stricky">
              <div class="container clearfix">
                  <!-- Brand and toggle get grouped for better mobile display -->
                  <div class="logo-box clearfix">
                      <a class="navbar-brand" href="/">
                          <img src="/assets/images/brand-logo1.jpg" class="main-logo" width="128" alt="Awesome Image" />
                      </a>
                      <div class="header__social">
                          <a href="#"><i class="fab fa-twitter"></i></a>
                          <a href="#"><i class="fab fa-facebook-square"></i></a>
                          <a href="#"><i class="fab fa-pinterest-p"></i></a>
                          <a href="#"><i class="fab fa-instagram"></i></a>
                      </div><!-- /.header__social -->
                      <button class="menu-toggler" data-target=".main-navigation">
                          <span class="kipso-icon-menu"></span>
                      </button>
                  </div><!-- /.logo-box -->
                  <!-- Collect the nav links, forms, and other content for toggling -->
                  <div class="main-navigation">
                      <ul class=" navigation-box">
                          <li class="current">
                              <a href="/">Home</a>
                          </li>
                          <li>
                              <nuxt-link to="/courses">Courses</nuxt-link>
                              <ul class="sub-menu">
                                  <li><nuxt-link to="/online-courses">Online Course</nuxt-link></li>
                                  <li><nuxt-link to="/offline-courses">Offline Course</nuxt-link></li>
                                  <li><nuxt-link to="/categories">Categories</nuxt-link></li>
                              </ul><!-- /.sub-menu -->
                          </li>

                          <li>
                              <nuxt-link to="/courses">Merchandise</nuxt-link>
                              <ul class="sub-menu">
                                  <li><nuxt-link to="/books">Books</nuxt-link></li>
                                  <li><nuxt-link to="/journal">Journal</nuxt-link></li>
                                  <li><nuxt-link to="/bags">Bag</nuxt-link></li>
                                  <li><nuxt-link to="/badges">Badges</nuxt-link></li>
                                  <li><nuxt-link to="/t-shirts">T-Shirt</nuxt-link></li>
                                  <li><nuxt-link to="#">Calender</nuxt-link></li>
                              </ul><!-- /.sub-menu -->
                          </li>

                           <li>
                              <nuxt-link to="/courses">Events</nuxt-link>
                              <ul class="sub-menu">
                                  <li><nuxt-link to="/summit">Summit</nuxt-link></li>
                                  <li><nuxt-link to="#">Live Event</nuxt-link></li>
                                  <li><nuxt-link to="#">Webinar</nuxt-link></li>
                                  <li><nuxt-link to="#">Podcast</nuxt-link></li>
                              </ul><!-- /.sub-menu -->
                          </li>

                          <li>
                              <a href="#">About Us</a>
                              <ul class="sub-menu">
                                  <li><nuxt-link to="/about">About HRDI</nuxt-link></li>
                                  <li><nuxt-link to="/team">Team</nuxt-link></li>
                                  <li><nuxt-link to="/mission-vision">Mission & Vission</nuxt-link></li>
                                  <li><nuxt-link to="/gallery">Gallery</nuxt-link></li>
                                  <li><nuxt-link to="/faq">FAQ'S</nuxt-link></li>
                              </ul><!-- /.sub-menu -->
                          </li>
                          
                          <!-- <li>
                              <nuxt-link to="/teachers">Teachers</nuxt-link>
                              <ul class="sub-menu">
                                  <li><nuxt-link to="/teachers">Teachers</nuxt-link></li>
                                  <li><nuxt-link to="/teacher-details">Teachers Details</nuxt-link></li>
                                  <li><nuxt-link to="/become-teacher">Become Teacher</nuxt-link></li>
                              </ul>
                          </li> -->
                          <!-- <li>
                              <nuxt-link to="/news">News</nuxt-link>
                              <ul class="sub-menu">
                                  <li><nuxt-link to="/news">News Page</nuxt-link></li>
                                  <li><nuxt-link to="/news-details">News Details</nuxt-link></li>
                              </ul>
                          </li> -->
                          <li>
                              <nuxt-link to="/contact">Contact</nuxt-link>
                          </li>
                      </ul>
                  </div><!-- /.navbar-collapse -->
                  <div class="right-side-box">
                      <a class="header__search-btn search-popup__toggler" href="#"><i class="kipso-icon-magnifying-glass"></i>
                          <!-- /.kipso-icon-magnifying-glass --></a>
                  </div><!-- /.right-side-box -->
              </div>
              <!-- /.container -->
          </nav>
          <div class="site-header__decor">
              <div class="site-header__decor-row">
                  <div class="site-header__decor-single">
                      <div class="site-header__decor-inner-1"></div><!-- /.site-header__decor-inner -->
                  </div><!-- /.site-header__decor-single -->
                  <div class="site-header__decor-single">
                      <div class="site-header__decor-inner-2"></div><!-- /.site-header__decor-inner -->
                  </div><!-- /.site-header__decor-single -->
                  <div class="site-header__decor-single">
                      <div class="site-header__decor-inner-3"></div><!-- /.site-header__decor-inner -->
                  </div><!-- /.site-header__decor-single -->
              </div><!-- /.site-header__decor-row -->
          </div><!-- /.site-header__decor -->
      </header>
    </div>
</template>

<script>
    export default {
        name: "NavOne"
    }
</script>

<style scoped>

</style>
