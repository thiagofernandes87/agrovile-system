<template>
    <div id="main-banner">
        <h1>Leve saúde viva melhor</h1>
    </div>
</template>

<script>
    export default{
        name: "Banner"
    }
</script>


<style scoped>
    #main-banner{
        background-image: url('/public/img/foto.jpeg');
        background-position: 0 -250px;
        background-size: cover;
        height: 350px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    #main-banner h1{
        color: #14213d;
        text-align: center;
        font-size: 30px ;
        background-color: #d9ed92 ;
        opacity: 0.5;
        padding: 20px 40px;
        }

</style>