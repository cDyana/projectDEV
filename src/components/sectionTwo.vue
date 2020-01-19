<template>
<div>
<section>
    <div class="happy"><img src="../assets/happy_news.png" alt="lady"></div>
    <div class="fast">
        <h2>Light, Fast and Powerful</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid sint tempora natus. Aliquid animi, possimus repellendus dicta quia laudantium maxime ut repudiandae quam laborum eos! <br> <br>Possimus repellendus dicta quia laudantium maxime ut repudiandae quam laborum eos!</p>
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
    height: 569px;
    background-color: #ffffff;
    display: flex;
    flex-wrap: wrap;
}
.happy{
    width: 480px;
    height: 315px;
    margin-left: 191px;
    margin-right: 155px;
}
.happy img{
    margin-top: 122px;
}
.fast{
    width: 445px;
    height: 228px;
    margin-top: 172px;
}
.fast h2{
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: 500;
font-size: 36px;
line-height: 48px;
color: #091133;
}
.fast p{
margin-top: 16px;
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: normal;
font-size: 16px;
line-height: 26px;
color: #6F7CB2;
}

</style>