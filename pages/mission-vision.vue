<template>
  <div>
    <NavOne />
    <PageHeader title="Mission & Vision" />
    <MissionVision />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import NavOne from "../components/NavOne";
  import Footer from "../components/Footer";
  import MissionVision from "../components/MissionVision";
  export default {
    components: {MissionVision, Footer, NavOne, PageHeader},
    head(){
      return {
        title: "HRDI | Mission & Vision"
      }
    }
  }
</script>

