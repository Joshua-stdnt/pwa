<template>
  <div>
    <div class="stdnt-sell-box col-3">
      <div class="stdnt-sell-box2">
        <div class="stdnt-sell-title">{{ title }}</div>
        <div class="stdnt-sell-text">
          {{ text }}
        </div>
        <q-btn rounded outline class="stdnt-sell-find">{{ find }}</q-btn>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ['title', 'text', 'find'],
}
</script>

<style lang='sass' scoped>
.stdnt-sell-box
  //width: 400px
  .stdnt-sell-box2
    //margin-left: 100px
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
</style>