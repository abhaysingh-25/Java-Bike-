# Java-Bike-
<!DOCTYPE html>
<html lang="en">

<head>
    <!--<meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />-->
    <link href="https://cdn.jsdelivr.net/npm/remixicon@3.4.0/fonts/remixicon.css" rel="stylesheet" />
    <link rel="stylesheet" href="landing.css" />
    <script src="serviece.js"></script>
    <title>Web Design Mastery | JAWA</title>
</head>

<body>
    <nav>
        <div class="nav__logo">
            <img src="logo-white.png" alt="logo" />
        </div>
        <ul class="nav__links">
            <li class="link"><a href="#">SERVICES</a></li>
            <li class="link"><a href="#">STORES</a></li>
            <li class="link"><a href="contactus.html">CONTACT US</a></li>
        </ul>
    </nav>
    <header class="section__container header__container">
        <img src="header.jpg" alt="header" />
    </header>

    <section class="section__container story__container">
        <h2 class="section__header">01 THE PERAK STORY</h2>
        

        
        <div class="evolution__grid">
            <div class="evolution__content">
                
                <p>
                    The Jawa Perak is a powerful and iconic motorcycle that traces its roots
                    back to the 1940s when the original Jawa brand was established in
                    Czechoslovakia. With a rich heritage of craftsmanship and innovation,
                    Jawa motorcycles quickly gained recognition for their exceptional
                    performance, reliability, and distinctive design.
                </p>
            </div>
            <div class="evolution__image">
                <img src="gallery-6.jpg" alt="evolution" />
            </div>
        </div>





    </section>

    <section class="section__container evolution__container">
        <h2 class="section__header">02 EVOLUTION OF JAWA PERAK</h2>
        <div class="evolution__grid">
            <div class="evolution__image">
                <img src="evolution.jpg" alt="evolution" />
            </div>
            <div class="evolution__content">
                <div class="evolution__nav">
                    <a href="#" class="active">1946</a>
                    <a href="#">2005</a>
                    <a href="#">2019</a>
                    <a href="#">2023</a>
                </div>
                <p>
                    Whether you are a seasoned rider or a motorcycle enthusiast looking
                    for a distinctive and powerful machine, the Jawa Perak offers a
                    captivating story and an unparalleled riding experience that will
                    leave an indelible mark on your journey.
                </p>
            </div>
        </div>
    </section>

    <section class="feature">
        <div class="section__container feature__container">
            <div class="feature__image">
                <img src="features.jpg" alt="feature" />
            </div>
            <div class="feature__content">
                <h2 class="section__header">03 FEATURES</h2>
                <ul>
                    <li>
                        SINGLE CYLINDER, FOUR STROKE, LIQUID COOLED, SI ENGINE, DOHC BSVVI
                        COMPLIANT
                    </li>
                    <li>CONSTANT MESH 6 SPPEED</li>
                    <li>MONO SHOCK ABSORBER, 7 STEP ADJUSTABLE</li>
                    <li>DISC WITH FLOATING CALIPER AND ABS</li>
                    <li>DOUBLE CRADLE TUBULAR FRAME</li>
                </ul>
            </div>
        </div>
    </section>

    <section class="section__container gallery__container">
        <h2 class="section__header">04 GALLERY</h2>
        <div class="gallery__grid">
            <div class="gallery__col">
                <img src="gallery-1.jpg" alt="gallery" />
            </div>
            <div class="gallery__col">
                <img src="gallery-2.jpg" alt="gallery" />
                <img src="gallery-3.jpg" alt="gallery" />
                <img src="gallery-4.jpg" alt="gallery" />
                <img src="gallery-5.jpg" alt="gallery" />
            </div>
            <div class="gallery__col">
                <img src="gallery-6.jpg" alt="gallery" />
            </div>
        </div>
    </section>

    <footer class="footer">
        <div class="section__container footer__container">
            <div class="footer__col">
                <img src="logo-black.jpg" alt="footer logo" />
            </div>
            <div class="footer__col">
                <ul>
                   <a href="#"><li>BOOK A TEST RIDE</li></a> 
                   <a href="#"><li>DEALER LOCATOR</li></a>
                   <a href="#"><li>FINANCE OFFER</li></a>
                   <a href="#"><li>EXCHANGE YOUR BIKE</li></a>
                   <a href="#"><li>CONTACT US</li></a>
                </ul>
            </div>
            <div class="footer__col">
               <a href="#"><h4>FOLLOW US</h4></a> 
                <div class="socials">
                    <span><i class="ri-linkedin-fill"></i></span>
                    <span><i class="ri-pinterest-line"></i></span>
                    <span><i class="ri-twitter-fill"></i></span>
                    <span><i class="ri-facebook-fill"></i></span>
                </div>
            </div>
            <div class="footer__col">
                <a href="#"><h4>GET IN TOUCH</h4></a>
                <input type="text" placeholder="EMAIL" />
            </div>
        </div>
    </footer>
   
</body>

</html>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap");

:root {
  --primary-color: #dc2626;
  --text-dark: #171717;
  --text-light: #78716c;
  --extra-light: #f9f9f9;
  --white: #ffffff;
  --black: #000000;
  --max-width: 1200px;
}

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.section__container {
  max-width: var(--max-width);
  margin: auto;
  padding: 5rem 1rem;
}

.section__header {
  margin: auto;
  padding-bottom: 0.75rem;
  width: fit-content;
  position: relative;
  font-size: 1.5rem;
  font-weight: 600;
  color: var(--text-dark);
}

.section__header::before {
  position: absolute;
  content: "";
  bottom: 0;
  left: 0;
  height: 2px;
  width: 50px;
  background-color: var(--primary-color);
}

img {
  width: 100%;
  display: flex;
}

a {
  text-decoration: none;
}

body {
  font-family: "Poppins", sans-serif;
  background-color: var(--extra-light);
}

nav {
  max-width: var(--max-width);
  margin: auto;
  padding: 2rem 1rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 2rem;
}

.nav__logo img {
  max-width: 100px;
}

.nav__links {
  list-style: none;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 4rem;
}

.link a {
  font-weight: 500;
  color: var(--text-light);
  transition: 0.3s;
}

.link a:hover {
  color: var(--primary-color);
}

.header__container {
  padding-top: 0;
}

.story__container .section__header {
  margin-bottom: 4rem;
}

.story__container p {
  margin-bottom: 2rem;
  color: var(--text-dark);
}

.evolution__grid {
  margin-top: 4rem;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem;
  align-items: center;
}

.evolution__nav {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 2rem;
}

.evolution__nav a {
  padding: 0.75rem 0;
  font-weight: 500;
  color: var(--text-light);
  border-top: 2px solid transparent;
  transition: 0.3s;
}

.evolution__nav a:hover {
  color: var(--primary-color);
  border-color: var(--primary-color);
}

.evolution__nav a.active {
  color: var(--primary-color);
  border-color: var(--primary-color);
}

.evolution__content p {
  padding-top: 4rem;
  border-top: 2px solid var(--text-light);
}

.feature {
  margin: 5rem 0;
  position: relative;
  isolation: isolate;
}

.feature::before,
.feature::after {
  position: absolute;
  content: "";
  background-color: var(--black);
  inset: 0;
  z-index: -1;
}

.feature::before {
  -webkit-clip-path: polygon(0 0, 100% 0, 100% 50%, 0% 100%);
  clip-path: polygon(0 0, 100% 0, 100% 50%, 0% 100%);
  transform: skewY(8deg);
}

.feature::after {
  -webkit-clip-path: polygon(0 0, 100% 50%, 100% 100%, 0% 100%);
  clip-path: polygon(0 0, 100% 50%, 100% 100%, 0% 100%);
  transform: skewY(-8deg);
}

.feature__container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem;
  align-items: center;
}

.feature__image img {
  max-width: 550px;
  margin: auto;
}

.feature__content {
  margin: auto;
}

.feature__content .section__header {
  width: 100%;
  margin-bottom: 4rem;
  color: var(--white);
}

.feature__content ul {
  list-style: none;
  max-width: 400px;
}

.feature__content li {
  position: relative;
  margin-bottom: 2rem;
  padding-left: 1rem;
  color: var(--white);
}

.feature__content li::after {
  position: absolute;
  content: "";
  left: 0;
  top: 5px;
  height: 12px;
  width: 2px;
  background-color: var(--primary-color);
}

.gallery__container .section__header {
  width: 100%;
}

.gallery__grid {
  margin-top: 4rem;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 2rem;
}

.gallery__col:nth-child(2) {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem;
}

.footer {
  background-color: var(--black);
}

.footer__container {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 2rem;
}

.footer__col img {
  max-width: 100px;
}

.footer__col ul {
  list-style: none;
}

.footer__col li {
  position: relative;
  margin-bottom: 2rem;
  padding-left: 1rem;
  color: var(--white);
}

.footer__col li::after {
  position: absolute;
  content: "";
  left: 0;
  top: 5px;
  height: 12px;
  width: 2px;
  background-color: var(--primary-color);
}

.footer__col h4 {
  margin-bottom: 2rem;
  font-size: 1rem;
  font-weight: 500;
  color: var(--white);
}

.socials {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem;
  max-width: fit-content;
}

.socials span {
  display: inline-block;
  height: 40px;
  width: 40px;
  text-align: center;
  line-height: 40px;
  font-size: 1.2rem;
  color: var(--white);
  background-color: var(--text-light);
  border-radius: 100%;
  cursor: pointer;
  transition: 0.3s;
}

.socials span:hover {
  background-color: var(--text-dark);
}

.footer__col input {
  margin-bottom: 2rem;
  width: 100%;
  padding: 0.5rem 1rem;
  outline: none;
  border: none;
  color: var(--white);
  font-size: 1rem;
  background-color: var(--text-light);
}

.footer__col input::placeholder {
  color: var(--white);
}

.footer__col p {
  color: var(--white);
}

@media (width < 900px) {
  .feature__container {
    grid-template-columns: repeat(1, 1fr);
  }

  .gallery__grid {
    grid-template-columns: repeat(2, 1fr);
    gap: 1rem;
  }

  .gallery__col:nth-child(2) {
    gap: 1rem;
  }

  .footer__container {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (width < 600px) {
  .nav__links {
    display: none;
  }

  .evolution__grid {
    grid-template-columns: repeat(1, 1fr);
    gap: 5rem;
  }

  .gallery__grid {
    grid-template-columns: repeat(1, 1fr);
  }
}
