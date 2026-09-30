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
  padding: 50px 30px 32px;
  margin-bottom: 45px;
}

.mavu-hero-inner {
  max-width: 1250px;
  margin: 0 auto;
}


/* ---------- Main logo row ---------- */

.mavu-brand-row {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 55px;
}


/* ---------- MAVU logo ---------- */

.mavu-main-logo {
  flex: 0 1 638px;
  max-width: 638px;
}

.mavu-main-logo figure {
  margin: 0 !important;
}

.mavu-main-logo img {
  width: 100% !important;
  max-width: 638px;
  height: auto;
  display: block;
  object-fit: contain;
}

.mavu-main-logo figcaption {
  display: none;
}


/* ---------- WACV logo ---------- */

.wacv-block {
  flex: 0 0 380px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.wacv-logo {
  width: 380px;
}

.wacv-logo figure {
  margin: 0 !important;
}

.wacv-logo img {
  width: 380px !important;
  max-width: 100%;
  height: auto;
  display: block;
  object-fit: contain;
}

.wacv-logo figcaption {
  display: none;
}


/* ---------- Workshop information ---------- */

.workshop-info {
  margin-top: 38px;
  padding-top: 10px;

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

@media (max-width: 1100px) {

  .mavu-brand-row {
    gap: 35px;
  }

  .mavu-main-logo {
    flex: 0 1 55%;
    max-width: 638px;
  }

  .wacv-block {
    flex: 0 1 32%;
  }

  .wacv-logo {
    width: 100%;
    max-width: 380px;
  }

  .wacv-logo img {
    width: 100% !important;
  }

}


@media (max-width: 720px) {

  .mavu-hero {
    padding: 35px 20px 26px;
  }

  .mavu-brand-row {
    flex-direction: column;
    gap: 20px;
  }

  .mavu-main-logo {
    width: 85%;
    max-width: 638px;
    flex: none;
  }

  .wacv-block {
    width: 65%;
    max-width: 380px;
    flex: none;
  }

  .wacv-logo {
    width: 100%;
  }

  .wacv-logo img {
    width: 100% !important;
    margin: 0 auto;
  }

  .workshop-info {
    flex-direction: column;
    gap: 5px;
    text-align: center;
    margin-top: 28px;
  }

  .workshop-info .separator {
    display: none;
  }

}
</style>


<section id="home" class="mavu-hero">

  <div class="mavu-hero-inner">

    <!-- ==============================
         Logo Row
         ============================== -->

    <div class="mavu-brand-row">

      <!-- MAVU main logo -->
      <div class="mavu-main-logo">
        {% include figure.html
           img="MAVU_logo.png"
           alt="MAVU - Multi-Faceted Video Understanding"
           caption=""
           width="100%" %}
      </div>


      <!-- WACV logo -->
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


    <!-- ==============================
         Date / Location
         ============================== -->

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
