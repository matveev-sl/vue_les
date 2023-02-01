<script setup lang="ts">
// import HelloWorld from './components/HelloWorld.vue'
import NavigateMenu from './components/NavigateMenu.vue'
</script>

<template>
  <div id="app">
    <header>
      <nav class="menu">
    <img class="logo" src="@/assets/images/Logo.svg">
    <ul class="nav">
        <li >Home</li>
        <li >Home</li>
        <li >Home</li>
        <li >Home</li>
        <li >Home</li>
        <li >Home</li>

    </ul>
  </nav>
    </header>
<section class="firstScreen">
<div class="Title">
<img class="BigLogo" src="@/assets/images/BigLogo.svg">
<img class="Line" src="@/assets/images/Line 3.svg">
<p class="AfterLine">User Interface Designer</p>
<p class="Subline">I’m UI/UX designer in lucknow , and I’m  very passionate 
and dedicated to my work..</p>
<button class="SayHello">say Hello <img class="Arrow" src="@/assets/images/Vector.svg"> </button>
</div>
<img class="avatar" src="@/assets/images/Avatar.png">
</section>

  </div>
</template>


<style scoped>
.nav {
  display: flex;
}
.nav li {

font-style: normal;
font-weight: 700;
font-size: 7.62468px;
line-height: 10px;
list-style-type: none;
margin-right: 20.63px;
}
.menu {
  display: flex;
  justify-content: space-between;
}
.BigLogo {
  display: block;
}
.AfterLine {
margin-top: 10px;
font-size: 8px;
font-weight: 500;
line-height: 10px;
letter-spacing: 0em;
text-align: left;
color: #000000;
display: inline-block;
}
.SayHello  {
margin-top: 30px;
background: #000000;
border-radius: 5.38213px;
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 4.48511px 12.1098px;
gap: 7.62px;
color: #ffffff;
font-size: 7.62468px;
}
.Subline {
  width: 70%;
}
/* .Title {
  display: flex;
}  */
.firstScreen {
  margin-top: 56px ;
  display: flex;
  justify-content: space-between;

}
</style>