<template>
  <div>
    <NavOne />
    <PageHeader title="Badges" />
    <Badges />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import NavOne from "../components/NavOne";
  import Footer from "../components/Footer";
  import Badges from "../components/Badges";
  export default {
    components: {Badges, Footer, NavOne, PageHeader},
    head(){
      return {
        title: "HRDI | Badges"
      }
    }
  }
</script>

