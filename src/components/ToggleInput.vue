<template>
  <div>
    <span class="toggle" role="checkbox" tabindex="0" @click="toggle" @keydown.space.prevent="toggle" :aria-checked="value.toString()">
    </span>
  </div>
</template>

<script>
export default {
  props: ["value"],
  methods: {
    toggle() {
      this.$emit("input", !this.value);
    }
  }
};
</script>

 