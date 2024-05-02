!<template>
    <div class="Info">


    <div class='container'>
        <h3>Новые модели Айфонов по выгодным ценам</h3>
        <p>Для тех, кто хочет приобрести новый телефон магазин Istoreapple.ru предлагает:</p>
            <p>
                Низкие цены на все виды устройств, недорогие аксессуары;<br>
                Оригинальные подарки бренда;<br>
                Новая линейка смартфонов и проверенные старые модели;<br>
                Лаконичный дизайн, большой выбор цветов и оттенков;<br>
                Все товары в каталоге есть в наличии и доступны для покупки в кредит и рассрочку;<br>
                Быстрая доставка по Санкт-Петербургу и области;<br>
                Гарантия на все модели телефонов;<br>
                Все способы оплаты!<br>
                Товары, представленные на официальном сайте Istoreapple.ru, сертифицированы. Мы занимаемся продажей айфонов с 2013 года. Вы всегда можете прочитать отзывы о покупке наших клиентов, позвонить в магазин и получить консультацию по любой модели Apple.
            </p>
    </div>

    <div class="ProAdd">
        <div class="containerAdd">
            <img src="../images/design_startframe__cffzwjeyro2q_large (1) 2.png">
            <div class="ProText">
                <h2>iPhone 14 Pro Max</h2>
                <p>по лучшей цене в Москве</p>
                <button class="more">Подробнее</button>
            </div>
        </div>
    </div>

    <div class="ProAdd_mobile">
        <div class="containerAdd">
            <img src="../images/Pro_mobile.png">
            <div class="ProText">
                <h2>iPhone 14 Pro Max</h2>
                <p>по лучшей цене в Москве</p>
                <button class="more">Подробнее</button>
            </div>
        </div>
    </div>

    <div class='container'>
        <h3>Новые модели Айфонов по выгодным ценам</h3>
        <p>Для тех, кто хочет приобрести новый телефон магазин Istoreapple.ru предлагает:</p>
            <p>
                Низкие цены на все виды устройств, недорогие аксессуары;<br>
                Оригинальные подарки бренда;<br>
                Новая линейка смартфонов и проверенные старые модели;<br>
                Лаконичный дизайн, большой выбор цветов и оттенков;<br>
                Все товары в каталоге есть в наличии и доступны для покупки в кредит и рассрочку;<br>
                Быстрая доставка по Санкт-Петербургу и области;<br>
                Гарантия на все модели телефонов;<br>
                Все способы оплаты!<br>
                Товары, представленные на официальном сайте Istoreapple.ru, сертифицированы. Мы занимаемся продажей айфонов с 2013 года. Вы всегда можете прочитать отзывы о покупке наших клиентов, позвонить в магазин и получить консультацию по любой модели Apple.
            </p>
    </div>

    </div>
</template> 

<style scoped>
.Info{
    display: flex;
    flex-direction: column;
    gap: 40px;
}
.ProText{
    display: flex;
    flex-direction: column;
    gap: 20px;
    justify-content: center;
}
.ProText>h2{
    font-size: 56px;
    color: white;
}
.ProText>p{
    font-size: 24px;
    color: white;
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
    .containerAdd{
        display: flex;
        flex-direction: row;
        margin-left: auto;
        margin-right: auto;
        gap: 30px;
        height: 360px;
    }
    .containerAdd>img{
        height: 360px;
        width: 246px;
    }
    .ProAdd{
       background-color: black; 
       width: 100vw;
    }
    .ProAdd_mobile{
        background-color: black; 
       width: 100vw;
    }
    h3{
        font-size: 32px
    }
    p{
        font-size: 16px
    }
    .container{
    display: flex;
    flex-direction: column;
    margin-left: auto;
    margin-right: auto;
    gap: 30px
  }
 @media screen and (width > 1440px){
    .ProAdd_mobile{
        display: none;
    }
  .container{
    width: 1200px;
  }
  .containerAdd{
    width: 1200px;
  }
 }
 @media screen and (width < 1440px) and (width > 780px){
    .ProAdd_mobile{
        display: none;
    }
  .container{
    width: 768px;
  }
  .containerAdd{
    width: 768px;
  }
 }
 @media screen and (width < 780px){
    .ProAdd{
        display: none;
    }
  .container{
    width: 320px;
  }
  .containerAdd{
    width: 320px;
    height: 151px;
  }
  h3{
    font-size: 24px;
  }
  p{
    font-size: 16px;
  }
  .containerAdd>img{
    width: 65px;
    height: 151px;
  }
  .ProText{
    display: flex;
    flex-direction: column;
    gap: 10px;
    justify-content: center;
}
.ProText>h2{
    font-size: 20px;
    color: white;
}
.ProText>p{
    font-size: 16px;
    color: white;
}
.more{
        background-color: #0071E4;
        color: white;
        width: 160px;
        height: 40px;
        border: none;
        border-radius: 8px;

        font-size: 16px;
    }
 }
</style>

<script>
export default {
    
}
</script>

