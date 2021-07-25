<template>
  <div>
    <NavOne />
    <BannerTwo />
    <AboutTwo />
    <CourseOne />
    <VideoTwo />
    <CountdownOne />
    <CallToActionThree />
    <ClientsLogoTwo />
    <BlogCarousel />
    <CallToActionFour />
    <Subscribe />
    <Footer />
  </div>
</template>

<script>
  import NavOne from "../components/NavOne";
  import BannerTwo from "../components/BannerTwo";
  import Footer from "../components/Footer";
  import AboutTwo from "../components/AboutTwo";
  import CourseOne from "../components/CourseOne";
  import VideoTwo from "../components/VideoTwo";
  import CountdownOne from "../components/CountdownOne";
  import CallToActionThree from "../components/CallToActionThree";
  import ClientsLogoTwo from "../components/ClientsLogoTwo";
  import BlogCarousel from "../components/BlogCarousel";
  import CallToActionFour from "../components/CallToActionFour";
  import Subscribe from "../components/Subscribe";

  export default {
    components: {
      Subscribe,
      CallToActionFour,
      BlogCarousel,
      ClientsLogoTwo,
      CallToActionThree,
      CountdownOne,
      VideoTwo,
      CourseOne,
      NavOne,
      BannerTwo,
      AboutTwo,
      Footer,
    }
  }
</script>
