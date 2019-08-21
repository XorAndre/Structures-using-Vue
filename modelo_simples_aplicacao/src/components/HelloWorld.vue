<template>
  <div class="main">
    <nav class="menu">
      <div class="logo">
        <h1>{{logo}}</h1>
      </div>
      <ul class="links">
        <li><a href="">Link</a></li>
        <li><a href="">Link</a></li>
        <li><a href="">Link</a></li>
        <li><a href="">Link</a></li>
        <li><a href="">Link</a></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'Meu site',
  props: {
    logo: String
  }
}
</script>

<style scoped>
/*Reset*/
*{
  box-sizing: border-box;
  font: inherit;
  font-size: 100%;
  line-height: 1.7;
  margin: 0;
  padding: 0;
}
/*Menu*/
.menu{
 background-color: #fff;
 display: flex;
 flex-direction: row;
 position: fixed;
 width: 100%;
}
</style>
