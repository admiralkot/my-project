<template>

<footer class="footer" id="footer-site">
  <hr/>
    <div class="row justify-content-center " >
      <i class="fas fa-code fa-4x" style="margin-right: 20px;"></i>
      <div>
        <h5>© 2017 - {{new Date().getUTCFullYear()}}</h5>
      </div>
    </div>
  </footer>

</template>

<script>
export default {
  name:'myFooter',
  data: ()=>({
    date: null,

  }),
}
</script>

<style>
html, body {
    margin: 5px;
    padding: 0;
}

#footer-site{
  padding-bottom: 20px;
  padding-top: 20px;
  text-align: center;

}

</style>
