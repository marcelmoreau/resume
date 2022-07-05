<script setup>
import TheMasthead from "./components/TheMasthead.vue";
import SectionHeading from "./components/SectionHeading.vue";
import IconBase from "./components/icons/IconBase.vue";
import IconLayers from "./components/icons/IconLayers.vue";
import IconPencil from "./components/icons/IconPencil.vue";
import IconWrench from "./components/icons/IconWrench.vue";
</script>

<template>
    <TheMasthead />
    <div class="torso">
        <!-- Experience -->
        <section class="section">
            <div class="container">
                <div class="grid section__grid">
                    <div class="section__rail">
                        <h2 class="section__heading">
                            <SectionHeading label="Experience">
                                <template #icon>
                                    <IconBase>
                                        <IconLayers />
                                    </IconBase>
                                </template>
                            </SectionHeading>
                        </h2>
                    </div>
                    <div class="section__main">

                        <div class="listing">
                            <ul class="listing__items">
                                <li class="listing__item">
                                    <h3 class="heading listing__heading" href="">Lead front-end engineer</h3>
                                    <div class="meta">
                                        <div class="meta__item">Imarc.com</div>
                                    </div>
                                    <p class="listing__intro">
                                        Lead front-end engineer responsible for evergreen project build-outs. Also versed in user experience exploration exercises. Familiar with the entire web lifecycle, from creative to deployment.
                                    </p>

                                    <div class="figures">
                                        <div class="grid figures__grid">
                                            <div class="figures__item">
                                                <div class="figures__asset" href="https://securityscorecard.com">
                                                    <img class="figures__image" src="/img/experience-ssc.png" alt=""/>
                                                </div>
                                                <div class="heading figures__heading">
                                                    <a href="https://securityscorecard.com">Security Scorecard</a>
                                                </div>
                                                <div class="figures__copy">
                                                    CSS, Vue.js, Craft CMS
                                                </div>
                                            </div>
                                            <div class="figures__item">
                                                <div class="figures__asset" href="https://handbook.imarc.com">
                                                    <img class="figures__image" src="/img/experience-handbook.png" alt="">
                                                </div>
                                                <div class="heading figures__heading">
                                                    <a href="https://handbook.imarc.com">Handbook</a>
                                                </div>
                                                <div class="figures__copy">
                                                    CSS, Jekyll, GreenSock
                                                </div>
                                            </div>
                                            <div class="figures__item">
                                                <div class="figures__asset" href="https://baoinc.com">
                                                    <img class="figures__image" src="/img/experience-bao.png" alt=""/>
                                                </div>
                                                <div class="heading figures__heading">
                                                    <a href="https://baoinc.com">BAO</a>
                                                </div>
                                                <div class="figures__copy">
                                                    CSS, Vue.js, Craft CMS
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Writing -->
        <section class="section">
            <div class="container">
                <div class="grid section__grid">
                    <div class="section__rail">
                        <h2 class="section__heading">
                            <SectionHeading label="Writing">
                                <template #icon>
                                    <IconBase>
                                        <IconPencil />
                                    </IconBase>
                                </template>
                            </SectionHeading>
                        </h2>
                    </div>
                    <div class="section__main">
                        <div class="listing">
                            <ul class="listing__items">
                                <li class="listing__item">
                                    <a class="listing__heading" href="https://css-tricks.com/improving-icons-for-ui-elements-with-typographic-alignment-and-scale/">Improving icons for UI elements with typographic alignment and scale</a>
                                    <div class="meta">
                                        <div class="meta__item">CSS-Tricks</div>
                                        <div class="meta__item">2022</div>
                                    </div>
                                </li>
                                <li class="listing__item">
                                    <a class="listing__heading" href="https://www.smashingmagazine.com/2021/09/reducing-need-pseudo-elements/">Reducing the need for pseudo-elements</a>
                                    <div class="meta">
                                        <div class="meta__item">Smashing Magazine</div>
                                        <div class="meta__item">2021</div>
                                    </div>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Projects -->
        <section class="section">
            <div class="container">
                <div class="grid section__grid">
                    <div class="section__rail">
                        <h2 class="section__heading">
                            <SectionHeading label="Projects">
                                <template #icon>
                                    <IconBase>
                                        <IconWrench />
                                    </IconBase>
                                </template>
                            </SectionHeading>
                        </h2>
                    </div>
                    <div class="section__main">
                        <div class="listing">
                            <ul class="listing__items">
                                <li class="listing__item">
                                    <a class="listing__heading" href="https://codepen.io/marcelmoreau/pen/OJONxeg">Scalable list icons</a>
                                    <div class="meta">
                                        <div class="meta__item">Codepen</div>
                                    </div>
                                </li>
                                <li class="listing__item">
                                    <a class="listing__heading" href="https://codepen.io/marcelmoreau/pen/eYpGKxg">Linear-gradient faux columns</a>
                                    <div class="meta">
                                        <div class="meta__item">Codepen</div>
                                    </div>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>

    <footer class="footer">
        <div class="container">
            <div class="grid footer__grid">
                <div class="footer__rail">
                    <img src="/img/marcel.jpg" alt="">
                </div>
                <div class="footer__main">
                    <h4 class="footer__heading">
                        Find me
                    </h4>
                    <div class="footer__links">
                        <a class="footer__link" href="https://codepen.io/marcelmoreau">Codepen</a>
                        <a class="footer__link" href="https://twitter.com/displaymarcel">Twitter</a>
                        <a class="footer__link" href="https://www.linkedin.com/in/marcelmoreau/">LinkedIn</a>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>
