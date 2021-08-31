<template>
 <header>
<div class="nav container justify-content-between align-items-center">
  <a href="#" class="logo">LOGO.</a>
  <ul class="link d-flex align-items-center mt">
    <li><a href="#" class="links">HOME</a></li>
    <li><a href="#" class="links">ABOUT</a></li>
    <li><a href="#" class="links">PAGES</a></li>
    <li><a href="#" class="links">SERVICES</a></li>
    <li><a href="#" class="links">PORTFOLIO</a></li>
    <li><a href="#" class="links">BLOG</a></li>
    <li><a href="#" class="links">CONTACT</a></li>
  </ul>
     <div class="divvi d-flex align-items-center">
                <input v-model="message" placeholder="Search"> <i class="fas fa-search"></i>
            </div>
</div>

  </header>
</template>

<script>
export default {

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  a{
    text-decoration: none!important;
    list-style: none;
}

li{
    list-style: none;
}
.nav{
  padding-top: 24px;
}
.logo{
    font-family: 'Roboto';
font-style: normal;
font-weight: bold;
font-size: 30px;
line-height: 35px;
color: #FFFFFF;
text-transform: uppercase;
transition: 0.5s;
}
.logo:hover{
    text-shadow: 0px 5px 10px black;
    color: white;
}

.links{
    font-family: 'Roboto';
font-style: normal;
font-weight: 500;
font-size: 16px;
line-height: 19px;
color: #FFFFFF;
margin-right: 20px;
transition: 0.5s;
}
.links:hover{
    text-shadow: 0px 5px 10px black;
    color: white;
}
.mt{
    margin-top: 20px;
}
.divvi{
    padding: 7px;
background: #FFFFFF;
border-radius: 30px;
color: #2370C8;
}
input{
    border: none;
    outline: none;
}
input::placeholder{
    font-family: 'Roboto';
font-style: normal;
font-weight: 500;
font-size: 16px;
line-height: 19px;

color: #2370C8;
}


</style>
