<template>
    <div class="back-img">
        <div class="fade">
          <img src="~assets/images/city.jpg" alt="">
            <div class="flexing-center">
             
                <p>
                    Space is vast, dark, and not your friend. Gamma rays and
                    neutrino bursts erupt from dying stars to cook you alive,
                    black holes tear you apart, and the void itself boils your
                    blood and seizes your brain. Try to scream and no one can
                    hear you—hold your breath and you rupture your lungs.
                </p>
                <p>
                    Space isn't as empty as you’d think, either—its frontiers
                    are ever expanding. Rival governments wage a cold war of
                    aggression while greedy corporations vie for valuable
                    resources. Colonists reach for the stars and gamble with
                    their lives—each new world tamed is either feast or famine.
                    And there are things lurking in the shadows of every
                    asteroid—things strange and different and deadly.
                </p>
            </div>
        </div>
    </div>
</template>

<style scoped>
  img {
    width:100%;
    height:auto;
    margin-bottom:30px;
    display:none;
  }
.back-img {
    background: url('~assets/images/city.jpg') no-repeat center center;
    background-size: cover;
    width: 100%;
    padding-top: 200px;
}


@media only screen and (max-width: 650px) {
  img {
    display: block;
  }
  .back-img {
    /* background: none; */
    /* background-size: cover; */
    width: 100%;
    padding-top: 0px;
}

.fade {
  background: rgba(0, 0, 0, 0.852);

}
}
</style>