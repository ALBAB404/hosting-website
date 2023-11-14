<script setup>
// All Import File  Code Is Here......................................................................................................

import {
  Header,
  Navbar,
  Navbar2,
  FooterSection,
  ButtomToTopButton
} from "@/components";


// All Variable  Code Is Here.....................................................................................................
// const currentRoute = ref('');

// API Calling Code Is Here.....................................................................................................

// All Function  Code Is Here.....................................................................................................


</script>

<template>
  <div>
    <!--header section start-->
     <!-- <template v-if="$route.name !== 'about'"> -->
        <header id="header" class="header-main">
            <Header />
            <Navbar />
        </header>
      <!-- </template> -->
       <!-- <template v-else>
        <header id="header" class="header-main headroom">
            <Navbar2 />
        </header>
      </template> -->
    <!--header section end-->

  <router-view></router-view>

    <!--footer section start-->
    <FooterSection />
    <!--footer section end-->
    <!--bottom to top button start-->
   <ButtomToTopButton />
    <!--bottom to top button end-->
  </div>
</template>

<style></style>
