<template>
  <section id='about-area1' class='home-about-area section-gap'>
    <div class='container'>
      <div class='row'>
        <div class='col-lg-9 offset-3'>
          <h1>
            Hola, ¿cómo estás?
          </h1>
          <p>
            <span>Soy Tatiana, aprendí a preparar tortas deliciosas de la mano de mi mamá, pero por falta de imaginación siempre termino cocinando lo mismo. Cuando queremos celebrar algo especial con mis amigos ya no quieren mis pasteles y prefieren comprar algo en la repostería del supermercado. 😰</span>
          </p>
          <a class='primary-btn squire mx-auto mt-20' v-scroll-to="'#categories-area'" href='#'>Soy como Tatiana 🙈</a>
        </div>
      </div>
    </div>
    <img class='about-img left' src='../assets/img/tatiana1.png' alt=''>
  </section>
</template>

<style lang='scss' scoped>
  .about-img.left{
    left:0;
    right: unset;
  }
  .home-about-area {
    background: #eaf9fd;
  }
</style>
