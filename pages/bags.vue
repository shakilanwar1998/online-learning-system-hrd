<template>
  <div>
    <NavOne />
    <PageHeader title="Bags" />
    <Bags />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import NavOne from "../components/NavOne";
  import Footer from "../components/Footer";
  import Bags from "../components/Bags";
  export default {
    components: {Bags, Footer, NavOne, PageHeader},
    head(){
      return {
        title: "HRDI | Course"
      }
    }
  }
</script>

