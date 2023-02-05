<template>
  <div class="footer">
    <div class="upper">
      <div class="left">
        <p>
          <h3>Christian Stegemann</h3>
          <a href="www.myfangs.de">myfangs.de</a><br />
          <a href="mailto:vamps66@web.de">E-Mail</a>
        </p>
      </div>
      <div class="right">
        <ul>
          <li><router-link to="/impressum">Impressum</router-link></li>
          <li><router-link to="/datenschutz">Datenschutz</router-link></li>
        </ul>
      </div>
    </div>
    <div class="lower">
      Copyright 2023 | myfangs
    </div>
  </div>  
</template>

<script lang="ts">
</script>

<style lang="scss" scoped>

  .footer {
    width: 100%;
    display: block;
    position: fixed;
    bottom: 0;
    a:hover {
    color: darkred;
    }
    .upper {
      background: #242424;
      height: 150px;
      display: flex;
      justify-content: space-evenly;
      align-items: center;
    }
    .lower {
    background: #000;
    height: 40px;
    display: flex;
    justify-content: center;
    align-items: center;
    box-shadow: 0px 0px 20px #000;
    }
  }

</style>