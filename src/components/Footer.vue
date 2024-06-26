<template>
  <footer class="container-fluid">
      <div class="row lead">
        <p>Khanya's portfolio &copy; 
            <span class="shadow">{{ cYear }}</span>
        </p>
    </div>
  </footer>
</template>

<script>
export default {
name: "FooterComp",
data(){
return{
 cYear: new Date().getUTCFullYear()

}
}
}
</script>

<style lang="sss" scoped>

</style>