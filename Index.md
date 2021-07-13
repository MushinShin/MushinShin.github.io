<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Deploy your websites in less than 3 years">
    <meta property="og:title" content="Facufy...">
    <meta property="og:description" content="Facufy description...">
    <meta property="og:type" content="website">
    <meta property="og:image" content="http://...">
    <meta property="og:url" content="https://moshified.com">
    <title>Facufy - Go Online for Just a Pete</title>
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="CSS/normalize.css">
    <link rel="stylesheet" href="CSS/style.css">
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
</head>
<body>
    <header>
        <nav class="nav collapsible">
            <a href="/"><img src="images/logo.svg" alt=""></a>
            <svg class="icon icon--white nav__toggler">
                <use xlink:href="images/sprite.svg#menu"></use>
            </svg>
            <ul class="list nav__list collapsible__content">
                <li class="nav__item"><a href="#">Hosting</a></li>
                <li class="nav__item"><a href="#">VPS</a></li>
                <li class="nav__item"><a href="#">Domain</a></li>
                <li class="nav__item"><a href="#">Pricing</a></li>
            </ul>
        </nav>
    </header>
    <section class="block block--dark block--skewed-left">
        <div class="container grid grid--1x2">
            <header class="block__header hero__content" data-aos="fade-down">
                <h1 class="block__heading">Cloud Hosting for Pros</h1>
                <p class="hero__tagline">Deploy your websites in less than 60 seconds</p>
                <a href="" class="butto butto--accent butto--stretched">Get Started</a>
            </header>
            <img class="hero__image" src="images/banner.png" alt="" data-aos="fade-up">
        </div>
    </section>
    <section class="block container block-domain" data-aos="zoom-in">
        <header class="block__header">
            <h2>Starting at $9 per month</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis
                 accusantium dolor, iusto delectus quibusdam nostrum.
            </p>
        </header>
        <div class="input-group">
            <input type="text" class="input" placeholder="Enter Domain here...">
            <button class="butto butto--accent"><svg class="icon icon--white">
                <use xlink:href="images/sprite.svg#search"></use>
            </svg>Search</button>
        </div>
        <ul class="list block-domain__prices">
            <li><span class="badge badge--secondary">.com 9$</span></li>
            <li>.sg 9$</li>
            <li>.space $11</li>
            <li>.info $14</li>
            <li>.net $10</li>
            <li>.xyz $10</li>
        </ul>
    </section>
    <section class="block container block-plans" data-aos="zoom-in">
        <div class="grid grid--1x3">
                <div class="plan">
                    <div class="card card--secondary">
                        <header class="card__header">
                            <h3 class="plan__name">Entry</h3>
                            <span class="plan__price">$14</span>
                            <span class="plan__billing-cycle">/Month</span>
                            <span class="badge badge--secondary badge--small">10% OFF</span>
                            <span class="plan__description">Easy start on the cloud</span>
                        </header>
                        <div class="card__body">
                            <ul class="list list--tick">
                                <li class="list__item">Unlimited Websites</li>
                                <li class="list__item">Unlimited Bandwidth</li>
                                <li class="list__item">100 GB SSD Storage</li>
                                <li class="list__item">3 GB RAM</li>
                            </ul>
                            <button class="butto butto--outline butto--block">Buy Now</button>
                        </div>
                    </div>
                </div>
                <div class="plan plan--popular">
                    <div class="card card--primary">
                        <header class="card__header">
                            <h3 class="plan__name">Entry</h3>
                            <span class="plan__price">$14</span>
                            <span class="plan__billing-cycle">/Month</span>
                            <span class="badge badge--primary badge--small">10% OFF</span>
                            <span class="plan__description">Easy start on the cloud</span>
                        </header>
                        <div class="card__body">
                            <ul class="list list--tick">
                                <li class="list__item">Unlimited Websites</li>
                                <li class="list__item">Unlimited Bandwidth</li>
                                <li class="list__item">100 GB SSD Storage</li>
                                <li class="list__item">3 GB RAM</li>
                            </ul>
                            <button class="butto butto--outline butto--block">Buy Now</button>
                        </div>
                    </div>
                </div>
                <div class="plan">
                    <div class="card card--secondary">
                        <header class="card__header">
                            <h3 class="plan__name">Entry</h3>
                            <span class="plan__price">$14</span>
                            <span class="plan__billing-cycle">/Month</span>
                            <span class="badge badge--secondary badge--small">10% OFF</span>
                            <span class="plan__description">Easy start on the cloud</span>
                        </header>
                        <div class="card__body">
                            <ul class="list list--tick">
                                <li class="list__item">Unlimited Websites</li>
                                <li class="list__item">Unlimited Bandwidth</li>
                                <li class="list__item">100 GB SSD Storage</li>
                                <li class="list__item">3 GB RAM</li>
                            </ul>
                            <button class="butto butto--outline butto--block">Buy Now</button>
            
                        </div>
                    </div>
                </div>
        </div>
    </section>
    <section class="block container">
        <header class="block__header">
            <h2>Host on the Cloud to keep Growing</h2>
            <p>Lorem ipsum dolor sit amet.</p>
        </header>
        <article class="grid grid--1x2 feature">
            <div class="feature__content" data-aos="fade-right">
                <span class="icon-container">
                    <svg class="icon icon--primary">
                        <use xlink:href="images/sprite.svg#easy"></use>
                    </svg>
                </span>
                <h3 class="feature__heading">Super Easy to Use</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur
                     adipisicing elit. Quaerat, amet?
                </p>
                <a href="#" class="link-arrow">Learn More</a>
            </div>
            <img class="feature__image" src="images/easy.jpg" alt="" data-aos="fade-left">
        </article>
    </section>
    <section class="block container">
        <article class="grid grid--1x2 feature">
            <div class="feature__content" data-aos="fade-left">
                <span class="icon-container">
                    <svg class="icon icon--primary">
                        <use xlink:href="images/sprite.svg#easy"></use>
                    </svg>
                </span>
                <h3 class="feature__heading" data-aos="zoom-in-left">Super Easy to Use</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur
                     adipisicing elit. Quaerat, amet?
                </p>
                <a href="#" class="link-arrow">Learn More</a>
            </div>
            <img class="feature__image" src="images/wordpress.jpg" alt="" data-aos="slide-left">
        </article>
    </section>
    <section class="block container">
        <article class="grid grid--1x2 feature">
            <div class="feature__content" data-aos="flip-right">
                <span class="icon-container">
                    <svg class="icon icon--primary">
                        <use xlink:href="images/sprite.svg#easy"></use>
                    </svg>
                </span>
                <h3 class="feature__heading">Super Easy to Use</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur
                     adipisicing elit. Quaerat, amet?
                </p>
                <a href="#" class="link-arrow">Learn More</a>
            </div>
            <img class="feature__image" src="images/fast.jpg" alt="" data-aos="flip-left">
        </article>
    </section>
    <section class="block block--dark block--skewed-right block-showcase">
        <header class="block__header">
            <h2>User Friendly Control Panel</h2>
        </header>
        <div class="container grid grid--1x2">
            <img class="block-showcase__image" src="images/ipadsmall.png" alt="" data-aos="fade-right">
            <ul class="list" data-aos="fade-up">
                <li>
                    <div class="media">
                        <div class="media__image">
                            <svg class="icon icon--primary">
                                <use xlink:href="images/sprite.svg#snap"></use>
                            </svg>
                        </div>
                        <div class="media__body">
                            <h3 class="media__title">Easy Start & Managed Updates</h3>
                            <p>
                                Lorem, ipsum dolor sit amet consectetur
                                 adipisicing elit. Illum soluta doloribus
                                  vel deserunt? Consequatur, nam. Placeat
                                   quaerat id velit provident.
                            </p>
                        </div>
                    </div> 
                </li>
                <li>
                    <div class="media">
                        <div class="media__image">
                            <svg class="icon icon--primary">
                                <use xlink:href="images/sprite.svg#snap"></use>
                            </svg>
                        </div>
                        <div class="media__body">
                            <h3 class="media__title">Stagin, GIT & WP-CLI</h3>
                            <p>
                                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Illum soluta doloribus vel deserunt? Consequatur, nam. Placeat quaerat id velit provident.
                            </p>
                        </div>
                    </div>
                </li>
                <li>
                    <div class="media">
                        <div class="media__image">
                            <svg class="icon icon--primary">
                                <use xlink:href="images/sprite.svg#snap"></use>
                            </svg>
                        </div>
                        <div class="media__body">
                            <h3 class="media__title">Dynamic Cachin & More</h3>
                            <p>
                                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Illum soluta doloribus vel deserunt? Consequatur, nam. Placeat quaerat id velit provident.
                            </p>
                        </div>
                    </div>
                </li>
            </ul>
        </div>
    </section>
    <section class="block" data-aos="zoom-in">
        <header class="block__header">
            <h2>What our costumers are saying</h2>
            <p>
                Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                Rerum dignissimos ratione ut placeat consequuntur harum
                doloribus beatae similique eos nesciunt. Ullam, necessitatibus
                a. Aut, impedit sit nisi
                perferendis sapiente dolore.
            </p>
        </header>
        <div class="container">
                <div class="card testimonial">
                    <div class="grid grid--1x2">
                        <div class="testimonial__image">
                            <img src="images/testimonial.jpg" 
                            alt="Happy Smiling costumer">
                            <span class="icon-container icon-container--accent">
                                <svg class="icon icon--white icon--small">
                                    <use xlink:href="images/sprite.svg#quotes"></use>
                                </svg>
                            </span>
                        </div>
                        <blockquote class="quote">
                            <p class="quote__text"> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quos, porro!</p>
                            <footer>
                                <div class="media">
                                    <div class="media__image">
                                        <svg class="icon icon--primary quote__line">
                                            <use xlink:href="images/sprite.svg#line"></use>
                                        </svg>
                                    </div>
                                    <div class="media__body">
                                        <h3 class="media__title quote__author">John Smith</h3>
                                        <p class="quote__company">
                                            ABC Company
                                        </p>
                                    </div>
                                </div>
                            </footer>
                        </blockquote>
                    </div>
                </div>
        </div>
    </section>
    <div class="callout callout--primary">
        <div class="grid grid--1x2">
            <div class="callout__content">
                <h2 class="callout__heading">Ready to Get Started?</h2>
                <p>Lorem ipsum dolor sit amet 
                    consectetur adipisicing elit. Et maiores perspiciatis 
                    saepe illo nostrum ullam nam vitae quibusdam perferendis!
                </p>
            </div>
            <a href="#" class="butto butto--secondary butto--stretched">Get Started</a>
        </div>
    </div>
    <footer class="block block--dark footer">
        <div class="container grid footer__sections">
            <section class="collapsible collapsible--expanded footer__section">
                <div class="collapsible__header">
                    <h2 class="collapsible__heading footer__heading">Products</h2>
                        <svg class="icon icon--white collapsible__chevron">
                            <use xlink:href="images/sprite.svg#chevron"></use>
                        </svg>
                </div>
                <div class="collapsible__content">
                    <ul class="list footer__links">
                        <li class="footer__link">
                            <a href="#">Website Hosting</a>
                        </li>
                        <li>
                            <a href="#">Free Automated</a>
                        </li>
                        <li class="footer__link">
                            <a href="#">Wordpress</a>
                        </li>
                        <li class="footer__link">
                            <a href="#">Migrations</a>
                        </li>
                    </ul>
                </div>
            </section>
            <section class="collapsible  footer__section">
                <div class="collapsible__header">
                    <h2 class="collapsible__heading footer__heading">Company</h2>
                        <svg class="icon icon--white collapsible__chevron">
                            <use xlink:href="images/sprite.svg#chevron"></use>
                        </svg>
                </div>
                <div class="collapsible__content">
                    <ul class="list footer__links">
                        <li class="footer__link">
                            <a href="#">About</a>
                        </li>
                        <li>
                            <a href="#">Affiliates</a>
                        </li>
                        <li class="footer__link">
                            <a href="#">Blog</a>
                        </li>
                    </ul>
                </div>
            </section>
            <section class="collapsible  footer__section">
                <div class="collapsible__header">
                    <h2 class="collapsible__heading footer__heading">Support</h2>
                        <svg class="icon icon--white collapsible__chevron">
                            <use xlink:href="images/sprite.svg#chevron"></use>
                        </svg>
                </div>
                <div class="collapsible__content">
                    <ul class="list footer__links">
                        <li class="footer__link">
                            <a href="#">Contact</a>
                        </li>
                        <li>
                            <a href="#">Knowledge Base</a>
                        </li>
                        <li class="footer__link">
                            <a href="#">FAQ</a>
                        </li>
                    </ul>
                </div>
            </section>
            <section class="collapsible  footer__section">
                <div class="collapsible__header">
                    <h2 class="collapsible__heading footer__heading">Domains</h2>
                        <svg class="icon icon--white collapsible__chevron">
                            <use xlink:href="images/sprite.svg#chevron"></use>
                        </svg>
                </div>
                <div class="collapsible__content">
                    <ul class="list footer__links">
                        <li class="footer__link">
                            <a href="#">Domain Checker</a>
                        </li>
                        <li>
                            <a href="#">Domain Transfer</a>
                        </li>
                        <li class="footer__link">
                            <a href="#">Free Domain</a>
                        </li>
                        
                    </ul>
                </div>
            </section>
            <div class="footer__brand">
                <img src="images/logo.svg" alt="">
                <p class="footer__copyright">Copyright 2020 Mosh Hamedani</p>
            </div>
        </div>
    </footer>
    <script src="js/main.js"></script>
    <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
    <script>
      AOS.init();
    </script>
</body>
</html>
