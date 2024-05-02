<template>
    <div class='container'>
      <footer>
          <div class="block">
            <img src="../images/logo.png">
            <p class="inf_cen">© 2013-2022</p>
            <p class="inf_cen">Продажа iPhone в МСК</p>
            <p class="inf_smol">*Сайт не является публичной оффертой. Вся информация, указанная на сайте носит информационный характер.</p>
          </div>
          <div class="block links_list">
            <a>Гарантия</a>
            <a>Политика возврата</a>
            <a>Кредит</a>
            <a>Доставка и оплата</a>
            <a>Отзывы</a>
            <a>Контакты</a>
            <a>Политика конфеденциальности</a>
          </div>
          <div class="block links_list">
            <a>iPhone</a>
            <a>iPad</a>
            <a>Macbook и iMac</a>
            <a>Watch</a>
            <a>Аксессуары</a>
            <a>Акция</a>
          </div>
          <div class="block links_list extend">
            <h3>+7 812 704 86 97</h3>
            <p class="inf_cen ">Бесплатная консультация <br>
            С 10:00 до 21:00, без выходных</p>
            <div class="connect">
              <a class="call">Заказать звонок</a>
              <img src="../images/wa.png">
              <img src="../images/tele.png">
              <img src="../images/vk.png">
            </div>
            
            <a>Москва,  ул Барклая 8</a>
            <a>Москва,  ул Барклая 8</a>
          </div>

      </footer>

    </div>



    <div class='container_laptop'>
      <footer>
          <div class="block">
            <img src="../images/logo.png">
            <div class="info_field">
              <p class="inf_cen">© 2013-2022</p>
              <p class="inf_cen">Продажа iPhone в МСК</p>
              <p class="inf_smol">*Сайт не является публичной оффертой. Вся информация,<br> указанная на сайте носит информационный характер.</p>
            </div>

          </div>
          <div class="block links_list">
            <a>Гарантия</a>
            <a>Политика возврата</a>
            <a>Кредит</a>
            <a>Доставка и оплата</a>
            <a>Отзывы</a>
            <a>Контакты</a>
            <a>Политика конфеденциальности</a>
          </div>
          <div class="block links_list">
            <a>iPhone</a>
            <a>iPad</a>
            <a>Macbook и iMac</a>
            <a>Watch</a>
            <a>Аксессуары</a>
            <a>Акция</a>
          </div>
          <div class="block links_list extend">
            <div class="group">
              <h3>+7 812 704 86 97</h3>
            <p class="inf_cen ">Бесплатная консультация <br>
            С 10:00 до 21:00, без выходных</p>
            </div>
            <div class="group">
              <img src="../images/wa.png">
              <img src="../images/tele.png">
              <img src="../images/vk.png">
            </div>
          </div>
          <div class="connect">
              <a class="call">Заказать звонок</a>
            </div>
          <div class="block links_list vert">
            <a>Москва,  ул Барклая 8</a>
            <a>Москва,  ул Барклая 8</a>
          </div>

      </footer>


    </div>

    <div class='container_mobile'>
      <footer>
          <div class="Iphone_block">
            <div class="Iphone_info">
              <img src="../images/logo.png">
            <div class="info_field">
              <p class="inf_cen">© 2013-2022</p>
              <p class="inf_cen">Продажа iPhone в МСК</p>
            </div>
            </div>

            <p class="inf_smol">*Сайт не является публичной оффертой. Вся информация, указанная на сайте носит информационный характер.</p>
          </div>
          <div class="block links_list">
            <a>Гарантия</a>
            <a>Политика возврата</a>
            <a>Кредит</a>
            <a>Доставка и оплата</a>
            <a>Отзывы</a>
            <a>Контакты</a>
            <a>Политика конфеденциальности</a>
          </div>
          <div class="block links_list">
            <a>iPhone</a>
            <a>iPad</a>
            <a>Macbook и iMac</a>
            <a>Watch</a>
            <a>Аксессуары</a>
            <a>Акция</a>
          </div>
          <div class="block links_list extend">

              <h3>+7 812 704 86 97</h3>
            <p class="inf_cen ">Бесплатная консультация <br>
            С 10:00 до 21:00, без выходных</p>
            <div class="connect">
              <a class="call">Заказать звонок</a>
            </div>
            <div class="group">
              <img src="../images/wa.png">
              <img src="../images/tele.png">
              <img src="../images/vk.png">
            </div>
          </div>

          <div class="block links_list vert">
            <a>Москва,  ул Барклая 8</a>
            <a>Москва,  ул Барклая 8</a>
          </div>

      </footer>
      

    </div>
</template>

<style scoped>
.connect{
  display: flex;
  flex-direction: row;
  gap: 5px;
}
h3{
  font-size: 40px;
}
  .block{
    display: flex;
    flex-direction: column;
    gap: 20px;
    justify-content: space-around;
    width: 265px;
  }
  .links_list{
    gap: 15px;
  }
  .extend{
    width: 330px;
    
  }
  .links_list>a{
    font-size: 16px;
  }
  .block>img{
    width: 40px;
  }
  .inf_cen{
    font-size: 16px;
    color: #878787;
  }
  .inf_smol{
    font-size: 14px;
    color: #B7B7B7;
  }
  footer{
    display: flex;
    flex-direction: row;
    align-items: start;
    justify-content: center;
    gap: 30px;
  }
    .container{
    display: flex;
    flex-direction: column;
    margin-left: auto;
    margin-right: auto;
    gap: 30px;
    height: 229px;
    padding: 40px 0px 40px 0px;
  }
  .call{
    font-size: 20px;
    align-self: center;
    text-align: center;
    color: #0071E4;
    margin-right: 40px;
  }
 @media screen and (width > 1440px){
  .container{
    width: 1200px;
  }
  .container_laptop, .container_mobile{
    display: none;
  }
}
@media screen and (width < 1440px) and (width > 780px){
  .container_laptop{
    width: 768px;
    margin-bottom: 120px;
    display: flex;
    flex-direction: column;
    margin-left: auto;
    margin-right: auto;
    gap: 30px;
    padding: 40px 0px 40px 0px;
  }
  .container, .container_mobile{
    display: none;
  }
  footer{
    flex-direction: column;
  }
  .block{
    flex-direction: row;
    flex-wrap: wrap;
    align-items: start;
    justify-content: start;
    height: auto;
    width: auto;
  }
  .inf_cen{
    width: auto;
    height: auto;
  }
  .block>img{
    width: 45px;
    height: 45px;
  }
  img{
    width: 32px;
    height: 32px;
  }
  .info_field{
    display: flex;
    flex-direction: column;
    gap: 10px;
  }
  h3{
    font-size: 32px;
  }
  .vert{
    flex-direction: column;
  }
  .group{
    display: flex;
    gap: 10px;
  }
  .extend{
    justify-content: space-between;
    align-items: start;
    width: 768px;
  }
}







@media screen and (width < 780px){
  .container_mobile{
    width: 320px;
    margin-bottom: 120px;
    display: flex;
    flex-direction: column;
    margin-left: auto;
    margin-right: auto;
    gap: 30px;
    padding: 40px 0px 40px 0px;
  }
  .container, .container_laptop{
    display: none;
  }
  footer{
    flex-direction: column;
  }
  .block{
    flex-direction: column;
    flex-wrap: wrap;
    align-items: start;
    justify-content: start;
    height: auto;
    width: auto;
  }
  .inf_cen{
    font-size: 14px;
    width: auto;
    height: auto;
  }
  .inf_smol{
    font-size: 11px;
    text-align: center;
    width: 200px;
    height: 39px;
  }
  .block>img{
    width: 45px;
    height: 45px;
  }
  img{
    width: 32px;
    height: 32px;
  }
  .info_field{
    display: flex;
    flex-direction: column;
    gap: 5px;
  }
  h3{
    font-size: 32px;
  }
  .vert{
    flex-direction: column;
  }
  .group{
    display: flex;
    gap: 10px;
  }
  .extend{
    justify-content: space-between;
    align-items: start;
    width: 768px;
  }
  .links_list{
    gap: 10px;
  }
  .Iphone_info{
    display: flex;
    gap: 20px;
  }
  .Iphone_block{
    align-items: center;
    display: flex;
    flex-direction: column;
    gap: 20px;
    justify-content: space-around;
    width: 260px;
  }
}
</style>

<script>

</script>

