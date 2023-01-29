<template>
  <div class="header">
    <div class="upper">
      <div class="logo">Logo</div>
    </div>
    <div class="lower">
      <div class="nav">
        <ul>
          <a href="#"><li>Vampirzähne</li></a>
          <a href="#"><li>Über mich</li></a>
          <a href="#"><li>Referenzen</li></a>
          <a href="#"><li>Angebot & Kosten</li></a>
          <a href="#"><li>Gästebuch</li></a>
          <a href="#"><li>Kontakt</li></a>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style scoped>

  .header {
    width: 100%;
  }

  .header .upper {
    height: 80px;
    background: #000;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    box-shadow: 0px 0px 20px #000;
  }

  .header .lower {
    height: 70px;
    background: #242424;
  }

  .header .nav {
    display: flex;
    flex-direction: row;
    justify-content: center;
  }

  .header .nav ul {
    display: flex;
    font-weight: 600;
  }

  .header .nav ul a {
    display: flex;
    align-content: center;
    justify-content: center;
    width: 200px;
    line-height: 35px;
  }

  
  .header .nav ul a:hover {
    background: rgb(113, 21, 11);
  }

</style>