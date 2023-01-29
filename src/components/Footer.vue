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
          <li><a href="#">Impressum</a></li>
          <li><a href="#">Datenschutz</a></li>
        </ul>
      </div>
    </div>
    <div class="lower">
      Copyright 2023
    </div>
  </div>  
</template>

<script>
</script>

<style scoped>

  .footer {
    width: 100%;
    display: block;
    position: absolute;
    bottom: 0;
  }

  .footer a:hover {
    color: darkred;
  }

  .footer .upper {
    background: #242424;
    height: 200px;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
  }

  .footer .lower {
    background: #000;
    height: 40px;
    display: flex;
    justify-content: center;
    align-items: center;
    box-shadow: 0px 0px 20px #000;
  }

</style>