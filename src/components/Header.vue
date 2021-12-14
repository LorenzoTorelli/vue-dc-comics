<template>
    <section id="header">
        <div class="container">
            <div id="img-box"><img src="../assets/img/dc-logo.png" alt="dc-logo" @click="selected = 999"></div>
            <div id="nav-box">
                <nav>
                    <ul>
                        <li v-for= " (elemento,index) in menu" :key= "index" ><a @click="selected = index" :class="index==selected? 'active': '' " href="#">{{elemento.nome}}</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Header',
    data() {
        return {
            menu: [
            {
                nome:'characters',
                state:"true"
            },
            {
                nome:'comics',
                state:"false"
              
            },
             {
                nome:'movies',
                state:"false"
            },
                
            {
                nome:'tv',
                state:"false"
            },
                
            {
                nome:'games',
                state:"false"
            },
                
            {
                nome:'collectibles',
                state:"false"
            },
                
            {
                nome:'videos',
                state:"false"
            },
                
            {
                nome:'fans',
                state:"false"
            },
                
            {
                nome:'news',
                state:"false"
            },
                
            {
                nome:'shop',
                state:"false"
            },
                
            ],
            selected: 999,
        
        }

        },

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
                cursor: pointer;
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
                    
                    .active {
                        color: #0c7cec;
                        }
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
                        a:hover {
                            color: #0c7cec;
                        }
                    }
                   
                }
                }
                
            }
        }
    }
</style>>
    
