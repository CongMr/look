<template>
  <div>
    <Header></Header>
    <HomeSwiper></HomeSwiper>
    <div>texts</div>
  </div>
</template>

<script>
import Header from "@/components/home/Header";
import HomeSwiper from "@/components/home/HomeSwiper";

export default {
  name: "Home",
  components: {
    Header,
    HomeSwiper
  },


}
</script>

<style scoped>

</style>