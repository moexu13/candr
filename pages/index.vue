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
      <section class="cards">
        <div class="row justify-content-center m-0">
          <div class="cards__card">
            <span class="cards__card--text">Our Services</span>
          </div>
          <div class="cards__card">
            <span class="cards__card--text">Our Work</span>
          </div>
          <div class="cards__card">
            <span class="cards__card--text">Contact Us</span>
          </div>
        </div>
      </section>

      <section id="main-copy" class="main-copy">

        <h2 class="main-copy--heading">Your Website Should Grow Your Business</h2>

        <p class="main-copy--text">
          Small businesses have been hit hard by the pandemic. Providing online services can help your business not only survive but thrive. 
        </p>

        <h2 class="main-copy--heading">What We Offer</h2>

        <p class="main-copy--text">
          We offer a variety of services to help your business.
        </p>

        <h2 class="main-copy--heading">Get a Website Tailored for Your Business</h2>
        
        <p class="main-copy--text">
          Your web presence is more important than ever. Your customers expect to be able to find and do business with you online. 
        </p>
      </section>

      <section id="about"></section>
      
      <section id="portfolio"></section>
    
      <section id="contact">
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
  </div>
</template>

<script>
export default {}
</script>