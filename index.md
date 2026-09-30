---
title: Home
layout: default
---

<style>
/* =========================================
   MAVU Homepage Hero
   ========================================= */

.mavu-hero {
  background: #ffffff;

  /* No blank space above logos */
  padding: 0 30px 0;

  margin-top: 0;
  margin-bottom: 0;
}

.mavu-hero-inner {
  max-width: 1250px;
  margin: 0 auto;
}


/* =========================================
   Main Logo Row
   ========================================= */

.mavu-brand-row {
  display: flex;
  align-items: center;
  justify-content: center;

  /* Space only between MAVU and WACV */
  gap: 55px;

  margin: 0;
  padding: 0;
}


/* =========================================
   MAVU Logo
   75% of previous 638px ≈ 478px
   ========================================= */

.mavu-main-logo {
  flex: 0 1 478px;
  max-width: 478px;

  margin: 0;
  padding: 0;
}

.mavu-main-logo figure {
  margin: 0 !important;
  padding: 0 !important;
}

.mavu-main-logo img {
  width: 100% !important;
  max-width: 478px;

  height: auto;
  display: block;

  margin: 0 !important;
  padding: 0 !important;

  object-fit: contain;
}

.mavu-main-logo figcaption {
  display: none;
}


/* =========================================
   WACV Logo
   50% of previous 380px = 190px
   ========================================= */

.wacv-block {
  flex: 0 0 190px;

  display: flex;
  align-items: center;
  justify-content: center;

  margin: 0;
  padding: 0;
}

.wacv-logo {
  width: 190px;

  margin: 0;
  padding: 0;
}

.wacv-logo figure {
  margin: 0 !important;
  padding: 0 !important;
}

.wacv-logo img {
  width: 190px !important;
  max-width: 100%;

  height: auto;
  display: block;

  margin: 0 !important;
  padding: 0 !important;

  object-fit: contain;
}

.wacv-logo figcaption {
  display: none;
}


/* =========================================
   Workshop Information
   ========================================= */

.workshop-info {

  /* No blank space between logos and text */
  margin: 0;
  padding: 0;

  display: flex;
  justify-content: center;
  align-items: center;

  gap: 14px;

  font-size: 1.08rem;
  font-weight: 600;
  color: #394b5f;
}

.workshop-info .separator {
  color: #149dcc;
  font-size: 1.2rem;
}


/* =========================================
   Responsive
   ========================================= */

@media (max-width: 900px) {

  .mavu-brand-row {
    gap: 30px;
  }

  .mavu-main-logo {
    flex: 0 1 55%;
    max-width: 478px;
  }

  .wacv-block {
    flex: 0 1 25%;
    max-width: 190px;
  }

  .wacv-logo {
    width: 100%;
    max-width: 190px;
  }

  .wacv-logo img {
    width: 100% !important;
  }
}


@media (max-width: 720px) {

  .mavu-hero {
    padding: 0 20px;
  }

  .mavu-brand-row {
    flex-direction: column;

    /* Small gap between logos on mobile */
    gap: 8px;

    margin: 0;
    padding: 0;
  }

  .mavu-main-logo {
    width: 75%;
    max-width: 478px;
    flex: none;
  }

  .wacv-block {
    width: 40%;
    max-width: 190px;
    flex: none;
  }

  .wacv-logo {
    width: 100%;
  }

  .wacv-logo img {
    width: 100% !important;
    margin: 0 auto !important;
  }

  .workshop-info {
    flex-direction: column;
    gap: 2px;

    text-align: center;

    margin: 0;
    padding: 0;
  }

  .workshop-info .separator {
    display: none;
  }
}
</style>


<section id="home" class="mavu-hero">

  <div class="mavu-hero-inner">

    <!-- =====================================
         Logos
         ===================================== -->

    <div class="mavu-brand-row">

      <!-- MAVU Logo -->
      <div class="mavu-main-logo">
        {% include figure.html
           img="MAVU_logo.png"
           alt="MAVU - Multi-Faceted Video Understanding"
           caption=""
           width="100%" %}
      </div>


      <!-- WACV Logo -->
      <div class="wacv-block">

        <div class="wacv-logo">
          {% include figure.html
             img="wacv-logo.svg"
             alt="WACV 2027 - Orlando, Florida"
             caption=""
             width="100%" %}
        </div>

      </div>

    </div>


    <!-- =====================================
         Date and Location
         ===================================== -->

    <div class="workshop-info">

      <span>January 4 or 5 (Full-Day), 2027</span>

      <span class="separator">•</span>

      <span>Disney Springs, Buena Vista, FL</span>

    </div>

  </div>

</section>

<hr>

{% include embed-page.html file="0-prep.md" id="about" %}

<hr>

{% include embed-page.html file="1-intro.md" id="call-for-papers" %}

<hr>

{% include embed-page.html file="3-speaker.md" id="speakers" %}

<hr>

{% include embed-page.html file="2-program.md" id="program-schedule" %}

<hr>

{% include embed-page.html file="4-resources.md" id="organizers" %}

<hr>

<div class="page-footer" markdown="1">

> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})).
> Last build date: {{ site.time | date: "%Y-%m-%d" }}.
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>

</div>
