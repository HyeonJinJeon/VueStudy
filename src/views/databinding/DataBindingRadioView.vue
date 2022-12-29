<template>
  <div>
    <input type="radio" name="" id="html" value="HTML" v-model="favoriteLang">
    <label for="html">HTML</label>
  </div>
  <div>
    <input type="radio" name="" id="css" value="CSS" v-model="favoriteLang">
    <label for="css">CSS</label>
  </div>
  <div>
    <input type="radio" name="" id="js" value="JS" v-model="favoriteLang">
    <label for="js">JavaScript</label>
  </div>
  <!--동일한 name을 지정하지 않아도 동일한 v-modle을 지정하기 때문에 같은 그룹의 체크박스로 묶인다.-->
  <div>선택한 지역: {{ favoriteLang }}</div>
</template>
<script>
export default {
  components: {},
  data () {
    return {
      favoriteLang: ''
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}

</script>
