<template>
    <div class="container">
      
      <NavigationBar />
    <!-- <div class="form"> -->
        <br />
        <br />
        <br />
    <hr /><iframe src="https://docs.google.com/forms/d/e/1FAIpQLSe2sjlkt2S0RePZoGqpGYJ9ry69dwPnZaVcePxKQ0vvanevKA/viewform?embedded=true" width="100%" height="1650" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
<ScrollTopVue />
    <ScrollTopArrowVue />


   
    <ScrollTopVue />
    <ScrollTopArrowVue />
    
  </div>
  
  </template>
  
  <script>
  import NavigationBar from "~/components/NavigationBar";
  import FooterSection from "~/components/FooterSection";
  import ScrollTopVue from "../components/ScrollTop.vue";
import ScrollTopArrowVue from "../components/ScrollTopArrow.vue";
  export default {
    components: {
      NavigationBar,
      FooterSection,
      ScrollTopVue,
      ScrollTopArrowVue,
    },
  };
  </script>
  
  <style>
  
  
  .container {
    display: flex;
    flex-direction: column;
  }
    @media screen and (max-width: 992px) {
            .form{
                height: 700px;
                 width: 700px;   
            }
  }
  
.res{
 width: 100%;
}
  </style>
  