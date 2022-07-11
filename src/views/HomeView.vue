<template>
  <main>
    <div class="container">
      <first-comp/>
      <secound-comp/>
      <third-comp/>
      <last-comp/>
    </div>
  </main>
</template>

<script>
// @ is an alias to /src

import FirstComp from "@/components/firstComp";
import SecoundComp from "@/components/secoundComp";
import ThirdComp from "@/components/thirdComp";
import LastComp from "@/components/lastComp";

export default {
  name: 'HomeView',
  components: {LastComp, ThirdComp, SecoundComp, FirstComp},
}
</script>
