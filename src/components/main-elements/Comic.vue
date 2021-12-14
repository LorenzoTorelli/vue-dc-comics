<template>
    <div class="comic">
        <div class="img-container">
            <img :src="src"  :alt="series">
        </div>
        <div class="text-container">
            <a href="#">{{series}}</a>
            <p>{{price}}</p>
        </div>
    </div>
</template>

<script>
export default {
    props: {
        src: String,
        series: String,
        price: String,

    }
}
</script>

<style lang="scss" scoped>


    .comic {
        margin: 10px 5px;
        width: calc(100% / 6 - 30px);
       
        .img-container {

            img {
                object-fit: cover;
            }
        }
        
        .text-container {
            margin-top: 10px;

            a {
                color: white;
                word-wrap: normal;
                text-decoration: none;
                font-weight: bold ;
            }
            a:hover {
                text-decoration: underline;
            }

            p {
                margin-top: 10px;
                color: grey;
            }
        }

    }
    
    
</style>

