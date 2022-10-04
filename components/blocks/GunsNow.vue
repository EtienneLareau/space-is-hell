<template>
    <div>
        <div class="grid-guns-a">
            <div class="card">
                <img src="~assets/images/m4a3pistol.webp" alt="" />
                <div>
                    <h3>M4A3 Pistol</h3>
                    <div class="grid-guns-info">
                        <div>
                            <div><span>Bonus = </span><span> 2</span></div>
                            <div><span>Damage = </span><span>1</span></div>
                        </div>
                        <div>
                            <div><span>Range = </span><span>Medium</span></div>
                            <div><span>Weight = </span><span>1/2</span></div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="card">
                <img src="~assets/images/357magnum.webp" alt="" />
                <div>
                    <h3>.357 Magnum</h3>
                    <div class="grid-guns-info">
                        <div>
                            <div><span>Bonus = </span><span>1</span></div>
                            <div  class="hl"><span>Damage = </span><span>2</span></div>
                        </div>
                        <div>
                            <div><span>Range = </span><span>Medium</span></div>
                            <div  class="hl"><span>Weight = </span><span>1</span></div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="card">
                <img src="~assets/images/armatmodel37a2.webp" alt="" />
                <div>
                    <h3>Armat model 37A2</h3>
                    <div class="grid-guns-info">
                        <div>
                            <div><span>Bonus = </span><span>1</span></div>
                            <div><span>Damage = </span><span>2</span></div>
                        </div>
                        <div>
                            <div><span>Range = </span><span>Medium</span></div>
                            <div><span>Weight = </span><span>1</span></div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
        vail
    </div>
</template>

<style scoped>
  img {
    width:100%;
    height:auto;
  }
h3,
p,
span {
    color: #fff;
    padding-bottom: 16px;
    font-weight: 300;
}

span {
  /* padding: 0 10px 0; */
}

h3 {
    font-weight: 400;
    padding-top:1rem;
}
.grid-guns-a,
.grid-guns-info {
    display: grid;
}

.grid-guns-a {
    grid-template-columns: 1fr 1fr 1fr;
    gap: 2rem;
    width: 90%;
    margin: 0 auto;
}

.grid-guns-info {
    grid-template-columns: 1fr 1fr;
}

.grid-guns-info > div > div {
  padding-bottom: 10px;
  padding-top: 10px;
}
.card {
    background-color: #000;
    padding: 20px 20px;
}

.hl {
  background-color: rgb(22, 22, 22);
  border-width:2px 0 2px 0;
  border-style: solid;
  border-color: rgb(46, 46, 46);
}
</style>