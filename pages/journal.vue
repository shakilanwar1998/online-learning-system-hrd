<template>
  <div>
    <NavOne />
    <PageHeader title="Journal" />
    <Journal />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import NavOne from "../components/NavOne";
  import Footer from "../components/Footer";
  import Journal from "../components/Journal";
  export default {
    components: {Journal, Footer, NavOne, PageHeader},
    head(){
      return {
        title: "HRDI | Course"
      }
    }
  }
</script>
