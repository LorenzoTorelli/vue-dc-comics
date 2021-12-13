<template>
    <section id="header">
        <div class="container">
            <div id="img-box"><img src="../assets/img/dc-logo.png" alt="dc-logo"></div>
            <div id="nav-box">
                <nav>
                    <ul>
                        <li><a href="">characters</a></li>
                        <li><a href="">comics</a></li>
                        <li><a href="">movies</a></li>
                        <li><a href="">tv</a></li>
                        <li><a href="">games</a></li>
                        <li><a href="">collectibles</a></li>
                        <li><a href="">videos</a></li>
                        <li><a href="">fans</a></li>
                        <li><a href="">news</a></li>
                        <li><a href="">shop</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style lang="scss" scoped>
    #header {
        // padding: 15px 0px;
        // height: 120px;
       
        .container {
            display: flex;
            justify-content: space-around;
            align-items: center;

            #img-box {
                width: 30%;
                // background-color: blue;
                // padding: 15px 0px;
                height: 120px;
                display: flex;
                align-items: center;
            }

            #nav-box {
                width: 70%;
                height: 120px;

                // height: 100%;
                // background-color: red;

                nav { 
                    height: 100%;

                    ul {
                    display: flex;
                    list-style: none;
                    justify-content: space-between;
                    height: 100%;
                    align-items: center;

                    li {
                        margin: 0px 5px;
                        // height: 100%;
                        // margin-top: 40px;
                                                
                        a {
                        color: grey;
                        text-decoration: none;
                        text-transform: uppercase;
                        font-size: 19px;
                        height: 100%;
                       
                       }
                    }
                }
                }
                
            }
        }
    }
</style>>
    
