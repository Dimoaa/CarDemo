<template>
  <div>
    <md-card class="md-alignment-center-center my-card" md-with-hover>
      <md-ripple>
        <md-card-header>
          <div class="md-title">Introduction</div>
          <div class="md-subhead">A demo works with SIMBA Chain</div>
        </md-card-header>

        <md-card-content>
          <p>This NodeJs (VueJs) web app is a simple demo to illustrate how SIMBA API works. This demo shows how to make a real-world blockchain end-user client working with the API generated by SIMBA, and how to sign transactions (records to be posted on blockchain) with a local Ethereum Wallet.</p>
          <br>
          <br>
          <br>
          <br>
        </md-card-content>
      </md-ripple>
    </md-card>
  </div>
</template>

<script>

export default {
  name: 'Home'
}
</script>

<style lang="scss" scoped>
  .my-card {
    margin-top: 40px;
    width: 300px;
    display: inline-block;
    vertical-align: top;
    margin-bottom: 20px;
  }
</style>
