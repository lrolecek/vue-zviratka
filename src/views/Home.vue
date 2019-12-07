<template>
  <div class="home">

    <h1>Zvířátka v ZOO</h1>

    <div class="container">

      <!-- zacatek zvirata -->
      <div class="zvirata" id="zvirata">

        <div class="zvire">
          <div class="zvire__foto">
            <img src="images/slon.jpg" alt="Slon africký">
          </div>
          <div class="zvire__popis">
            <div class="zvire__nazev">Slon africký</div>
            <div class="zvire__latinsky">Slonus africanus</div>
          </div>
        </div>

      </div>
      <!-- konec zvirata -->


      <!-- zacatek detail -->
      <div class="detail">

        <div class="detail__obsah" id="detail">

          <div class="detail__hlavicka">
            <img class="detail__foto" src="images/slon.jpg" alt="Slon africký">
            <div class="detail__titulek">
              <h2 class="detail__nazev"><span id="nazev">Slon africký</span></h2>
              <div class="detail__latinsky"><span id="latinsky">Slonus africanus arabicus</span></div>
            </div>
          </div>

          <div class="detail__info">
            <p class="detail__popis" id="popis">Typickými znaky největších suchozemských savců jsou kly (přeměněné horní řezáky) a pohyblivý chobot, který vznikl srůstem a prodloužením horního pysku a nosu. Velikosti těla odpovídá i množství potravy, které kolísá od 300 do 450 kg. Samec a samice se setkávají pouze v období páření. Zatímco samci vytvářejí mládenecké skupiny nebo žijí samotářsky, samice společně s mláďaty vytvářejí rodinné klany čítající 20 až 30 zvířat. Mládě přichází na svět po březosti 22 měsíců, měří na výšku 1 m a váží 100 kg. Mateřské mléko pije tlamou, chobot se naučí používat teprve ve 3 měsících.</p>

            <div class="detail__udaje">
              <div class="detail__udaj">
                <h3>Domovina</h3>
                <p id="domovina">subsaharská Afrika</p>
              </div>
              <div class="detail__udaj">
                <h3>Biotop</h3>
                <p id="biotop">savany, polopouště, pouště</p>
              </div>
              <div class="detail__udaj">
                <h3>Potrava</h3>
                <p id="potrava">tráva, listí, větve</p>
              </div>
              <div class="detail__udaj">
                <h3>Velikost</h3>
                <p id="velikost">hmotnost 2,7-6,3 t; délka těla 6-7,5 m</p>
              </div>
            </div>

          </div>

        </div>
      </div>
      <!-- konec detail -->

    </div>

  </div>
</template>

<script>

export default {
  name: 'home',
}
</script>
