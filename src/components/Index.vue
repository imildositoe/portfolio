<template>
  <div>
    <img src="#" alt="small logo">

    <ul class="menu">
      <li>home</li>
      <li>work</li>
      <li>about me</li>
      <li>contact</li>
    </ul>

    <h2>welcome to my portfolio</h2>
    <h4>I am a Mozambican developer, living in Maputo.</h4>

    <img src="#" alt="profile">

    <div class="home"></div>
    <div class="work"></div>
    <div class="about_me"></div>
    <div class="contact"></div>
  </div>
</template>

<script>
export default {
  name: 'Index',
}
</script>

<style scoped>
  .menu {
    display: flex;
  }

  .menu li {
    list-style: none;
  }
</style>
