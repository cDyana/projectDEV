<template>
  <div>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My one page website</title>
</head>
<body>
    <div class="container">
      <div class="firstPage">
        <img src="../assets/Path1.png" alt="PathOne">
        <groupOne></groupOne>
        <nav class="topnav">
          <div class="navbar">
            <a href="">Home</a>
            <a href="">About</a>
            <a href="">Contact</a>
          </div>
          <div class="title"><a href="">Landie</a></div>
          <div class="navButton"><a href="">Buy Now</a></div>
        </nav>
        <main>
          <div class="introduceProduct">
            <h1>Introduce Your Product Quickly & Effectively</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid sint tempora natus. Aliquid animi, possimus repellendus dicta quia laudantium maxime ut repudiandae quam laborum eos! <br> <br>Possimus repellendus dicta quia laudantium maxime ut repudiandae quam laborum eos!</p>
            <div class="purchase">
            <a class="kit" href="">Purchase UI Kit</a>
            <a class="learn" href="">Learn More</a>
            </div>
          </div>
        </main>
      </div>
      <sectionOne></sectionOne>
      <sectionTwo></sectionTwo>
      <sectionThree></sectionThree>
      <sectionFour></sectionFour>
      <sectionFive></sectionFive>
    
    </div>
</body>
</html>

  </div>
</template>

<script>
import groupOne from '../components/groupOne'
import sectionOne from '../components/sectionOne'
import sectionTwo from '../components/sectionTwo'
import sectionThree from '../components/sectionThree'
import sectionFour from '../components/sectionFour'
import sectionFive from '../components/sectionFive'
export default {
  name: 'HelloWorld',
  components:{
    groupOne,
    sectionOne,
    sectionTwo,
    sectionThree,
    sectionFour,
    sectionFive
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
html{
  margin: 0;
  padding: 0;
  
}
html body{
  margin: 0;
  padding: 0;
 
}
.container{
 width: 1440px;
 height: 4628px;
 padding: 0;
 
}
.firstPage{
  width: 1440px;
  height: 1103px;
  background-color: #ffffff;
  position: relative;
}
img{
position: absolute;
left: 28.98%;
right: -32.45%;
top: -0.06%;
bottom: 75.97%;
}

.topnav{
  width: 100%;
  max-width: 90rem;
  height: 60px;
  display: flex;
  flex-wrap: wrap;

}
.topnav a{
  text-decoration: none;
  font-family: 'Roboto', sans-serif;
}
.navbar{
  width: 245px;
  height: 24px;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin-top: 18px;
  margin-left: 165px;

}
.navbar a{
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 24px;
color: #505F98;
display: inline-block;

}

.title{
margin-top: 12px;
margin-left: 271px;
z-index: 10;
}
.title a{
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: 900;
font-size: 26px;
line-height: 38px;
text-align: center;
color: #37447E;
}
.navButton{
width: 160px;
height: 26px;
margin: 0 auto;
background: #111B47;
border-radius: 2px;
text-align: center;
margin-top: 17px;
margin-left: 355px;
z-index: 10;
display: flex;
align-items: center;
}
.navButton a{
display: block;
width: 100%;
color: #FFFFFF;
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: 500;
font-size: 12px;
line-height: 18px;
}
main{
  position: relative;
}
.introduceProduct{
  width: 539.37px;
  height: 421px;
  position: absolute;
  top: 243px;
  left: 163.12px;
}
.introduceProduct h1{
width: 539px;
height: 132px;
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: 500;
font-size: 50px;
line-height: 66px;
letter-spacing: 1px;
color: #091133;
}
.introduceProduct p{
width: 539px;
height: 164px;
margin-top: 20px;
font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 18px;
line-height: 30px;
color: #505F98;
}

.purchase{
  margin-top: 69px;
  display: flex;
  flex-direction: row;
}
.purchase a{

text-decoration: none;
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: 500;
font-size: 16px;
line-height: 26px;
}
.kit{
 width: 189px;
 max-height: 36px;
 background: #111B47;
 border-radius: 2px;
 margin-right: 30px;
 text-align: center;
 display: inline-block;
 color: #FFFFFF;
}
.learn{
  width: 189px;
  max-height: 36px;
  border: 2px solid #091133;
  border-radius: 2px;
  text-align: center;
  display: inline-block;
  color: #091133;
  
}




</style>
