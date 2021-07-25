<template>
  <div>
    <SummitHead />
    <SummitSectionOne />
    <Footer />
  </div>
</template>

<script>
  import SummitHead from "../components/SummitHead";
  import SummitSectionOne from "../components/SummitSectionOne";
  import Footer from "../components/Footer";

  export default {
    components: {
      SummitHead,
      SummitSectionOne,
      Footer,
    }
  }
</script>
