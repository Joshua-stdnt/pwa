<template>
  <div>
    <q-layout view="hHh lpR fFf">
      <q-page-container>
        <q-page>
          <!-- Header -->
          <div align="center">
            <div class="header row justify-between items-center">
              <div class="row">
                <img
                  src="~/assets/images/logo.svg"
                  alt="logo"
                  style="margin-right: 5px"
                />

                <div class="header-logo">STDNT</div>
              </div>
              <div class="row header-component items-center">
                <q-btn outline round icon="search"></q-btn>
                <div class="header-components">BUY</div>
                <div class="header-components">SELL</div>
                <div class="header-components">ACCOUNT</div>
                <div class="header-components">CONTACT</div>
              </div>
            </div>
          </div>
          <!-- Body -->
          <div align="center">
            <!-- Title-->
            <div class="stdnt-title">
              A CONVENIENT WAY TO BUY AND SELL TEXTBOOKS
            </div>
            <!-- Sell section -->
            <div class="stdnt-sell row no-wrap justify-center">
              <div class="stdnt-sell-box col-3">
                <div class="stdnt-sell-box2">
                  <div class="stdnt-sell-title">SELL</div>
                  <div class="stdnt-sell-text">
                    SELL YOUR OLD TEXTBOOKS EASILY BY CREATING A NEW LISTING ON
                    OUR WEBSITE.
                  </div>
                  <q-btn rounded outline class="stdnt-sell-find"
                    >FIND OUT MORE</q-btn
                  >
                </div>
              </div>

              <img
                class="stdnt-sell-image col-8"
                src="~/assets/images/im1.svg"
                alt="office"
              />
            </div>
            <!-- Buy section -->
            <div class="stdnt-buy row no-wrap justify-center">
              <img
                class="stdnt-buy-image col-8"
                src="~/assets/images/im2.svg"
                alt="office"
              />
              <div class="stdnt-buy-box col-3">
                <div class="stdnt-buy-box2">
                  <div class="stdnt-buy-title">BUY</div>
                  <div class="stdnt-buy-text">
                    SEARCH FOR A BOOK YOU NEED AND BUY IT. IT’S THAT EASY.
                  </div>
                  <q-btn rounded outline class="stdnt-buy-find"
                    >FIND OUT MORE</q-btn
                  >
                </div>
              </div>
              <div style="margin-right: 100px">
                <!--SellBuy :title="title" :text="text" :find="find" /-->
              </div>
            </div>
            <!-- Collect Deliver -->
            <div class="stdnt-coldel row no-wrap justify-center">
              <div class="stdnt-coldel-collect">
                <div class="stdnt-coldel-title">Collect</div>
                <div class="stdnt-coldel-text">
                  WE’LL FETCH THE BOOK FROM YOU AND MAKE SURE IT GET’S TO THE
                  RIGHT PLACE.
                </div>
                <img
                  class="stdnt-coldel-img"
                  src="~/assets/images/im3.svg"
                  alt="collect"
                />
                <div class="stdnt-coldel-sell">
                  <div>BUY</div>
                </div>
              </div>
              <div class="stdnt-coldel-collect">
                <div class="stdnt-coldel-title">deliver</div>
                <div class="stdnt-coldel-text">
                  WE’LL BRING YOUR NEW PURCHASE TO YOUR DOOR OR WHEREVER YOU’D
                  PREFER.
                </div>
                <img
                  class="stdnt-coldel-img"
                  src="~/assets/images/im4.svg"
                  alt="deliver"
                />
              </div>
            </div>
          </div>
        </q-page>
      </q-page-container>
    </q-layout>
  </div>
</template>

<script>
import SellBuy from '~/components/SellBuy'
export default {
  components: { SellBuy },
  data() {
    return {
      title: 'BUY',
      text: 'SEARCH FOR A BOOK YOU NEED AND BUY IT. IT’S THAT EASY.',
      find: 'FIND OUT MORE',
      img: '~/assets/images/im2.svg',
    }
  },
}
</script>

<style lang='sass' scoped>
.q-page
  background: linear-gradient(90deg, #0B409C 0%, #05255E 100%)
.header
  max-width: 1280px
  padding: 24px 34px 24px 34px
  .header-logo
    font-family: Junegull
    font-style: normal
    font-weight: normal
    font-size: 48px
  .header-components
    font-family: Helvetica
    font-style: normal
    font-weight: normal
    font-size: 18px
    margin-left: 34px
.stdnt-title
  max-width: 1200px
  margin-top: 46px
  font-family: 'Junegull', sans-serif
  font-style: normal
  font-weight: normal
  font-size: 85px
  line-height: 85px
  letter-spacing: -0.01em
.stdnt-sell
  //max-width: 1200px
  height: 450px
  .stdnt-sell-box
    width: 300px
    margin-left: 100px
    .stdnt-sell-box2
      margin-left: 100px
      width: 400px
      .stdnt-sell-title
        margin-top: 161px
        font-family: Junegull
        font-style: normal
        font-weight: normal
        font-size: 64px
        line-height: 64px
      .stdnt-sell-text
        margin-top: 1px
        font-family: Helvetica
        font-style: normal
        font-weight: normal
        font-size: 18px
        line-height: 21px
        text-align: center
        letter-spacing: -0.01em
      .stdnt-sell-find
        margin-top: 7px
        font-family: Helvetica
        font-style: normal
        font-weight: normal
        font-size: 13px
        color: rgba(255, 255, 255, 0.5)
  .stdnt-sell-image
    margin-right: 100px
    width: 800px
    height: 800px
.stdnt-buy
  margin-left: 300px
  height: 600px
  .stdnt-buy-box
    width: 300px
    margin-right: 300px
    .stdnt-buy-box2
      //margin-right: 200px
      width: 400px
      .stdnt-buy-title
        margin-top: 161px
        font-family: Junegull
        font-style: normal
        font-weight: normal
        font-size: 64px
        line-height: 64px
      .stdnt-buy-text
        margin-top: 1px
        font-family: Helvetica
        font-style: normal
        font-weight: normal
        font-size: 18px
        line-height: 21px
        text-align: center
        letter-spacing: -0.01em
      .stdnt-buy-find
        margin-top: 7px
        font-family: Helvetica
        font-style: normal
        font-weight: normal
        font-size: 13px
        color: rgba(255, 255, 255, 0.5)
  .stdnt-buy-image
    //margin-right: 100px
    width: 800px
    height: 800px
.stdnt-coldel
  max-width: 1200px
  margin-right: 90px
  .stdnt-coldel-collect
    .stdnt-coldel-title
      font-family: Junegull
      font-style: normal
      font-weight: normal
      font-size: 64px
      line-height: 64px
    .stdnt-coldel-text
      margin-bottom: 5px
      width: 402px
      font-family: Helvetica
      font-style: normal
      font-weight: normal
      font-size: 18px
      line-height: 21px
      text-align: center
      letter-spacing: -0.01em
    //margin-right: 50px
    .stdnt-coldel-img
</style>
