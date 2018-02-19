<template>
  <div>
      <headline></headline>
      <sign-in></sign-in>
      <recommend></recommend>
      <welfare></welfare>
  </div>
</template>
<script>
import Headline from './headline'
import SignIn from './sign_in'
import Recommend from './recommend'
import Welfare from './more_welfare'
export default {
  components:{
      Headline,
      SignIn,
      Recommend,
      Welfare
  }
}
</script>
<style lang="scss" scoped>

</style>
