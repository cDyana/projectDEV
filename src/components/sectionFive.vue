<template>
<div>
<section>
    <div class="rectangle"><img src="../assets/Rectangle.png" alt="rectangle ">
    <div class="path"><img src="../assets/Path2.png" alt="">
        <h2>A Price To Suit Everyone</h2>
        <div class="text">
        <p class="lorem">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid sint tempora natus. Aliquid animi, possimus repellendus dicta quia laudantium maxime ut repudiandae repudiandae quam laborum eos!</p>
        <p class="price">$40</p>
        <p class="design">UI Design Kit</p>
        <p class="simple">See, One Price. Simple.</p>
        <button><a href="">27593979-2D30-4AFB-A339-</a></button>
        <p class="number">BCE88A32C28C</p>
        </div>
    </div>
    
    <footer>
        <div class="uix">
        <img src="../assets/uix.png" alt="">
        <div class="title"><a href="">Landie</a></div>
        <button class="numberTwo"><a href="">ECD6D6E8-ABBE-4</a></button>
        <p>B2D-84DE-906D920<br>771E1</p>
        </div>
        <hr>
        <div class="footernav">
            <div class="nav">
                <a href="">Home</a>
                <a href="">About</a>
                <a href="">Contact</a>
            </div>
            <div class="social">
                <a href=""><img src="../assets/facebook.png" alt="facebook icon"></a>
                <a href=""><img src="../assets/linkedin.png" alt="linkedin icon"></a>
                <a href=""><img src="../assets/twit.png" alt="twitter icon"></a>
                <a href=""><img src="../assets/youtube.png" alt="youtube icon"></a>
                <a href=""><img src="../assets/instagram.png" alt="instagram icon"></a>
            </div>
        </div>
    </footer>
    </div>
</section>
</div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
section{
width: 1440px;
height: 996px;
background-color: #fff;
position: relative;
}
.rectangle{
    margin-top: 152px;
}
.path{
position: absolute;
z-index: 12; 
left: 13.19%;
right: 13.19%;
top: -5.69%;
bottom: 5.88%;
}
.path h2{
width: 600px;
height: 48px;
position: absolute;
height: 48px;
left: 240px;
right: 0px;
top: 204px;
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: 500;
font-size: 36px;
line-height: 48px;
text-align: center;
color: #091133;
}
.text{
    position: relative;
}
.lorem{
width: 600px;
height: 78px;
margin-top: -550px;
margin-left: 230px;
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: normal;
font-size: 16px;
line-height: 26px;
text-align: center;
color: #6F7CB2;
}
.price{
margin-top: 35px;
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: 500;
font-size: 50px;
line-height: 66px;
text-align: center;
letter-spacing: 1px;
color: #222F65;
}
.design{
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: normal;
font-size: 16px;
line-height: 26px;
text-align: center;
color: #222F65;
}
.simple{
margin-top: 60px;
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 24px;
text-align: center;
color: #5D6970;
}
button{
background: #111B47;
border-radius: 2px;
margin-left: 435px;
margin-top: 16px;
}
a{
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: 500;
font-size: 14px;
line-height: 24px;
text-align: center;
color: #FFFFFF;
text-decoration: none;

}
.number{
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: 500;
font-size: 14px;
line-height: 24px;
text-align: center;
color: #FFFFFF;
}
footer{
    width: 1440px;
    height: 216px;
    background: #E7ECFF;
    margin-top: -133px;
}

.uix img{
    margin-top: 68px;
    margin-left: 165px;
    margin-bottom: 47px;
}
.uix{
    position: relative;
}
.title a{
position: absolute;
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: 900;
font-size: 26px;
line-height: 38px;
color: #37447E;
left: 681px;
top: 54px;
}
.numberTwo{
background: #111B47;
border-radius: 2px;
position: absolute;
left: 715px;
top: 44px;
}
.uix p{
width: 109px;
height: 54px;
position: absolute;
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: 500;
font-size: 12px;
line-height: 18px;
text-align: center;
color: #FFFFFF;
left: 1155px;
top: 85px;
}

hr{
width: 1110px;
height: 1px;
background: #CDD1D4;
margin: 0 auto;
}
.nav{
   margin-left: 165px;
   margin-top: 20px;
   
}
.nav a{
margin-right: 60px; 
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 24px;
color: #929ECC;
}
.footernav{
    display: flex;
    flex-direction: row;
}
.social{
    margin-left: 605px;
    margin-top: 29px;
    
}
.social a{
margin-right: 30px;

}
</style>