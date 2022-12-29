<template>
  <div>
    <select v-model="selectedCity">
      <option value=""></option>
      <option value="02">서울</option>
      <option value="051">부산</option>
      <option value="064">제주</option>
    </select>
    <button @click="changeCity">도시 변경 콘솔 확인</button>
  </div>
</template>
<script>
export default {
  components: {},
  data () {
    return {
      selectedCity: '02'
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {
    changeCity() {
      console.log(this.selectedCity)
    }
  }
}

</script>
