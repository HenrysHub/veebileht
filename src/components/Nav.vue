<template>
  <div class="nav_wrapper">
    <nav class="menu">
                    <a href="#kool">Kool</a>
                    <a href="#suhted">Suhted</a>
                    <a href="#narkootikumid">Narkootikumid</a>
                    <a href="#vaimnetervis">Vaimne tervis</a>
                    <a href="#soltuvus">Sõltuvus</a>
                    <a href="#vanematele">Vanematele</a>
                </nav>
  </div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.menu{
  display: flex;
  justify-content:space-between;
  width: 700px;
}

.menu a {
  color: #524549;
  font-family: Gothic A1;
  text-align: center;
  text-decoration: none;
  font-size: 17px;
}

.menu a:hover {
  color: black;
}

.nav_wrapper {
  display: flex;
  justify-content:flex-end;
  position: relative;
  z-index: 10;
}
</style>
