<template>
    <div class='scroller'>
        <div class="card_list">
            <button class="nav_button">
                <img src="../images/dashicons_arrow-left-alt2.svg" alt="">
            </button>
            <div class="card_container">
                <div class="image"></div>
                <div class="text_field">
                    <div class="name">
                        <h2>iPh</h2>
                        <div class="oval"></div>
                        <h2>ne 14</h2>
                    </div>
                    <div class="price">
                        <p>от</p>
                        <h3>137 900 ₽</h3>
                    </div>
                    <button class="more">подробнее</button>
                </div>
            </div>
            <button class="nav_button">
                <img src="../images/dashicons_arrow-right-alt2.svg" alt="">
            </button>
        </div>
    </div>


    <div class='scroller_laptop'>
        <div class="card_list">
            <button class="nav_button">
                <img src="../images/dashicons_arrow-left-alt2.svg" alt="">
            </button>
            <div class="card_container">
                <div class="text_field">
                    <div class="name">
                        <h2>iPh</h2>
                        <div class="oval"></div>
                        <h2>ne 14</h2>
                    </div>
                    <div class="price">
                        <p>от</p>
                        <h3>137 900 ₽</h3>
                    </div>
                    <button class="more">подробнее</button>
                    <div class="image"></div>
                </div>
            </div>
            <button class="nav_button">
                <img src="../images/dashicons_arrow-right-alt2.svg" alt="">
            </button>
        </div>
    </div>

    <div class='scroller_mobile'>
        <div class="card_list">
            <button class="nav_button">
                <img src="../images/dashicons_arrow-left-alt2.svg" alt="">
            </button>
            <div class="card_container">
                <div class="text_field">
                    <div class="name">
                        <h2>iPh</h2>
                        <div class="oval"></div>
                        <h2>ne 14</h2>
                    </div>
                    <div class="price">
                        <p>от</p>
                        <h3>137 900 ₽</h3>
                    </div>
                    <button class="more">подробнее</button>
                    <div class="image"></div>
                </div>
            </div>
            <button class="nav_button">
                <img src="../images/dashicons_arrow-right-alt2.svg" alt="">
            </button>
        </div>
    </div>
    <div class="Buy">
        <h3>купить iPhone в Москве</h3>
    </div>
</template>

<style scoped>
     @media screen and (width > 1440px){
        .scroller_laptop, .scroller_mobile{
            display: none;
        }

 }
    .scroller_mobile{
        background: rgb(208, 234, 252);
        width: 100vw;
        height: 320px;
    }
    .scroller_laptop{
        background: rgb(208, 234, 252);
        width: 100vw;
        height: 480px;
    }
    .Buy{
        height: 115px;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .Buy>h3{
        font-size: 48px
    }
    .more{
        background-color: #0071E4;
        color: white;
        width: 160px;
        height: 56px;
        border: none;
        border-radius: 8px;

        font-size: 16px;
    }
    .price{
        display: flex;
        flex-direction: row;
        gap: 20px;
        align-items: end;
    }
    .price>p{
        color: rgb(30, 50, 64);
        font-size: 32px;
    }
    .price>h3{
        color: rgb(30, 50, 64);
        font-size: 48px;
        height: 54px;
    }
    .name{
        display: flex;
        flex-direction: row;
        width: 457px;
        height: 84px;
        align-items: center;
    }
    h2{
        color: rgb(30, 50, 64);
        font-size: 88px;
        font-weight: 700;
        line-height: 105px;
        letter-spacing: 0%;
        text-align: left;
        align-self: self-end;
    }
    .text_field{
        height: 340px;
        display: flex;
        flex-direction: column;
        gap: 20px;
    }
    .oval{
        box-sizing: border-box;
        border: 11px solid rgb(30, 50, 64);
        border-radius: 500px;
        width: 101px;
        height: 45px;
    }
    .image{
        width: 398px;
        height: 380px;
        background-image: url('../images/orig (66) 1.png');
        background-repeat: no-repeat;
        background-size: contain;
    }
    .card_container{
        width: 1000px;
        height: 479px;
        display: flex;
        align-items: end;
        justify-content: center;
        gap: 50px;
    }
    .card_list{
        display: flex;
        flex-direction: row;
        width: 1300px;
        margin: 0 auto;
        align-items: center;
        justify-content: space-between;
    }
    .nav_button{
        background-color: transparent;
        border: none;
        outline: none;
    }
    .scroller{
        background: rgb(208, 234, 252);
        width: 100vw;
        height: 480px;
    }
    @media screen and (width < 1440px) and (width >780px){
        .scroller, .scroller_mobile{
            display: none;
        }
        .card_list{
            width: 768px;
        }
        .card_container{
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-between;
        }
        .text_field{
            justify-content: space-between;
            align-items: center;
            height: 479px;
        }
        h2{
            font-size: 60px;
            height: 72px;
            text-align: center;
        }
        .oval{
            width: 68px;
            height: 30px;
            border: 7.41px solid #1E3240;
        }
        .name{
            justify-content: center;
            height: 72px;
            align-items: end;
        }
        .image{
            width: 269px;
            height: 324px;
        }
 }
 @media screen and (width < 780px){
    .scroller, .scroller_laptop{
            display: none;
        }
    
    .card_list{
        width: 320px;
    }
    .oval{
            width: 42px;
            height: 19px;
            border: 4.63px solid #1E3240;
        }
        .card_container{
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-between;
            width: 240px;
            height: 300px;
            padding-top: 20px;
        }
        .text_field{
            justify-content: space-between;
            align-items: center;
            height: 420px;
            gap: 10px;
        }
        h2{
            font-size: 36px;
            height: 72px;
            text-align: center;
        }
        .name{
            height: 32px;
            width: 320px;
            justify-content: center;
            align-items: center;
        }
        .image{
            width: 170px;
            height: 160px;
        }
        .price{
            align-items: center;
            gap: 5px;
        }
        .price>p{
            font-size: 20px;
        }
        .price>h3{
            font-size: 32px;
            height: auto;
        }
        .more{
            height: 40px;
            font-size: 16px;
        }
        .nav_button{
            width: 40px;
            height: 40px;
        }
        .Buy>h3{
            font-size: 24px;
        }
 }
</style>

<script>
export default {
    
}
</script>
