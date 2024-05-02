<template>
  <div class="color">
    <div class="container">
      <div class="sub_container">
        <img src='../images/img.png'>
        <div class="sub_info">
          <h2>Подписка на рассылку акций!</h2>
          <p class="info_text">Подпишитесь на рассылку, чтобы узнавать о всех акциях первым</p>
          <form @submit.prevent="">
            <h3>Скидка 10%</h3>
            <p>на первую покупку за подписку</p>
            <div class="inputs">
              <input type='tel' placeholder="+ 7">
              <button class="submit" type="submit">подписаться</button>
            </div>
          </form>
        </div>
      </div>
    </div>

    <div class="container_laptop">
      <div class="sub_container">
        <img src='../images/img.png'>
        <div class="sub_info">
          <h2>Подписка на рассылку акций!</h2>
          <p class="info_text">Подпишитесь на рассылку, чтобы узнавать о всех акциях первым</p>
          <form @submit.prevent="">
            <h3>Скидка 10%</h3>
            <p>на первую покупку за подписку</p>
          </form>
          <div class="inputs">
              <input type='tel' placeholder="+ 7">
              <button class="submit" type="submit">подписаться</button>
            </div>
        </div>
      </div>

    </div>

    <div class="container_mobile">
      <div class="sub_container">
        <div class="sub_info">
          <h2>Подписка на рассылку акций!</h2>
          <p class="info_text">Подпишитесь на рассылку, чтобы узнавать о всех акциях первым</p>
          <form @submit.prevent="">
            <h3>Скидка 10%</h3>
            <p>на первую покупку за подписку</p>
          </form>
          <div class="inputs">
              <input type='tel' placeholder="+ 7">
              <button class="submit" type="submit">подписаться</button>
            </div>
        </div>
      </div>

    </div>

  </div>
</template>

<style scoped>
.color{
  background: #F9F9F9;
  padding: 40px 0px 30px 0px;
}
.submit{
  background: #E7E7E7;
  border-radius: 8px;
  width: 160px;
  height: 56px;
  font-size: 16px;
  color: #585656;
  border: none;
}
.inputs{
  display: flex;
  flex-direction: row;
  gap: 15px;
}
  .inputs>input{
    padding: 10px 0px 10px 15px;
    border: 1px solid #DBDBDB;
    width: 231px;
    height: 34px;
    border-radius: 8px;
    font-size: 24px;
  }
  form{
    width: 426px;
    height: 136px;
    display: flex;
    flex-direction: column;
    gap: 7px;
    background: linear-gradient(90.34deg, #F7355D 0.3%, #9747FF 101.33%);
    border-radius: 16px;
    padding: 30px;
  }
  h3{
    font-size: 40px;
    color: white;
  }
  form>p{
    font-size: 20px;
    color: white;
  }
  h2{
    font-size: 48px;
  }
  .info_text{
    color: #585656;
    font-size: 24px
  }
  .sub_container{
    display: flex;
    flex-direction: row;
    gap: 60px;
  }
  .sub_info{
    display: flex;
    flex-direction: column;
    width: 486px;
    gap: 5px;
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
  .container_laptop, .container_mobile{
    display: none;
  }
 }
 @media screen and (width < 1440px) and (width > 780px){
  .container, .container_mobile{
    display: none;
  }
  .container_laptop{
    display: flex;
    flex-direction: column;
    margin-left: auto;
    margin-right: auto;
    gap: 30px;
    width: 768px;
  }
  img{
    width: 225px;
    height: 173px;
  }
  h2{
    font-size: 32px;
    width: 300px;
  }
  .info_text{
    font-size: 16px;
    width: 300px;
  }
  form{
    width: 259px;
    height: 43px;
    padding: 15px;
    justify-content: space-around;
  }
  form>h3{
    font-size: 20px;
  }
  form>p{
    font-size: 16px;
  }
 }
 @media screen and (width < 780px){
  .container_mobile{
    display: flex;
    flex-direction: column;
    margin-left: auto;
    margin-right: auto;
    gap: 30px;
    width: 320px;
  }
  .container, .container_laptop{
    display: none;
  }
  .inputs{
    flex-direction: column;
  }
  .inputs>button{
    width: 320px;
  }
  .inputs>input{
    width: 300px;
  }
  h2{
    font-size: 24px;
    width: 228px;
  }
  .sub_info{
    width: 300px;
  }
  .info_text{
    font-size: 16px;
  }
  form{
    width: 268px;
    height: 56px;
    gap: 3px;
    padding: 0 0 0 20px;
    justify-content: center;
    border-radius: 8px;
  }
  form>h3{
    font-size: 16px;
  }
  form>p{
    font-size: 14px;
  }
 }
</style>

<script>
export default {
    
}
</script>

