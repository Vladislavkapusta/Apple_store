<template>
    <div class='container'>
        <h3>Наши преимущества</h3>

        <div class='cards_list'>

            <div class='card_container red'>
            <div class ='card'>
                <img src="../images/discount.png">
                <h4>Акции и подарки</h4>
                <p>Постоянные акции, бонусы и скидки. Покупайте технику Apple по самым выгодным ценам</p>

            </div>
            <button class='more'>подробнее</button>
            </div>

            <div class='card_container purple'>
            <div class ='card'>
                <img src="../images/delivery.png">
                <h4>Доставим <br>за 3 часа</h4>
                <p>Быстрая и бесплатная доставка по Москве. Доставим за 3 часа в день заказа. Также доступна быстрая доставка по всей России или самовывоз</p>

            </div>
            <button class='more'>подробнее</button>
            </div>

            <div class='card_container blue'>
            <div class ='card'>
                <img src="../images/card_wallet.png">
                <h4>Удобные способы<br> оплаты</h4>
                <p>Наличными или картой при получении, оплата на сайте или в кредит</p>

            </div>
            <button class='more'>подробнее</button>
            </div>

            <div class='card_container yellow'>
            <div class ='card'>
                <img src="../images/building_with_columns.png">
                <h4>Покупка в кредит</h4>
                <p>Получите самое выгодное кредитное предложение от более чем 30 ведущих банков страны</p>

            </div>
            <button class='more'>подробнее</button>
            </div>

            <div class='card_container green'>
            <div class ='card'>
                <img src="../images/approval.png">
                <h4>Гарантия</h4>
                <p>Все товары, представленные в нашем сайте, имеют гарантию
от нашего магазина или компании Apple</p>

            </div>
            <button class='more'>подробнее</button>
            </div>
        </div>

        <div class='cards_list_laptop'>

<div class='card_container'>
<div class ='card'>
    <img src="../images/discount.png">
    <div class="textSpace">
    <h4>Акции и подарки</h4>
    <p>Постоянные акции, бонусы и скидки. Покупайте технику Apple по самым выгодным ценам</p>
    </div>
</div>
<button class='more'>подробнее</button>
</div>

<div class='card_container'>
<div class ='card'>
    <img src="../images/delivery.png">
    <div class="textSpace">
    <h4>Доставим за 3 часа</h4>
    <p>Быстрая и бесплатная доставка по Москве. Доставим за 3 часа в день заказа. Также доступна быстрая доставка по всей России или самовывоз</p>
    </div>
</div>
<button class='more'>подробнее</button>
</div>

<div class='card_container'>
<div class ='card'>

    <img src="../images/card_wallet.png">
    <div class="textSpace">
    <h4>Удобные способы оплаты</h4>
    <p>Наличными или картой при получении, оплата на сайте или в кредит</p>
</div>
</div>
<button class='more'>подробнее</button>
</div>

<div class='card_container'>
<div class ='card'>
    <img src="../images/building_with_columns.png">
    <div class="textSpace">
    <h4>Покупка в кредит</h4>
    <p>Получите самое выгодное кредитное предложение от более чем 30 ведущих банков страны</p>
</div>
</div>
<button class='more'>подробнее</button>
</div>

<div class='card_container'>
<div class ='card'>
    <img src="../images/approval.png">
    <div class="textSpace">
    <h4>Гарантия</h4>
    <p>Все товары, представленные в нашем сайте, имеют гарантию
от нашего магазина или компании Apple</p>
    </div>
</div>
<button class='more'>подробнее</button>
</div>
</div>

<div class='cards_list_mobile'>

<div class='card_container'>
<div class ='card'>

    <div class="textSpace">
    <h4>     <img src="../images/discount.png"> Акции и подарки</h4>
    <p>Постоянные акции, бонусы и скидки. Покупайте технику Apple по самым выгодным ценам</p>
    </div>
</div>
</div>

<div class='card_container'>
<div class ='card'>
    <div class="textSpace">
    <h4>     <img src="../images/delivery.png"> Доставим за 3 часа</h4>
    <p>Быстрая и бесплатная доставка по Москве. Доставим за 3 часа в день заказа. Также доступна быстрая доставка по всей России или самовывоз</p>
    </div>
</div>
</div>

<div class='card_container'>
<div class ='card'>


    <div class="textSpace">
    <h4><img src="../images/card_wallet.png">Удобные способы оплаты</h4>
    <p>Наличными или картой при получении, оплата на сайте или в кредит</p>
</div>
</div>
</div>

<div class='card_container'>
<div class ='card'>

    <div class="textSpace">
    <h4>     <img src="../images/building_with_columns.png">Покупка в кредит</h4>
    <p>Получите самое выгодное кредитное предложение от более чем 30 ведущих банков страны</p>
</div>
</div>
</div>

<div class='card_container'>
<div class ='card'>

    <div class="textSpace">
    <h4>     <img src="../images/approval.png">Гарантия</h4>
    <p>Все товары, представленные в нашем сайте, имеют гарантию
от нашего магазина или компании Apple</p>
    </div>
</div>
</div>
</div>

    </div>

    
</template>

<script>
export default {
    
}
</script>

<style scoped>

    .card{
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: 20px;
    }

    .card>p{
        font-size: 16px;
        width: 212px;
        align-self: center;
        color: #585656;

    }

    h3{
        align-self: center;
        font-size: 32px;
    }

    h4{
        align-self: center;
        font-size: 24px;
        text-align: start;
    }

    .card_container{
        width: 228px;
        height: 460px;
        border-radius: 16px;
        padding-top: 40px;
        text-align: center;
        display: inline;
        position: relative;
    }
    .more{
        position: absolute;
        bottom: 20px;
        left: 8px;
        width: 212px;
        height: 56px;
        background-color: transparent;
        border: 1px solid #0071E4;
        border-radius: 8px;
        font-size: 18px;
        color: #0071E4;
    }

    .red{
        background: linear-gradient(180.04deg, #FE94A6 0.04%, white);
    }
    .purple{
        background: linear-gradient(180.04deg, #E685FF 0.04%, white);
    }
    .blue{
        background: linear-gradient(180.04deg, #7DE9FF 0.04%, white);
    }
    .yellow{
        background: linear-gradient(180.04deg, #FFE685 0.04%, white);
    }
    .green{
        background: linear-gradient(180.04deg, #ADFFC1 0.04%, white);
    }

    .cards_list{
        display: flex;
        flex-direction: row;
        gap: 10px;
    }

    .container{
    display: flex;
    flex-direction: column;
    margin-left: auto;
    margin-right: auto;
    gap: 30px;
    width: 1200px;
  }
 @media screen and (width > 1440px){
  .container{
    width: 1200px;
  }
  .cards_list_laptop, .cards_list_mobile{
    display: none;
  }
 }
 @media screen and (width < 1440px) and (width > 780px){
  .container{
    width: 768px;
  }
  .cards_list, .cards_list_mobile{
    display: none;
  }
  .cards_list_laptop{
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .card_container{
    height: 158px;
    width: 720px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: start;
    padding: 0;
    gap: 20px;
  }
  .card{
    flex-direction: row;
    height: 158px;
    justify-content: center;
    align-items: start;
  }
  .card>img{
    width: 64px;
    height: 64px;
  }
  .more{
    position: relative;
  }
  .textSpace{
    display: flex;
    flex-direction: column;
    align-items: start;
    justify-content: start;
    text-align: start;

    width: 300px;
  }
  h4{
    text-align: start;
    align-self: flex-start;
    width: 350px;
    font-size: 24px;
  }

 }

 @media screen and (width < 780px){

  .container{
    width: 280px;
  }
  .cards_list, .cards_list_laptop{
    display: none;
  }
  .textSpace{
    display: flex;
    flex-direction: column;
    align-items: start;
    justify-content: start;
    gap: 10px;
  }
  img{
    height: 32px;
    width: 32px;
  }
  h4{
    /* width: 300px; */
    display: flex;
    align-self: self-start;
    align-items: center;
    gap: 10px;
  }
  p{
    width: 230px;
    text-align: start;
  }
  .cards_list_mobile{
        display: flex;
        flex-direction: column;

        align-items: center;
        justify-content: center;
        width: 280px;
    }
    .card_container{
        height: auto;
        width: 280px;
        align-items: start;
        justify-content: start;
        
    }
    .card{
        align-items: start;
    }
    h3{
        font-size: 24px;
    }
  }
</style>