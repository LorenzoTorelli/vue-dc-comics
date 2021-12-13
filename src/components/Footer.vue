<template>
    <section id="footer">
        
        <div id="top-footer">
            <div class="container">
                <ul>
                    <li>
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="digital-comics">
                        <a href="#">Digital comics</a>
                    </li>
                    <li>
                        <img src="../assets/img/buy-comics-merchandise.png" alt="digital-comics">
                        <a href="#">Digital comics</a>
                    </li>
                    <li>
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="digital-comics">
                        <a href="#">Digital comics</a>
                    </li>
                    <li>
                        <img src="../assets/img/buy-comics-merchandise.png" alt="digital-comics">
                        <a href="#">Digital comics</a>
                    </li>
                     <li>
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="digital-comics">
                        <a href="#">Digital comics</a>
                    </li>
                </ul>
            </div>
        </div>

        <div id="mid-footer">
            <div class="container">
                <div class="left-side">
                    <div class="elenco">
                        <h3>Dc comics</h3>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>       
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                    </div>

                     <div class="elenco">
                        <h3>Shop</h3>
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>       
                        </ul>
                    </div>

                    <div class="elenco">
                        <h3>Dc</h3>
                        <ul>
                            <li><a href="#">Terms Of Use</a></li>
                            <li><a href="#">Privacy Policy (New)</a></li>       
                            <li><a href="#">Ad Choices</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">Subscriptions</a></li>
                            <li><a href="#">Talent Workshop</a></li>
                            <li><a href="#">CPSC Certificates</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>
                    </div>

                     <div class="elenco">
                        <h3>Sites</h3>
                        <ul>
                            <li><a href="#">DC</a></li>
                            <li><a href="#">MAD Magazine</a></li>
                            <li><a href="#">DC Kids</a></li>
                            <li><a href="#">DC Universe</a></li>
                            <li><a href="#">DC Power Visa</a></li>        
                        </ul>
                    </div>

                </div>
                <div class="right-side">
                </div>
            </div>
        </div>

        <div id="bottom-footer">
            <div class="container">
                <div id="button">
                    <a href="">Sign-up Now!</a>
                </div>
                <div id="socials">
                    <h3>Follow  Us</h3>
                    <img src="../assets/img/footer-facebook.png" alt="facebook">
                    <img src="../assets/img/footer-twitter.png" alt="twitter">
                    <img src="../assets/img/footer-youtube.png" alt="youtube">
                    <img src="../assets/img/footer-pinterest.png" alt="pinterest">
                    <img src="../assets/img/footer-periscope.png" alt="periscope">
                </div>
            </div>
        </div>
       
    </section>
</template>

<script>
export default {
    name:'Footer',
}
</script>

<style lang="scss" scoped>
    #footer {
        // height: 600px;
        // background-color: blue;

        #top-footer {
            background-color: #0c7cec;
            height: 120px;

            .container {
                height: 100%;
                ul {
                    display: flex;
                    list-style: none;
                    justify-content: space-around;
                    align-items: center;
                    height: 100%;

                    li {
                        display: flex;
                        flex-direction: row;

                        img {
                            width: 60px;
                        }

                        a {
                            text-decoration: none;
                            margin-left: 15px;
                            align-self: center;
                            color: white;
                            text-transform: uppercase;
                        }
                    }
                }
            }
        }

        #mid-footer {
            background-image: url("../assets/img/footer-bg.jpg");
            height: 400px;

            .container {
                display: flex;
                height: 100%;

                .left-side {
                    width: 50%;
                    display: flex;
                    flex-direction: column;
                    flex-wrap: wrap;
                    padding: 25px 0px;
                    .elenco {
                        
                        h3 {
                            color: white;
                            text-transform: uppercase;
                            margin: 15px 0px;
                            font-size: 20px;
                        }

                        ul {
                            list-style: none;
                            li {
                                line-height: 25px;
                                a {
                                    text-decoration: none;
                                    color: grey;
                                }
                            }
                        }
                    }
                }
                .right-side {
                    width: 50%;
                    background-image: url("../assets/img/dc-logo-bg.png");
                    background-position:center;
                    background-repeat: no-repeat ;
                   
                }
            }
        }

        #bottom-footer {
            height: 115px;
            background-color:rgb(48, 48, 48) ;

            .container {
                display: flex;
                justify-content: space-between;
                align-items: center;
                height: 100%;

                #button {
                    border: 2px solid #0c7cec;
                    padding: 15px 25px;

                    a {
                        text-decoration: none;
                        color: white;
                        text-transform: uppercase;
                    }
                }

                #socials {
                    display: flex;
                    align-items: center;

                    h3 {
                        color: #0c7cec;
                        text-transform: uppercase;
                    }

                    img {
                        margin: 10px
                    }
                }
            }


        }
    }
</style>

