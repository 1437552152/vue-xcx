<template>
  <div>
    <p class="card">
      {{text}},你好啊小叶
    </p>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
  created() {
    console.log(this.text);
  },
  props: ["text"]
};
</script>

<style>
.card {
  padding: 10px;
}
</style>
