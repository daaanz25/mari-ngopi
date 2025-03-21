Website Kopi, playlist pak sandikah Galih

<h1>21/03/2025</h1>
<h2>Hero section </h2>

```html
<!-- Hero Scetion Start -->
<section class="hero" id="home">
  <main class="content">
    <h1>Mari Nikmati Secangkir <span>Kopi</span></h1>
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempore, nobis.
    </p>
    <a href="#" class="cta">Beli Sekarang</a>
  </main>
</section>
<!--Hero Scetion End -->
```

<h2> CSS Hero section </h2>

```css
/* Hero section */
.hero {
  min-height: 100vh;
  display: flex;
  align-items: center;
  background-image: url("../img/header-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  position: relative;
}

.hero::after {
  content: "";
  display: block;
  position: absolute;
  width: 100%;
  height: 30%;
  background: linear-gradient(
    0deg,
    rgba(1, 1, 3, 1) 8%,
    rgba(255, 255, 255, 0) 55%
  );
  bottom: 0;
}

.hero .content {
  padding: 1.4rem 6%;
  max-width: 60rem;
}

.hero .content h1 {
  font-size: 5em;
  color: #fff;
  text-shadow: 1px 1px 3px rgba(1, 1, 3, 0.5);
  line-height: 1.2;
}

.hero .content h1 span {
  color: var(--primay);
}

.hero .content p {
  font-size: 1.6rem;
  margin-top: 0.5rem;
  line-height: 1.4;
  font-weight: 100;
  text-shadow: 1px 1px 3px rgba(1, 1, 3, 0.5);
  mix-blend-mode: difference;
}
.hero .content .cta {
  margin-top: 1rem;
  display: inline-block;
  padding: 1rem 3rem;
  font-size: 1.4rem;
  color: #fff;
  background-color: var(--primay);
  border-radius: 0.5rem;
  box-shadow: 1px 1px 3px rgba(1, 1, 1, 0.5);
}
```

<h2> About section </h2>

```html
<!-- About Section Start -->
<section id="about" class="about">
  <h2><span>Tentang</span> Kami</h2>
  <div class="row">
    <div class="about-img">
      <img src="img/tentang-kami.jpg" alt="Tentang Kami" />
    </div>
    <div class="content">
      <h3>Kenapa memilih kopi kami</h3>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex culpa
        consectetur sapiente, odio voluptatibus incidunt!
      </p>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio
        culpa inventore odio optio assumenda ea? Quia dicta nulla voluptates
        nobis.
      </p>
    </div>
  </div>
</section>
<!-- About Section End -->
```

<h2> CSS About section </h2>

```css
/* About section */
.about {
  padding: 8rem 6% 1.4rem;
}
.about h2 {
  text-align: center;
  font-size: 2.6rem;
  margin-bottom: 3rem;
}
.about h2 span {
  color: var(--primay);
}
.about .row {
  display: flex;
}
.about .row .about-img {
  flex: 1 1 45rem;
}
.about .row .about-img img {
  width: 100%;
}
.about .row .content {
  flex: 1 1 35rem;
  padding: 0 1rem;
}
.about .row .content h3 {
  font-size: 1.8rem;
  margin-bottom: 1rem;
}
.about .row .content p {
  margin-bottom: 0.8rem;
  font-size: 1.3rem;
  font-weight: 100;
  line-height: 1.6;
}
```
