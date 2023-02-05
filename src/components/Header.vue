<template>
  <div class="header">
    <div class="upper">
      <div class="logo">My Fangs</div>
    </div>
    <div class="lower">
      <div class="nav">
        <ul>
          <router-link to="vampirzaehne"><li>Vampirzähne</li></router-link>
          <router-link to="ueber-mich"><li>Über mich</li></router-link>
          <router-link to="referenzen"><li>Referenzen</li></router-link>
          <router-link to="angebot"><li>Angebot & Kosten</li></router-link>
          <router-link to="gaestebuch"><li>Gästebuch</li></router-link>
          <router-link to="kontakt"><li>Kontakt</li></router-link>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style lang="scss" scoped>

  .header {
    width: 100%;
      .upper {
      height: 90px;
      background: #000;
      display: flex;
      flex-direction: row;
      justify-content: center;
      align-items: center;
      box-shadow: 0px 0px 20px #000;
    
      .logo {
        font-family: 'Babylonica', cursive;
        font-size: 64px;
      }
    }
      .lower {
      background: #242424;
      .nav {
      font-family: 'Marcellus SC', serif;
      display: flex;
      flex-direction: row;
      justify-content: center;
      letter-spacing: 2px;

        ul {
        display: flex;
        align-items: center;
        font-weight: 600;
          a {
          display: flex;
          align-content: center;
          justify-content: center;
          width: 200px;
          line-height: 35px;

            &:hover {
              background: rgb(113, 21, 11);
            }
          }
        }
      }
    }
  }

</style>