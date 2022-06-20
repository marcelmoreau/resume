<script setup>
    import HelloWorld from "./components/HelloWorld.vue";
    import TheWelcome from "./components/TheWelcome.vue";
</script>

<template>
    <div class="masthead">
        <div class="container">
            <div class="grid masthead__grid">
                <h1 class="masthead__logo">
                    Marcel Moreau
                </h1>
                <div class="masthead__byline">
                    Front-end engineer in Maine, USA
                </div>
            </div>
        </div>
    </div>

    <div class="torso">

        <!-- Experience -->
        <section class="section">
            <div class="container">
                <div class="grid section__grid">
                    <div class="section__rail">
                        <h2 class="section__heading">
                            <span class="section__headingAsset">
                                <svg class="section__headingIcon" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M7.76471 1.55882C7.91176 1.48039 8.08824 1.48039 8.23529 1.55882L15.7353 5.55882C15.8982 5.64572 16 5.81534 16 6C16 6.18466 15.8982 6.35428 15.7353 6.44118L8.23529 10.4412C8.08824 10.5196 7.91176 10.5196 7.76471 10.4412L0.264706 6.44118C0.101774 6.35428 0 6.18466 0 6C0 5.81534 0.101774 5.64572 0.264706 5.55882L7.76471 1.55882Z" fill="currentColor"/><path d="M2.125 8.56667L0.264706 9.55882C0.101774 9.64572 0 9.81534 0 10C0 10.1847 0.101774 10.3543 0.264706 10.4412L7.76471 14.4412C7.91176 14.5196 8.08824 14.5196 8.23529 14.4412L15.7353 10.4412C15.8982 10.3543 16 10.1847 16 10C16 9.81534 15.8982 9.64572 15.7353 9.55882L13.875 8.56667L8.70588 11.3235C8.26471 11.5588 7.73529 11.5588 7.29412 11.3235L2.125 8.56667Z" fill="currentColor"/>
                                </svg>
                            </span>
                            <span class="section__headingLabel">Experience</span>
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
                                        Lead front-end engineer responsible for evergreen project build-outs. Also versed in user experience exploration exercises. Exposure to the full web lifecycle, from business development, to creative to development.
                                    </p>

                                    <div class="figures">
                                        <div class="grid figures__grid">
                                            <div class="figures__item">
                                                <div class="figures__asset">
                                                    <img class="figures__image" src="https://dummyimage.com/500x344.png" alt=""/>
                                                </div>
                                                <div class="heading figures__heading">
                                                    <a href="">Security Scorecard</a>
                                                </div>
                                                <div class="figures__copy">
                                                     Front-end engineering (Craft CMS)
                                                </div>
                                            </div>
                                            <div class="figures__item">
                                                <div class="figures__asset">
                                                    <img class="figures__image" src="/img/experience-handbook.png" alt=""/>
                                                </div>
                                                <div class="heading figures__heading">
                                                    <a href="">Handbook</a>
                                                </div>
                                                <div class="figures__copy">
                                                     Front-end engineering (Hugo)
                                                </div>
                                            </div>
                                            <div class="figures__item">
                                                <div class="figures__asset">
                                                    <img class="figures__image" src="https://dummyimage.com/500x344.png" alt=""/>
                                                </div>
                                                <div class="heading figures__heading">
                                                    <a href="">BAO</a>
                                                </div>
                                                <div class="figures__copy">
                                                    Front-end engineering (Craft CMS)
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
                            <span class="section__headingAsset">
                                <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M12.8536 0.146447C12.6583 -0.0488155 12.3417 -0.0488155 12.1465 0.146447L10.5 1.7929L14.2071 5.50001L15.8536 3.85355C16.0488 3.65829 16.0488 3.34171 15.8536 3.14645L12.8536 0.146447Z" fill="currentColor"/><path d="M13.5 6.20711L9.7929 2.50001L3.29291 9H3.5C3.77614 9 4 9.22386 4 9.5V10H4.5C4.77614 10 5 10.2239 5 10.5V11H5.5C5.77614 11 6 11.2239 6 11.5V12H6.5C6.77614 12 7 12.2239 7 12.5V12.7071L13.5 6.20711Z" fill="currentColor"/><path d="M6.03166 13.6755C6.01119 13.6209 6 13.5617 6 13.5V13H5.5C5.22386 13 5 12.7761 5 12.5V12H4.5C4.22386 12 4 11.7761 4 11.5V11H3.5C3.22386 11 3 10.7761 3 10.5V10H2.5C2.43827 10 2.37915 9.98881 2.32455 9.96835L2.14646 10.1464C2.09858 10.1943 2.06092 10.2514 2.03578 10.3143L0.0357762 15.3143C-0.0385071 15.5 0.00502989 15.7121 0.146461 15.8536C0.287892 15.995 0.500001 16.0385 0.68571 15.9642L5.68571 13.9642C5.74858 13.9391 5.80569 13.9014 5.85357 13.8536L6.03166 13.6755Z" fill="currentColor"/></svg>
                            </span>
                            <span class="section__headingLabel">Writing</span>
                        </h2>
                    </div>
                    <div class="section__main">
                        <div class="listing">
                            <ul class="listing__items">
                                <li class="listing__item">
                                    <a class="listing__heading" href="">Lorem ipsum dolor, sit amet consectetur adipisicing elit</a>
                                    <div class="meta">
                                        <div class="meta__item">CSS-Tricks</div>
                                        <div class="meta__item">2022</div>
                                    </div>
                                </li>
                                <li class="listing__item">
                                    <a class="listing__heading" href="">Lorem ipsum dolor, sit amet consectetur adipisicing elit</a>
                                    <div class="meta">
                                        <div class="meta__item">CSS-Tricks</div>
                                        <div class="meta__item">2022</div>
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
                            <span class="section__headingAsset">
                                <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M16 4.5C16 5.92835 15.3345 7.20128 14.2967 8.02563L13 5L15.959 3.89036C15.986 4.08972 16 4.29323 16 4.5Z" fill="currentColor"/><path d="M11.5 9C12.1528 9 12.7733 8.86096 13.3332 8.61088L12 5.5L11 3L14.8265 1.46939C14.0035 0.566554 12.8179 0 11.5 0C9.01468 0 6.99996 2.01472 6.99996 4.5C6.99996 5.06048 7.10243 5.59702 7.28965 6.09193L1.17282 11.1893C0.00599647 12.1616 -0.0740367 13.926 0.999961 15C2.07396 16.074 3.83833 15.994 4.81068 14.8271L9.90803 8.71031C10.4029 8.89753 10.9395 9 11.5 9ZM10.208 4.63868L9.61215 5.53241L10.4209 5.26283C10.5222 5.22906 10.6338 5.26338 10.6986 5.34825C10.7635 5.43313 10.7672 5.54981 10.708 5.63868L10.1121 6.53241L10.9209 6.26283L11.079 6.73717L9.57902 7.23717C9.4777 7.27094 9.36611 7.23662 9.30128 7.15175C9.23646 7.06687 9.23271 6.95019 9.29195 6.86133L9.88778 5.96759L9.07902 6.23717C8.9777 6.27094 8.86611 6.23662 8.80128 6.15175C8.73646 6.06687 8.73271 5.95019 8.79195 5.86132L9.38778 4.96759L8.57902 5.23717L8.4209 4.76283L9.9209 4.26283C10.0222 4.22906 10.1338 4.26338 10.1986 4.34825C10.2635 4.43313 10.2672 4.54981 10.208 4.63868ZM2.99996 14C2.44768 14 1.99996 13.5523 1.99996 13C1.99996 12.4477 2.44768 12 2.99996 12C3.55225 12 3.99996 12.4477 3.99996 13C3.99996 13.5523 3.55225 14 2.99996 14Z" fill="currentColor"/></svg>
                            </span>
                            <span class="section__headingLabel">Projects</span>
                        </h2>
                    </div>
                    <div class="section__main">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Facilis esse eligendi ut velit, dolorem deserunt minus architecto perferendis!
                    </div>
                </div>
            </div>
        </section>
        <!-- <HelloWorld msg="Marcel, you did it!" /> -->
    </div>


    <main>
        <!-- <TheWelcome /> -->





    </main>

    <footer class="footer">
        <div class="container">
            <div class="grid footer__grid">
                <div class="footer__rail">
                    <img src="https://dummyimage.com/181x163.png?text=fpo" alt=""/>
                </div>
                <div class="footer__main">
                    <h5>
                        Hit my line
                    </h5>
                    <div class="footer__wrapper">
                        <a href="">Codepen</a>
                        <a href="">Twitter</a>
                        <a href="">LinkedIn</a>
                        <a href="">Email</a>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>
