<template>
  <div>
    <NavOne />
    <PageHeader title="Categories" />
    <Categories />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import NavOne from "../components/NavOne";
  import Footer from "../components/Footer";
  import Categories from "../components/Categories";
  export default {
    components: {Categories, Footer, NavOne, PageHeader},
    head(){
      return {
        title: "HRDI | Course"
      }
    }
  }
</script>

