<template>
  <div class="about">
    <h1>This is an about page</h1>
    <FormulaireVuelidate />
  </div>
</template>

<script>
// @ is an alias to /src
import FormulaireVuelidate from '@/components/FormulaireVuelidate.vue'


export default {
  name: 'AboutView',
  components: {
    FormulaireVuelidate,
}
}
</script>

