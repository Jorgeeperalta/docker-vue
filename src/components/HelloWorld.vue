<template>
  <div class="hello">
    <div style="padding: 40px">
      <h1>
        Hello from
        <span style="color: #29558c">Middleware[i</span>
        <span style="color: #ad5353">]nventory</span>
      </h1>

      It is good to have you here this is a Simple Page in
      <span class="bg-info">Vue JS</span> and Running on
      <span class="bg-success">Docker Container</span>
      <div class="divImg"><img src="@/assets/mobi.png" /></div>
    </div>
  </div>
</template>
<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.divImg{
      align-content: left;
} 
</style>