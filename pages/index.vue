<template>
  <div class="wrapper">
    <!-- <nav class="menu navbar navbar-expand-sm">
    <ul class="menu__list navbar-nav">
      <li class="menu__item nav-item ml-5">
        <n-link class="nav-link" :to="`/`">Home</n-link>
      </li>
      <li class="menu__item nav-item ml-5">
        <n-link class="nav-link" :to="`/#services`">Our Services</n-link>
      </li>
      <li class="menu__item nav-item ml-5">
        <n-link class="nav-link" :to="`/#reviews`">Portfolio</n-link>
      </li>
      <li class="menu__item nav-item ml-5">
        <n-link class="nav-link" :to="`/#faqs`">Contact</n-link>
      </li>
    </ul>
  </nav> -->
    <header class="header">
      <div class="header__logo">
        <img
          src="~assets/images/candr_logo.png"
          alt="Click and Rivets logo"
        />
      </div>
    </header>
    <main>
      <section class="menu">
        <div class="row justify-content-center m-0">
          <n-link to="#services">
            <div class="menu__menu__item mr-5">
              <span class="menu__menu__item--text">Our Services</span>
            </div>
          </n-link>
          <n-link to="#portfolio">
            <div class="menu__menu__item mr-5">
              <span class="menu__menu__item--text">Our Work</span>
            </div>
          </n-link>
          <n-link to="#contact">
            <div class="menu__menu__item">
              <span class="menu__menu__item--text">Contact Us</span>
            </div>
          </n-link>
        </div>
      </section>

      <section id="main-copy" class="main-copy">
        <h2 class="main-copy--heading">Get a Website Tailored for Your Business</h2>
        <p class="main-copy--text">
          Your web presence is more important than ever. Your customers expect to be able to find and do business with you online. 
        </p>


        <h3 class="main-copy--heading">Your Website Should Grow Your Business</h3>
        <p class="main-copy--text">
          Small businesses have been hit hard by the pandemic. Providing online services can help your business not only survive but thrive. 
        </p>

        <h3 id="services" class="main-copy--heading">What We Offer</h3>

        <p class="main-copy--text">
          We offer a variety of services to help your business.
        </p>      
      </section>
      
      <section id="portfolio" class="portfolio">
        <h2 class="portfolio__heading">Our Work</h2>     
        <div class="cards">
          <div class="cards__card">
            <div class="cards__card__face cards__card__face--front">
              <a href="https://route53medical.com" target="_blank">
                <img src="~assets/images/screenshots/rt53.png" alt="Route 53 Medicine" />
              </a>
            </div>
            <div class="cards__card__face cards__card__face--back">
              <a href="https://route53medical.com" target="_blank">
                <div class="cards__card__face--back--inner">
                  <img src="/favicon.png" alt="" />
                  <p class="cards__card__face--back--text">
                    Route 53 Medical
                  </p>
                </div>
              </a>
            </div>
        </div>
          <div class="cards__card">
            <div class="cards__card__face cards__card__face--front">
              <a href="https://richthetreeman.com" target="_blank">
                <img src="~assets/images/screenshots/treeman.png" alt="The Treeman" />
              </a>
            </div>
            <div class="cards__card__face cards__card__face--back">
              <a href="https://richthetreeman.com" target="_blank">
                <div class="cards__card__face--back--inner">
                  <img src="/favicon.png" alt="" />
                  <p class="cards__card__face--back--text">
                    The Tree Man
                  </p>
                </div>
              </a>
            </div>
          </div>
          <div class="cards__card">
            <div class="cards__card__face cards__card__face--front">
              <a href="https://terryalbarella.com" target="_blank">
                <img src="~assets/images/screenshots/ta.png" alt="Terry Albarella" />
              </a>
            </div>
            <div class="cards__card__face cards__card__face--back">
              <a href="https://terryalbarella.com" target="_blank">
                <div class="cards__card__face--back--inner">
                  <img src="/favicon.png" alt="" />
                  <p class="cards__card__face--back--text">
                    Terry Albarella
                  </p>
                </div>
              </a>
            </div>
          </div>
          <div class="cards__card">
            <div class="cards__card__face cards__card__face--front">
              <a href="https://highclasstree.services" target="_blank">
                <img src="~assets/images/screenshots/highclass.png" alt="High Class Tree Services" />
              </a>
            </div>
            <div class="cards__card__face cards__card__face--back">
              <a href="https://highclasstree.services" target="_blank">
                <div class="cards__card__face--back--inner">
                  <img src="/favicon.png" alt="" />
                  <p class="cards__card__face--back--text">
                    High Class Tree Service
                  </p>
                </div>
              </a>
            </div>
          </div>
        </div>
      </section>
    
      <section id="contact" class="contact-form">
        <h2 class="contact__heading">Contact Us</h2>
        <div class="form__container">
          <form name="contact" netlify>
            <div class="form-group mt-4">
              <label for="name" class="form-label">Name</label>
              <input
                id="name"
                type="text"
                name="name"
                class="form-control"
                required
              />
            </div>
            <div class="form-group mt-4">
              <label for="email" class="form-label">Email</label>
              <input
                id="email"
                type="email"
                name="email"
                class="form-control"
                required
              />
            </div>
            <div class="form-group mt-4">
              <label for="message" class="form-label">Message</label>
              <textarea
                id="message"
                name="message"
                class="form-control"
                rows="6"
                cols="50"
                required
              ></textarea>
            </div>

            <div class="row">
              <button class="btn btn-submit">Send</button>
            </div>
          </form>
        </div>
      </section>
    </main>

    <footer class="footer">
      <div class="footer__social-bar">
        <a href="https://www.facebook.com/Clicks-and-Rivets-111094736905456"
           target="_blank"><font-awesome-icon :icon="['fab', 'facebook-f']"
        /></a>
        <a href="https://www.instagram.com/clicksandrivets/"
           target="_blank"><font-awesome-icon :icon="['fab', 'instagram']"
        /></a>
        <a href="https://twitter.com/clicksandrivets"
           target="_blank"><font-awesome-icon :icon="['fab', 'twitter']"
        /></a>
      </div>
      <div class="footer__attribution">
          &copy; 2020 Clicks and Rivets LLC
      </div>
    </footer>
  </div>
</template>

<script>
export default {}
</script>