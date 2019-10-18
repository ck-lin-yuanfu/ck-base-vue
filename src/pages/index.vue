<template>
  <div class="contains">
    <h1>{{message}}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: '欢迎使用 ck-base-vue v 0.0.1'
    }
  },
  components: {},
  methods: {}
}
</script>

<style>
.contains {
    width: 960px;
    margin: 30px auto;
}
</style>
