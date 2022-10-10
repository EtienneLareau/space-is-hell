<template>
    <div>
        <div class="grid-guns-a">
            <div class="card">
                <img src="~assets/images/m4a3pistol.webp" alt="" />
                <div>
                    <h3>M4A3 Pistol</h3>
                    <div class="grid-guns-info hl">
                        <div>
                            <div><span>Bonus = </span><span> 2</span></div>
                            <div><span>Damage = </span><span>1</span></div>
                        </div>
                        <div>
                            <div><span>Range = </span><span>Medium</span></div>
                            <div><span>Weight = </span><span>1/2</span></div>
                            <div><span>Cost = </span><span>$500</span></div>
                        </div>
                    </div>
                    <div>
                        <p>
                            This inexpensive 9mm pistol is the standard sidearm
                            of the USCMC. You should always have a backup for
                            your backup, and this pistol might as well be it.
                        </p>
                    </div>
                </div>
            </div>
            <div class="card">
                <img src="~assets/images/357magnum.webp" alt="" />
                <div>
                    <h3>.357 Magnum</h3>
                    <div class="grid-guns-info hl">
                        <div>
                            <div><span>Bonus = </span><span>1</span></div>
                            <div class="">
                                <span>Damage = </span><span>2</span>
                            </div>
                        </div>
                        <div>
                            <div><span>Range = </span><span>Medium</span></div>
                            <div class="">
                                <span>Weight = </span><span>1</span>
                            </div>
                            <div><span>Cost = </span><span>$500</span></div>
                        </div>
                    </div>
                    <div>
                        <p>
                            A classic high caliber revolver, equally popular
                            amongst both Frontier Marshals and lowlifes.
                        </p>
                    </div>
                </div>
            </div>
            <div class="card">
                <img src="~assets/images/armatmodel37a2.webp" alt="" />
                <div>
                    <h3>Armat model 37A2</h3>
                    <div class="grid-guns-info hl">
                        <div>
                            <div><span>Bonus = </span><span>1</span></div>
                            <div><span>Damage = </span><span>2</span></div>
                        </div>
                        <div>
                            <div><span>Range = </span><span>Medium</span></div>
                            <div><span>Weight = </span><span>1</span></div>
                            <div><span>Cost = </span><span>$500</span></div>
                        </div>
                    </div>
                    <div>
                        <p>
                            A classic pump-action combat shotgun, the M37A2 is
                            an optional weapon in use by the USCMC. Reliable and
                            direct, the '37 is the gun you want to keep handy
                            for close encounters.
                        </p>
                    </div>
                </div>
            </div>
            <div class="card">
                <img src="~assets/images/bodyarmor.webp" alt="" />
                <div>
                    <h3>M3 Personal Armor</h3>
                    <div class="grid-guns-info hl">
                        <div>
                            <div>
                                <span>Armor Rating = </span><span>6</span>
                            </div>
                            <div><span>Air Supply = </span><span>0</span></div>
                        </div>
                        <div>
                            <div><span>Weight = </span><span>1</span></div>
                            <div><span>Cost = </span><span>$1200</span></div>
                        </div>
                    </div>

                    <div>
                        <p>
                            Standard issue for the USCMC, the M3 consists of a
                            rigid armor padded vest, a flexible ballistic pad
                            that covers the abdomen, and clamshell greaves on
                            the lower legs. The armor protects against edged
                            weapons and glancing blows from high powered
                            ammunition. It has a built-in comm unit and Personal
                            Data Transmitter, combat webbing straps to connect a
                            variety of equipment, and contact points which
                            monitor the wearer’s vitals and transmit them to a
                            tactical monitoring station. Armor Rating 6.
                        </p>
                        <p>Comment: Built-in comm unit</p>
                    </div>
                </div>
            </div>
        </div>
        
    </div>
</template>

<style scoped>
img {
    width: 100%;
    height: auto;
}
h3,
p,
span {
    color: #fff;
    padding-bottom: 16px;
    font-weight: 400;
}

span {
    /* padding: 0 10px 0; */
}

h3 {
    font-weight: 400;
    padding-top: 1rem;
    font-size: 1.4rem;
}
p {
    line-height: 1.6;
    padding: 20px 0;
}

.grid-guns-a,
.grid-guns-info {
    display: grid;
}

.grid-guns-a {
    grid-template-columns: 1fr 1fr 1fr;
    gap: 2rem;
    width: 90%;
    max-width:1050px;
    margin: 0 auto;
    padding-top:150px;
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
    border-width: 2px 0 2px 0;
    border-style: solid;
    border-color: rgb(46, 46, 46);
    padding: 10px 12px;
}

@media only screen and (max-width: 620px) {


h3 {
    font-weight: 500;
    padding-top: 1rem;
    font-size: 1.15rem;
    padding-left:12px;
}
p {
    line-height: 1.5;
    padding: 20px 12px;
    font-size: 0.95rem;
}
span {
  font-size: 0.95rem;
  padding-bottom:12px;
}

.grid-guns-a {
    grid-template-columns: 1fr;
    gap: 2rem;
    width: 95%;
    margin: 0 auto;
}


.grid-guns-info {
    grid-template-columns: 1fr;
}


.card {
    background-color: #000;
    padding: 5px 5px;
}

}
</style>