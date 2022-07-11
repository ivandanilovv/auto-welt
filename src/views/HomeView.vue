<template>
  <main class="container py-5">
    <intro/>
    <steps-for-buying/>
    <physical-person/>
    <hr/>
    <juridical-person/>
  </main>
</template>

<script>
// @ is an alias to /src

import Intro from "@/components/Intro";
import StepsForBuying from "@/components/StepsForBuying";
import PhysicalPerson from "@/components/PhysicalPerson";
import JuridicalPerson from "@/components/JuridicalPerson";

export default {
  components: {
    Intro,
    StepsForBuying,
    PhysicalPerson,
    JuridicalPerson,
  }
}
</script>
