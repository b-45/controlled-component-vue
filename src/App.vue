<template>

  <div class="min-h-screen bg-grey-light p-8">
    <div class="max-w-sm mx-auto">
      <user-sign-up-form></user-sign-up-form>
    </div>
  </div>
</template>

<script>
import UserSignUpForm from "./components/UserSignUpForm.vue";

export default {
  name: "app",
  components: {
    UserSignUpForm
  }
};
</script>

<style>
body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
}
</style>
