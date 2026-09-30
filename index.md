---
title: Home
layout: default
---

<style>
/* =========================================
   MAVU Homepage Hero
   ========================================= */

.mavu-hero {
  background: #f3f6fb;
  padding: 50px 30px 32px;
  margin-bottom: 45px;
  border-bottom: 1px solid #dfe6ee;
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
  flex: 1 1 auto;
  max-width: 850px;
}

.mavu-main-logo figure {
  margin: 0 !important;
}

.mavu-main-logo img {
  width: 100% !important;
  max-width: 850px;
  height: auto;
  display: block;
  object-fit: contain;
}

.mavu-main-logo figcaption {
  display: none;
}


/* ---------- WACV block ---------- */

.wacv-block {
  flex: 0 0 225px;
  text-align: left;
  padding-top: 5px;
}

.wacv-label {
  font-size: 0.93rem;
  color: #5d6673;
  margin-bottom: 12px;
  line-height: 1.4;
}

.wacv-label strong {
  color: #32465a;
  font-weight: 600;
}

.wacv-logo figure {
  margin: 0 !important;
}

.wacv-logo img {
  width: 190px !important;
  max-width: 100%;
  height: auto;
  display: block;
}

.wacv-logo figcaption {
  display: none;
}


/* ---------- Workshop information ---------- */

.workshop-info {
  margin-top: 38px;
  padding-top: 25px;
  border-top: 1px solid rgba(25, 70, 110, 0.12);

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


/* ---------- Optional full workshop name ---------- */

.workshop-full-name {
  text-align: center;
  margin-top: 12px;
  font-size: 0.95rem;
  color: #6b7785;
}


/* =========================================
   Responsive
   ========================================= */

@media (max-width: 950px) {

  .mavu-brand-row {
    gap: 30px;
  }

  .wacv-block {
    flex-basis: 180px;
  }

  .wacv-logo img {
    width: 160px !important;
  }

}


@media (max-width: 720px) {

  .mavu-hero {
    padding: 35px 20px 26px;
  }

  .mavu-brand-row {
    flex-direction: column;
    gap: 25px;
  }

  .mavu-main-logo {
    width: 100%;
  }

  .wacv-block {
    text-align: center;
    flex: none;
  }

  .wacv-logo img {
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


      <!-- WACV -->
      <div class="wacv-block">

        <div class="wacv-label">
          <strong>In conjunction with</strong>
        </div>

        <div class="wacv-logo">
          {% include figure.html
             img="wacv27_logo.png"
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

      <span>January 4 or 5 (Half-Day), 2027</span>

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
