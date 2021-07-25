<template>
  <div>
    <NavOne />
    <PageHeader title="Books" />
    <Books />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import NavOne from "../components/NavOne";
  import Footer from "../components/Footer";
  import Books from "../components/Books";
  export default {
    components: {Books, Footer, NavOne, PageHeader},
    head(){
      return {
        title: "HRDI | Course"
      }
    }
  }
</script>

