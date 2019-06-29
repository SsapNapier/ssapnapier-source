<template>
  <section>
      <div class="header">
        <div class="FirstBall">
          <img src="first.svg" alt="">
        </div>
      </div>
      <div class="container">
         <div class="MassMediaLinks">
          <div class="first">
            <a href="https://www.linkedin.com/in/%D0%B5%D0%BB%D0%B5%D0%BD%D0%B0-%D0%BC%D0%B8%D1%85%D0%B5%D0%B5%D0%B2%D0%B0-b84002187?trk=people-guest_profile-result-card_result-card_full-click">
             <img class="Social" src="/linked.svg" alt="#">
            </a>
          </div>
          <div class="second">
           <a href="https://web.facebook.com/horkorr">
            <img class="Social" src="/fb.svg" alt="#">
           </a>
          </div>
          <div class="third">
            <a href="https://www.instagram.com/cheize/">
            <img class="Social" src="/inst.svg">
            </a>
          </div>
          <div class="fourth">
           <a href="https://vk.com/id8847779">
            <img class="Social" src="/vk_ic.svg" href="">
           </a>
          </div>
        </div>
        <div class="Content">
            <div class="SecondBall"></div>
          <div class="Name">
            <span>
              <h1 class="Member">Elena Mikheeva</h1>
            </span>
          </div>
        </div>
        <div class="Mail">
          <h3 class="E-adress">eo.mikheeva@gmail.com</h3>
        </div>
        <div class="Phone">
          <h3 class="Number">+7 (915) 369-43-96</h3>
        </div>
      </div>
      <footer>
        <div  class="OtherText">
          <div class="ThirdBall">
            <img src="second.svg" alt="">
          </div>
          <div class="footerLine">
            <div class="love">
              <p class="studio">In love with BI</p>
            </div>
            <div class="logo">
              <div class="studio">
                <p>Founder & CEO of</p>
              </div>
              <div class="web">
                <a href="https://its-web.ru/">
                  <img  src="/iw_logo_site.svg" alt="#">
                </a>
              </div>
            </div>
          </div>
        </div>
      </footer>
  </section>
</template>

<script>

</script>

<style lang="sass">
@import '../assets/variables'
.header
  min-height: 24.2vh
@media screen and (max-width: 768px)
  .header
    min-height: 26.5vh
  .container
    min-height: 67vh
@media screen and (max-height: 350px)
   .header
     min-height: 14vh
   .container
     min-height: 70vh
@media screen and (max-width: 480px)
  .header
    min-height: 0vh
  .container
    min-height: 100vh
    overflow: hidden
.FirstBall
  position: absolute
  left: 86%
  width: 14%
  padding-top: 14%
  border-radius: 0 0 15% 100% / 0 0 0% 100%
  background-color: $BallColor
  z-index: 1
.FirstBall img
  display: none
@media screen and (max-width: 1024px)
  .FirstBall
    left: 82%
    width: 18%
    padding-top: 18%
@media screen and (max-width: 480px)
  .FirstBall
    background: 0
    padding-top: 0
    left: 50%
    width: 50%
  .FirstBall img
    width: 100%
    display: block
.MassMediaLinks
  position: relative
  display: flex
  justify-content: space-between
  align-items: center
  width: 24%
  margin: 0 auto
  min-height: 19.8vh
.MassMediaLinks .Social
  width: 100%
  transition: .5s ease
.first,
.second,
.third,
.fourth
  z-index: 2
  width: 14.5%
  min-width: 37px
.first:hover .Social,
.second:hover .Social,
.third:hover .Social,
.fourth:hover .Social
  opacity: 0.3
@media screen and (max-width: 768px)
  .MassMediaLinks
    width: 30%
  .first,
  .second,
  .third,
  .fourth
    max-height: 16%
    min-width: 30px
@media screen and (max-width: 480px)
  .MassMediaLinks
    position: relative
    min-height: 27vh
    min-width: 87%
    margin-top: 0
  .MassMediaLinks .Social
    width: 121%
.Content
  position: relative
  display: flex
  min-height: 18vh
@media screen and (max-width: 768px)
  .Content
    min-height: 16vh
.SecondBall
  position: absolute
  display: flex
  width: 14%
  margin-top: -9.7%
  padding-top: 27.6%
  border-radius: 0 100% 100% 0 / 0 50% 50% 0
  background-color: $BallColor
  z-index: 1
.ThirdBall
  display: none
@media screen and (max-width: 1024px)
  .SecondBall
    width: 18%
    padding-top: 36%
    margin-top: -14.4%
@media screen and (max-width: 768px)
  .SecondBall
@media screen and (max-width: 480px)
  .SecondBall
    width: 0
    background: none
.Name
  position: relative
  left: 6.5%
  display: flex
  z-index: 2
@media screen and (max-width: 768px)
  .Name
    min-height: 8vh
.Name .Member
  color: $NameColor
  font-family: Klaxons
  font-size: 3.54rem
  letter-spacing: 0.395em
  font-weight: normal
  display: flex
.Mail
  position: relative
  display: flex
  justify-content: center
  min-height: 13.3vh
.Mail .E-adress
  color: white
  font-family: AvenirNextLight
  font-size: 1.4rem
  font-weight: 200
  z-index: 2
@media screen and (max-width: 768px)
  .Mail
    min-height: 13vh
  .Mail .E-adress
    font-size: 2.1rem
@media screen and (max-width: 480px)
  .Name
    left: 2.5%
    min-height: 18.2vh
  .Name .Member
    text-align: center
    font-size: 5.4rem
  .Mail
    min-height: 12vh
  .Mail .E-adress
    position: relative
    margin: auto
    font-weight: 200
    font-size: 3.105rem
.Phone
  position: relative
  display: flex
  justify-content: center
  min-height: 17.8vh
@media screen and (max-width: 768px)
  .Phone
    min-height: 0vh
.Phone .Number
  color: white
  font-family: AvenirNextLight
  font-weight: 200
  font-size: 1.35rem
  z-index: 2
@media screen and (max-width: 768px)
  .Phone .Number
    font-size: 1.6rem
@media screen and (max-width: 480px)
  .Phone
    position: relative
    margin: auto
    min-height: 4.4vh
    padding-bottom: 25%
  .Phone .Number
    margin: auto
    font-size: 3.1rem
@media screen and (max-height: 350px)
  .Phone
    position: relative
    margin: auto
    padding-bottom: 0%
.OtherText
  display: flex
  position: relative
  font-family: AvenirNext
  color: white
.footerLine
  display: flex
  margin: auto
  font-size: 20px
  justify-content: space-between
  width: 95%
.OtherText .studio
  font-size: 0.68rem
.love,
.logo
  display: flex
  z-index: 1
  align-items: center
.logo .studio
  align-items: center
  flex-shrink: 0
  margin-right: 3%
.logo .web
    align-items: center
    margin-left: 1%
    height: 80%
.logo .web img
    height: 80%
@media screen and (max-width: 768px)
  .OtherText .studio
    font-size: 1rem
@media screen and (max-width: 480px)
  .OtherText
    bottom: 0%
    width: 100%
  .footerLine
    position: absolute
    bottom: 0
    padding-bottom: 11.5vh
    flex-direction: column
    align-items: center
    width: 100%
  .OtherText .studio
    font-size: 3.12rem
  .logo
    margin-top: 2vh
  .ThirdBall
    position: absolute
    bottom: 0
    width: 28%
    display: flex
  .ThirdBall img
    position: absolute
    bottom: 0
    width: 100%
@media screen and (max-width: 768px)
  .logo .web
     height: 80%
     margin-left: 3%
  .logo .web img
     height: 80%
@media screen and (max-width: 480px)
  .logo .web
    margin-left: 1%
    height: 90%
</style>
