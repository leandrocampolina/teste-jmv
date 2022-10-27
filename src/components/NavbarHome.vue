<template>
    <div class="navbar">
      <div class="container">
        <div class="row">
          <div class="col-xl-3 col-lg-3 d-flex align-items-center">
            <a href="https://nochalks.com/">
              <img class="logo" src="https://nochalks.com/wp-content/uploads/2022/01/nochalks-logotipo.png">
            </a>
          </div>
          <div class="col-xl-9 col-lg-9 navbar-links">
            <a href="https://nochalks.com/plataforma-ead/">PLATAFORMA EAD</a>
            <a href="#news">SERVIÇOS</a>
            <a href="https://nochalks.com/blog/">BlOG</a>
            <a href="https://nochalks.com/plataforma-ead/#recursos">RECURSOS</a>
            <a href="https://nochalks.com/plataforma-ead/#seguranca">SEGURANÇA</a>
            <a href="https://nochalks.com/plataforma-ead/#planos">PLANOS</a>
            <a href="https://nochalks.com/plataforma-ead/#depoimentos">DEPOIMENTOS</a>
            <a href="https://nochalks.com/plataforma-ead/#contato">CONTATO</a>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  name: 'NavbarHome',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar {
  background-color: white;
  width: 100% !important;
  position:fixed;
  left:0;           
  top:0;
  z-index:200; 
  height:100px;
}

.logo {
  width: 100%;
  margin: 20px;
  padding-left: 30px;
}

.navbar-links {
  display: flex;
  align-content: flex-end;
  flex-wrap: wrap;
  justify-content: flex-end;
}

.navbar-links a{
  padding: 10px;
  text-decoration: none !important;
  font-size: 11px;
}

</style>
