<template>
  <div id="app">
    <Header />
<background />

  </div>
</template>

<script>
import Header from "./components/Header.vue"
import background from "./components/background.vue"
export default {
  components: {
    Header, background
  },
};
</script>

<style>
@font-face {
  font-family: "Roboto";
  src: url(/fonts/roboto.medium.ttf);
}
* {
  margin: 0;
  padding: 0;
}
.img {
  position: absolute;
  z-index: -1;
  width: 100%;
  height: 100vh;
  top: 0;
  left: 0;
}
.title{
    font-family: 'Roboto';
font-size: 72px;
line-height: 85px;
color: #FFFFFF;
width: 465px;
}

.head-info{
    margin-top: 172px;
}
.info-txt{
    font-family: 'Roboto';
font-style: normal;
font-weight: normal;
font-size: 16px;
line-height: 27px;
color: #FAFAFA;
width: 443px;
margin-top: 26px;
}

.learn{
    font-family: 'Roboto';
font-style: normal;
font-weight: bold;
font-size: 16px;
line-height: 80px;
color: #FFFFFF;
padding: 19px 33px;
background: #2370C8;
border-radius: 30px;
transition: 0.5s;
}
.learn:hover{
    text-shadow: 0px 5px 10px black;
    color: white;
}
</style>
