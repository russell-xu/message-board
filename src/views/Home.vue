<template>
  <section class="home">
    <Messages />
    <InputForm />
  </section>
</template>

<script>
// @ is an alias to /src
import Messages from "@/components/Messages.vue";
import InputForm from "@/components/InputForm.vue";

export default {
  name: "Home",
  components: {
    Messages,
    InputForm,
  },
};
</script>

<style scoped lang="scss">
.home {
  padding: 60px 0;
}
</style>
