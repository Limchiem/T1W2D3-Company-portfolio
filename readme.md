# Coder Academy - Portfolio #

## Overview ##

This is a portfolio website for displaying the services that coder academy provides. This is in development phase and we will keep on adding those features in this readme that we add on the website.

## Component ##

### Header ###

Header has logo and name of the company along with nav bar.

``` html
    <header>
        <div class="logo">
            <a href="./index.html">
                <img src="./images/logo.png" alt="Coder Academy Logo">
            </a>
            <p class="name">
                <span class="coder-text">Coder</span>
                <span class="academy-text">Academy</span>
            </p>
        </div>
        <nav class="nav-items">
            <a href="./pages/about.html">About</a>
            <a href="./pages/services.html">Services</a>
            <a href="./pages/contact.html">Contact</a>
        </nav>
    </header>
```

### Footer

Footer has social media links, contact and address.

``` html
    <footer>
        <div class="social-media">
            <a href="">
                <i class="fa-brands fa-github"></i>
            </a>
            <a href="">
                <i class="fa-brands fa-linkedin"></i>
            </a>
            <a href="">
                <i class="fa-brands fa-instagram"></i>
            </a>
        </div>
        <div class="info">
            <p>Contact: 04xx xxx xxx</p>
            <p>Address: 123 Fake street</p>
        </div>
    </footer>
```

## Pages

### Home

Home page currently displays some lorem ipsum text.

``` html
<main>
        <section>
            <div class="jumbotron">
                <img src="./images/jumobtron.jpg" alt="picture of server">
            </div>
            <div class="details">
                <p>
                    Coder Academy is Lorem ipsum.
                </p>
            </div>
        </section>
    </main>
```