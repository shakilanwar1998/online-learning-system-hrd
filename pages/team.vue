<template>
  <div>
    <NavOne />
    <PageHeader title="Team" />
    <Team />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import NavOne from "../components/NavOne";
  import Footer from "../components/Footer";
  import Team from "../components/Team";
  export default {
    components: {Team, Footer, NavOne, PageHeader},
    head(){
      return {
        title: "HRDI | Course"
      }
    }
  }
</script>

