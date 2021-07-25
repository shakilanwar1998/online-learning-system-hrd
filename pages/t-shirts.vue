<template>
  <div>
    <NavOne />
    <PageHeader title="T-Shirts" />
    <TShirts />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import NavOne from "../components/NavOne";
  import Footer from "../components/Footer";
  import TShirts from "../components/TShirts";
  export default {
    components: {TShirts, Footer, NavOne, PageHeader},
    head(){
      return {
        title: "HRDI | T-Shirts"
      }
    }
  }
</script>

