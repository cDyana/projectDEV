<template>
<div>
    <section>
        <div class="light">
            <div class="title">
                <h2>Light, Fast and Powerful</h2>
                 <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid sint tempora natus. Aliquid animi, possimus repellendus dicta quia laudantium maxime ut repudiandae quam laborum eos! <br> <br>Possimus repellendus dicta quia laudantium maxime ut repudiandae quam laborum eos!</p>
            </div>
            <div class="littleTitles">
                <div class="littleOne">
                    <img class="icon" src="../assets/icon1.png" alt="icon">
                    <h4>Title Goes Here</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit possimus.</p>
                </div>
                <div class="littleTwo">
                    <img class="icon" src="../assets/icon1.png" alt="icon">
                    <h4>Title Goes Here</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit possimus.</p>
                </div>
            </div>
        </div>
        <div class="phone">
            <img src="../assets/lady.png" alt="">
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
    height: 742px;
    background-color: #ffffff;
    display: flex;
    flex-wrap: wrap;
}
.light{
    width: 540px;
    height: 422px;
    margin-right: 30px;
    margin-left: 165px;
    margin-top: 160px;
}
.light h2{
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: 500;
font-size: 36px;
line-height: 48px;
color: #091133;
}
.light p{
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: normal;
font-size: 16px;
line-height: 26px;
color: #6F7CB2;
margin-top: 16px;
}
.littleTitles{
    display: flex;
    flex-wrap: wrap;
}
.littleOne{
    width: 255px;
    height: 138px;
    margin-top: 80px;
}
.littleTwo{
    width: 255px;
    height: 138px;
    margin-top: 80px;
}
.phone{
    width: 540px;
    height: 524px;
    margin-top: 109px;
}
.icon img{
    width: 36px;
    height: 36px;
    margin-bottom: 14px;
}
</style>