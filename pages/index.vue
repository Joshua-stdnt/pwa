<template>
  <div>
    <q-layout view="hHh lpR fFf">
      <q-page-container>
        <q-page>
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
          <div align="center">
            <div class="stdnt-title">
              A CONVENIENT WAY TO BUY AND SELL TEXTBOOKS
            </div>
            <div class="stdnt-sell row no-wrap">
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
          </div>
        </q-page>
      </q-page-container>
    </q-layout>
  </div>
</template>

<script>
export default {}
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
  max-width: 1200px
  .stdnt-sell-box
    //width: 400px
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
    width: 75%
    height: 75%
</style>
