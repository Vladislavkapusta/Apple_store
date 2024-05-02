<template>
    <div class="HeadContainer">
    <header class="HeadGeneral">
        <img class="logo" src="../images/logo.png" alt="logo">
        <ul>
            <li>
                <a>Весь каталог</a>
            </li>
            <li>
                <a class="onFire">🔥Акции</a>
            </li>
            <li>
                <a>Гарания</a>
            </li>
            <li>
                <a>Политика возврата</a>
            </li>
            <li>
                <a>Кредит</a>
            </li>
            <li>
                <a>Доставка и оплата</a>
            </li>
            <li>
                <a>Отзывы</a>
            </li>
            <li>
                <a>Контакты</a>
            </li>
            <div class="sitePhone">
                <img src="../images/fluent_call-16-filled.svg" alt="sitePhone">
                <p class="phoneNum">+7 812 561 96 62</p>
                <a>Вам позвонить?</a>
            </div>
        </ul>
    </header>
    <div class="searchBar">
        <button class="catalog">
            <img class="catalog_img" src="../images/carbon_overflow-menu-vertical.png" alt="triple">
            <p class="catalog_p">Каталог товаров</p>
        </button>
        <div class="search">
            <img src="../images/akar-icons_search.png" alt="search">
            <input type="text" placeholder="Поиск по каталогу товаров">
        </div>
        <button class="nav_button">
            <img src="../images/icon-park-outline_like.svg" alt="like">
        </button>
        <button class="nav_button">
            <img src="../images/gg_filters.svg" alt="like">
        </button>
        <button class="cart_button">
            <img src="../images/ri_shopping-bag-3-fill.svg" alt="like">
            <p class="catalog_p">в корзине</p>
        </button>
    </div>
    <div class="searchBar">
        <button class="typeOf">
            <img src="../images/iphonex_119956 6.svg" alt="">
            <p class="typeOf_text">IPhone</p>
        </button>
        <button class="typeOf">
            <img src="../images/ipadh_119979 3.svg" alt="">
            <p class="typeOf_text">IPad</p>
        </button>
        <button class="typeOf">
            <img src="../images/macbook_laptop_mac_apple_computer_icon_134097 3.svg" alt="">
            <p class="typeOf_text">Macbook и Imac</p>
        </button>
        <button class="typeOf">
            <img src="../images/applewatch_119991 3.svg" alt="">
            <p class="typeOf_text">Watch</p>
        </button>
        <button class="typeOf">
            <img src="../images/airpods_110489 3.svg" alt="">
            <p class="typeOf_text">Гаджеты</p>
        </button>
        <button class="typeOf">
            <img src="../images/iphonex_119956 5.svg"  alt="">
            <p class="typeOf_text">Аксессуары</p>
        </button>
        <button class="Pro">
            <div class="Pro_Img"></div>
            <p class="typeOf_text Pro_text" style="color: white;">iPhone 14 Pro Max</p>
            <img src="../images/bi_arrow-right-circle.svg" alt="">
        </button>
    </div>
</div>

<div class="HeadContainer_Laptop">
  <img class="logo" src="../images/logo.png" alt="logo">
  <div class="search">
            <img src="../images/akar-icons_search.png" alt="search">
            <input type="text" placeholder="Поиск по каталогу товаров">
  </div>
  <div class="phone">
                <img src="../images/fluent_call-16-filled.svg" alt="sitePhone">
                <p class="phoneNum">+7 812 561 96 62</p>
  </div>
  <img src="../images/bx_menu.png" alt="logo">
</div>

<div class="HeadGeneral_Laptop">
  <button class="typeOf">
            <img src="../images/pepicons_menu.png" alt="">
            <p class="typeOf_text">каталог</p>
        </button>
        <button class="typeOf">
            <img src="../images/ri_shopping-bag-3-fill.png" alt="">
            <p class="typeOf_text">корзина</p>
        </button>
        <button class="typeOf">
            <img src="../images/icon-park-outline_like.png" alt="">
            <p class="typeOf_text">избранное</p>
        </button>
        <button class="typeOf">
            <img src="../images/gg_filters.png" alt="">
            <p class="typeOf_text">сравнение</p>
        </button>
</div>

<div class="HeadContainer_Mobile">
  <img class="logo" src="../images/logo.png" alt="logo">
  <div class="nav_bar">
        <img src="../images/akar-icons_search.png" alt="search">
        <div class="phone">
                      <img src="../images/fluent_call-16-filled.svg" alt="sitePhone">
        </div>
        <img src="../images/bx_menu.png" alt="logo">
  </div>

</div>

<div class="HeadGeneral_Mobile">
  <button class="typeOf">
            <img src="../images/pepicons_menu.png" alt="">
            <p class="typeOf_text">каталог</p>
        </button>
        <button class="typeOf">
            <img src="../images/ri_shopping-bag-3-fill.png" alt="">
            <p class="typeOf_text">корзина</p>
        </button>
        <button class="typeOf">
            <img src="../images/icon-park-outline_like.png" alt="">
            <p class="typeOf_text">избранное</p>
        </button>
        <button class="typeOf">
            <img src="../images/gg_filters.png" alt="">
            <p class="typeOf_text">сравнение</p>
        </button>
</div>


</template>
  
  <script setup>
  </script>
  
  <style scoped>



   @media screen and (width >= 1440px){
  .HeadContainer_Laptop, .HeadGeneral_Laptop,.HeadContainer_Mobile, .HeadGeneral_Mobile {
    display: none;
  }
  .HeadContainer{
    width: 1200px;
  }
 }

  .HeadContainer{
    margin-left: auto;
    margin-right: auto;
  }
  .scroller{
    background: rgb(208, 234, 252);
    width: 1440px;
    height: 480px;
    margin-left: auto;
  }
  .Pro_text{
    font-size: 20px;
    font-weight: 200;
    line-height: 24px;
    letter-spacing: 0%;
    text-align: left;
  }
  .Pro{
    border-radius: 8px;
    background: linear-gradient(90deg, rgb(0, 0, 0) 27%,rgb(94, 85, 107) 100%);
    /* background-color: black; */

    display: flex;
    flex-direction: row;
    border: none;
    outline: none;

    justify-content: center;
    align-items: center;
  }
  .Pro_Img{
    width: 50px;
    height: 50px;
    background-image: url('../images/design_startframe__cffzwjeyro2q_large (1) 1.png');
  }
  .typeOf_text{
    color: rgb(16, 14, 14);
    font-size: 20px;
    font-weight: 400;
    line-height: 24px;
    letter-spacing: 0%;
    text-align: left;
  }
  .typeOf{
    display: flex;
    flex-direction: row;
    background-color: transparent;
    border: none;
    outline: none;

    justify-content: center;
    align-items: center;
  }
  .typeOf>img{

    /* filter: invert(42%) sepia(93%) saturate(1352%) hue-rotate(87deg) brightness(119%) contrast(119%); */
    filter: invert(100%) sepia(0%) saturate(50%) hue-rotate(-87deg) brightness(10%) contrast(0%);

    
  }
  .typeOf:hover>img{
    filter: invert(42%) sepia(93%) saturate(1352%) hue-rotate(87deg) brightness(119%) contrast(119%);
  }
  /* .logo{
    width: 29.55px;
    height: 35.4px;
  } */
  .nav_button{
    background-color: transparent;
    border: none;
    outline: none;
  }
  .nav_button>img{
    background-color: transparent;
  }
  .searchBar{
    /* width: max-content; */
    display: flex;
    flex-direction: row;
    height: 94px;
    align-items: center;
    justify-content: space-between;
    gap: 20px;
  }
  .search{
    box-sizing: border-box;
    /* 03 */
    border: 1px solid rgb(183, 183, 183);
    border-radius: 8px;
    background: rgb(255, 255, 255);
    padding: 18px 0px 18px 26px;

    width: 594px;
    /* height: 56px; */

    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: start;
    gap: 11px;
  }
  .search>input{
    border: none;
    outline: none;
    width: 500px;
    font-family: SF Pro Display;
    font-size: 20px;
    font-weight: 400;
    line-height: 24px;
    letter-spacing: 0%;
    text-align: left;
    
  }
.catalog{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 16px;

    border-radius: 16px;
    border:none;
    background: rgb(0, 113, 228);
}
.cart_button{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 16px 36px 16px 36px;
    gap: 7px;

    border-radius: 16px;
    border:none;
    background: rgb(82, 209, 22);
}
.catalog_p{
    color: rgb(255, 255, 255);
    font-size: 20px;
    font-weight: 400;
    line-height: 24px;
    letter-spacing: 0%;
    text-align: left;
}




.HeadGeneral{
    /* width: max-content; */
    display: flex;
    flex-direction: row;
    height: 94px;
    align-items: center;
    justify-content: space-around;
  }
    ul{
        display: flex;
        flex-direction: row;
        width: auto;
        justify-content: space-between;
        align-items: center;
        list-style: none;
        gap: 20px;
    }
    li{
        text-decoration: none;
        color: rgb(16, 14, 14);
        font-size: 18px;
        font-weight: 400;
        line-height: 21px;
        letter-spacing: 0%;
        text-align: left;
    }
    .onFire{
        padding: 5px;
        border-radius: 8px;
        background: rgb(253, 239, 191);
    }
    .sitePhone{
        width: 176px;
        height: 40px;
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: end;
    }
    .phoneNum{
        color: rgb(16, 14, 14);
        font-family: SF Pro Display;
        font-size: 20px;
        font-weight: 400;
        line-height: 24px;
        text-align: left;
    }
    @media screen and (width < 1440px) and (width > 780px){
  .HeadContainer, .HeadContainer_Mobile, .HeadGeneral_Mobile{
    display: none;
  }
  .HeadContainer_Laptop{
    width: 768px;
    display: flex;
    flex-direction: row;
    height: 40px;
    align-items: center;
    justify-content: space-around;

    margin-left: auto;
    margin-right: auto;
    gap:20px
  }
  .search{
    border: none;
    height: 40px;
    width: 400px;
    padding: 18px 0px 18px 0px;
  }
  .phone{
    display: flex;
    flex-direction: row;
  }
  .HeadGeneral_Laptop{
    display: flex;
    flex-direction: row;
    position: fixed;
    bottom: 0px;
    background-color: white;
    z-index: 2;
    width: 100vw;
    justify-content: space-around;
    margin-left: auto;
    margin-right: auto;
  }
 }
 @media screen and (width < 780px){
  .HeadContainer, .HeadContainer_Laptop, .HeadGeneral_Laptop{
    display: none;
  }
  .HeadContainer_Mobile{
    display: flex;
    flex-direction: row;
    width: 300px;
    padding: 0 10px 0 10px;
    height: 40px;
    align-items: center;
    justify-content: space-between;
    align-items: center;
    margin-left: auto;
    margin-right: auto;
  }
  .HeadContainer_Mobile>img{
    width: 32px;
    height: 32px;
  }
  .nav_bar>img, .phone>img{
    width: 24px;
    height: 24px;
    filter: invert(42%) sepia(93%) saturate(1352%) hue-rotate(87deg) brightness(0%) contrast(119%);
  }
  .nav_bar{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    width: 140px;
  }
  .HeadGeneral_Mobile{
    position: fixed;
    bottom: 0;
    display: flex;
    flex-direction: row;
    background-color: white;
    width: 100vw;
    justify-content: space-around;
    height: 48px;
    z-index: 2;
  }
  .typeOf{
    display: flex;
    flex-direction: column;
    align-items: center;

  }
  .typeOf_text{
    font-size: 13px;
  }
  .typeOf>img{
    width: 24px;
    height: 24px;
  }
 }
  </style>