<template>
  <main class="container py-5">
    <div class="row">
      <div class="col-12">
        <intro/>
        <steps-for-buying/>
        <fizicki-lica/>
        <hr/>
        <pravni-lica/>
      </div>
    </div>
  </main>
</template>

<script>
// @ is an alias to /src

import Intro from "@/components/Intro";
import PravniLica from "@/components/PravniLica";
import FizickiLica from "@/components/FizickiLica";
import StepsForBuying from "@/components/StepsForBuying";

export default {
  components: {
    Intro,
    PravniLica,
    FizickiLica,
    StepsForBuying,
  }
}
</script>
