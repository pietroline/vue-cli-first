<template>
    <div class="jumbotron">
        <h2>Jumbotron</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati nihil eos maiores quam recusandae molestias consequatur necessitatibus voluptatem nulla animi? Non, reiciendis optio. Et neque recusandae ipsa nisi, laborum eos.</p>
        
        <div class="container">

            <div class="img">
             <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/2048px-HTML5_logo_and_wordmark.svg.png" alt="img logo HTML 5">
            </div>

            <div class="img">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3d/CSS.3.svg/1200px-CSS.3.svg.png" alt="img logo CSS 3">
            </div>

            <div class="img">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/Bootstrap_logo.svg/2560px-Bootstrap_logo.svg.png" alt="img logo BOOTSTRAP">
            </div>

            <div class="img">
                <img src="https://upload.wikimedia.org/wikipedia/commons/7/73/Javascript-736400_960_720.png" alt="img logo JAVASCRIPT">
            </div>

        </div>
        
   </div>
</template>

<script>
    export default {
        name: "MainJumbotron",   
    }
</script>

<style scoped>
    .jumbotron{
        background-color: #eaeaea;

        width: 100%;

        padding-top: 20px;
    }
    
    .container{
        display: flex;
        justify-content: center;
    }

    .img{
        width: 50px;
        height: 50px;

        margin: 20px;
    }

    .img img{
        width: 100%;
        height: 100%;
        object-fit: contain;
    }

    .img img:hover{
        cursor: pointer;
    }
</style>