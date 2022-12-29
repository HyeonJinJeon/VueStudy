<template>
  <div class="DataBindingStringView">
    <h1>Hello {{ userName }}</h1>
    <p>{{ message }}</p>
  </div>
</template>
<script>
export default {
  data () {
    return {
      userName: 'Hyeon jin',
      message: '만나서 반갑습니다.',
      arr: [],
      obj: {}
    }
  }
}
</script>
<style scoped>
.text-red {
  color: red;
}
</style>
