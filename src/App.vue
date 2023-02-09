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
<section class="secondScreen">
<h2>About me</h2>
<p class="subtitle">My introducatio</p>
<div class="aboutME">
<img class="portrait" src="@/assets/images/portait.png"/>
<div class="features">
<div class="feature">
  <img class="featureImg" src="@/assets/images/Experience.svg">
</div>
<div class="feature">
  <img class="featureImg" src="@/assets/images/Completed.svg">
</div>
<div class="feature">
  <img class="featureImg" src="@/assets/images/Support.svg">
</div>
<p class="aboutText">UI/UX designer , I create web pages UI /UX userinterface ,
Ihave years of experience and many clients are happy with 
the projects carried out.</p>
<button class="SayHello">Dowmload cv<img class="Arrow" src="@/assets/images/Vector (1).svg"> </button>
</div>

</div>
</section>
<section class="thrirdScreen">
 <h2>Skills</h2>
 <p class="subtitle">avatar</p>  
<div class="iconsFirstRow">
  <div class="icon"><img class="icons" src='@/assets/images/figma.svg'></div>
  <div class="icon"><img class="icons" src='@/assets/images/c++.svg'></div>
  <div class="icon"><img class="icons" src='@/assets/images/java.svg'></div>
  <div class="icon"><img class="icons" src='@/assets/images/python.svg'></div>
</div>
<div class="iconsFirstRow">
  <div class="icon"><img class="icons" src='@/assets/images/html5.svg'></div>
  <div class="icon"><img class="icons" src='@/assets/images/css3.svg'></div>
  <div class="icon"><img class="icons" src='@/assets/images/wordpress.svg'></div>
  <div class="icon"><img class="icons" src='@/assets/images/vscode.svg'></div>
  <div class="icon"><img class="icons" src='@/assets/images/notion.svg'></div>
</div>

</section>
<section class="fourthScreen">
<h2>Services</h2>
<p class="subtitle">What i ofeer</p>
<div class="proSkills">
<img class="proSkil" src="@/assets/images/web-designer.svg">
<img class="proSkil" src="@/assets/images/uix-designer.svg">
<img class="proSkil" src="@/assets/images/branding.svg">
</div>

</section>
<section class="fifth">
 <h2>Qualification</h2>
 <p class="subtitle">My personal journey</p>
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
/* .avatar {
  width: 146px;
  height: 141px;
} */
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
body {
  padding-left:10%;
  padding-right: 10%;
  width: 518px;
  font-family: DM Sans;
}

p {
  font-family: 'DM Sans';
font-style: normal;
font-weight: 500;
font-size: 6.72064px;
line-height: 9px;

color: #4A4A4A;
}

h2 {
font-family: 'Manrope';
font-style: normal;
font-weight: 800;
font-size: 16.0817px;
line-height: 22px;
text-align: center;
color: #31353B;
}

.subtitle {
  font-family: 'DM Sans';
font-style: normal;
font-weight: 500;
font-size: 5.8918px;
line-height: 8px;
color: #545353;
text-align: center;
margin-top:-10px
}
.aboutME {
 display: flex;
 margin-top: 50px;
}
.features {
  margin-left: 28.26px;
}
.portrait {
  width: 158.77px;
height: 135.45px;
}
.feature {
display: inline-block;
width: 55.62px;
height: 46.2px;
border: 0.448511px solid #D4D4D4;
border-radius: 7.17617px;
margin-right: 27px;
}
.featureImg {
  width:100%;
  height: 100%;
}
.aboutText {
width: 70%;
font-weight: 500;
font-size: 6.72064px;
line-height: 9px;
color: #4A4A4A;
margin-left: 15px;
margin-top: 10px;
margin-bottom: -10px;
}
.iconsFirstRow {
  display: flex;
  width: 100%;
}
.icon {
  margin-right:5px;
}
.icons {
  width: 100%;
  height: 100%;

}
.proSkills {
  display: flex;
  width: 100%;
  justify-content: space-between;
}
.proSkil {
height: 158px;
}
</style>