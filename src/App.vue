<template>
  <div id="app">
      <Logo/>
      <Message/>
      <Bottom/>
  </div>
</template>

<script>
  import Logo from "@/views/header.vue";
  import Message from "@/views/content.vue";
  import Bottom from "@/views/footer.vue";
export default {
  name: 'app',
  components:{
    Logo,
    Message,
    Bottom
  }
}
</script>

