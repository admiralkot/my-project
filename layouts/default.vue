<template>
  <section>  
    <nuxt/>
    <my-footer/>
  </section>
</template>

<script>
  import myFooter from '~/components/footer.vue'
  export default {
    components: { myFooter},
  }
</script>
