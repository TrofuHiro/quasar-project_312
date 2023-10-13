<template>
  <div class="htmlClass">
    <h1>{{ title }}</h1>
  </div>

  <InputPage></InputPage>
  <FunctionPage></FunctionPage>
</template>


<script>
import InputPage from "../pages/InputPage.vue"
import FunctionPage from "../pages/FunctionPage.vue"
export default {
  name: 'HtmlComponent',
  components: {
    InputPage,
    FunctionPage
   },
  data() {
    return {
      title: 'Jirawat kongyoo',
    }
  },
}
</script>


<style scoped></style>
