<template>
  <section>
    <div class="wrap">
      <div class="header">
        <div class="FirstBall">
          <img src="oval1.png" alt="">
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
          <div class="SecondBall">
          </div>
          <div class="Name">
            <h1 class="Member">Elena Mikheeva</h1>
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
            <img src="oval2.png" alt="">
          </div>
          <div class="footerLine">
            <div class="love">
              <p class="studio">In love with BI</p>
            </div>
            <div class="logo">
              <div class="studio">
                <p>Founder & CEO of</p>
              </div>
              <div class="need">
		             &nbsp;
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
      </div>

  </section>
</template>

<script>

</script>

<style lang="sass">
@import '../assets/variables'
.header
 min-height: 25vh
.container
  min-height: 68vh
  overflow: hidden
@media screen and (max-width: 480px)
  .header
    min-height: 1vh
  .container
    min-height: 99vh
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
  margin: auto
  min-height: 18vh
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
  .MassMediaLinks .Social
    max-height: 10vh
  .first,
  .second,
  .third,
  .fourth
    max-height: 16%
    min-width: 30px
@media screen and (max-width: 480px)
  .MassMediaLinks
    min-height: 26vh
    min-width: 87%
    margin-top: 0
  .MassMediaLinks .Social
    width: 121%
.Content
  display: -webkit-flex
  -webkit-align-items: center
  display: flex
  align-items: center
  // margin-top: 7vh
@media screen and (max-width: 1024px)
  .Content
    // margin-top: 9%
.SecondBall
  position: absolute
  display: flex
  align-items: center
  width: 14%
  padding-top: 28%
  border-radius: 0 100% 100% 0 / 0 50% 50% 0
  background-color: $BallColor
  z-index: 1
.ThirdBall
  display: none
@media screen and (max-width: 1024px)
  .SecondBall
    width: 18%
    padding-top: 36%
@media screen and (max-width: 480px)
  .SecondBall
    background: none
.Name
  position: relative
  left: 14px
  display: flex
  margin: 0 auto
  z-index: 2
@media screen and (max-width: 768px)
  .Name
    left: 10px
.Name .Member
  color: $NameColor
  font-family: Klaxons
  font-size: 3.55rem
  letter-spacing: 0.38em
  font-weight: normal
  display: flex
.Mail
  display: flex
  justify-content: center
.Mail .E-adress
  color: white
  font-family: AvenirNextLight
  font-size: 1.4rem
  font-weight: 200
  margin-top: 6vh
  z-index: 2
@media screen and (max-width: 1024px)
  .Mail .E-adress
     margin-top: 8%
@media screen and (max-width: 768px)
  .Mail .E-adress
    margin-top: 9%
    font-size: 2.1rem
@media screen and (max-width: 480px)
  .Name
    min-height: 22vh
  .Name .Member
    text-align: center
    left: 10px
    font-size: 5.4rem
  .Mail .E-adress
    position: relative
    margin: auto
    font-weight: 200
    min-height: 8.5vh
    font-size: 3.105rem
.Phone
  display: flex
  justify-content: center
  margin-top: 8.5vh
  padding-bottom: 0vh
@media screen and (max-width: 768px)
  .Phone
     margin-top: 12%
     padding-bottom: 15%
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
    min-height: 4vh
    padding-bottom: 25%
  .Phone .Number
    margin: auto
    font-size: 3.1rem
.OtherText
  display: flex
  position: relative
  font-family: AvenirNext
  color: white
.footerLine
  display: flex
  padding-bottom: vh
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
    padding-bottom: calc(11.5vh - 0%)
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
