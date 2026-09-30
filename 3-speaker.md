---
title: Keynote Speakers
nav: true
---

<style>
/* ===== Keynote Speaker Section ===== */

.speaker-header {
  margin-bottom: 2.5rem;
}

.speaker-header h1 {
  margin-bottom: 0.5rem;
}

.speaker-header p {
  color: #667085;
  font-size: 1.05rem;
  max-width: 700px;
}


/* ===== Card Grid ===== */

.speaker-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
  margin-bottom: 3rem;
}


/* ===== Individual Card ===== */

.speaker-card {
  background: #ffffff;
  border: 1px solid #dce5e9;
  border-radius: 22px;
  padding: 28px 24px 30px;
  box-shadow: 0 10px 30px rgba(20, 50, 65, 0.06);

  display: flex;
  flex-direction: column;

  transition:
    transform 0.25s ease,
    box-shadow 0.25s ease;
}

.speaker-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 16px 36px rgba(20, 50, 65, 0.12);
}


/* ===== Speaker Photo ===== */

.speaker-photo {
  width: 125px;
  height: 125px;
  margin-bottom: 22px;
}

.speaker-photo figure {
  margin: 0 !important;
  width: 125px;
  height: 125px;
}

.speaker-photo img {
  width: 125px !important;
  height: 125px !important;
  object-fit: cover;
  object-position: center;
  border-radius: 50%;
  margin: 0 !important;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
}

.speaker-photo figcaption {
  display: none;
}


/* ===== Speaker Information ===== */

.speaker-name {
  font-size: 1.25rem;
  font-weight: 700;
  color: #102a43;
  margin-bottom: 7px;
  line-height: 1.3;
}

.speaker-affiliation {
  color: #00879a;
  font-size: 0.95rem;
  font-weight: 600;
  line-height: 1.5;
  min-height: 46px;
}


/* ===== Divider ===== */

.speaker-divider {
  height: 1px;
  background: #dce5e9;
  margin: 22px 0;
}


/* ===== Talk ===== */

.talk-label {
  font-size: 0.78rem;
  font-weight: 700;
  letter-spacing: 0.07em;
  text-transform: uppercase;
  color: #00879a;
  margin-bottom: 8px;
}

.talk-title {
  color: #34495e;
  font-size: 0.98rem;
  line-height: 1.6;
}


/* ===== Responsive Layout ===== */

@media (max-width: 1000px) {
  .speaker-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

@media (max-width: 650px) {
  .speaker-grid {
    grid-template-columns: 1fr;
  }

  .speaker-card {
    padding: 24px 22px;
  }
}
</style>


<div class="speaker-header">
  <h1>Keynote Speakers</h1>
  <p>
    We are delighted to welcome our keynote speakers to the workshop.
  </p>
</div>


<div class="speaker-grid">


<!-- ==================== Speaker 1 ==================== -->

<div class="speaker-card">

  <div class="speaker-photo">
    {% include figure.html
       img="dm2018-face.jpg"
       alt="Photo of Dr. Dinesh Manocha"
       caption=""
       width="100%" %}
  </div>

  <div class="speaker-name">
    Dinesh Manocha
  </div>

  <div class="speaker-affiliation">
    University of Maryland at College Park
  </div>

  <div class="speaker-divider"></div>

  <div class="talk-label">
    Keynote Talk
  </div>

  <div class="talk-title">
    Towards General Audio-Visual Intelligence
  </div>

</div>



<!-- ==================== Speaker 2 ==================== -->

<div class="speaker-card">

  <div class="speaker-photo">
    {% include figure.html
       img="XiaomingLiu-768x768.avif"
       alt="Photo of Dr. Xiaoming Liu"
       caption=""
       width="100%" %}
  </div>

  <div class="speaker-name">
    Xiaoming Liu
  </div>

  <div class="speaker-affiliation">
    University of North Carolina at Chapel Hill
  </div>

  <div class="speaker-divider"></div>

  <div class="talk-label">
    Keynote Talk
  </div>

  <div class="talk-title">
    To be announced
  </div>

</div>



<!-- ==================== Speaker 3 ==================== -->

<div class="speaker-card">

  <div class="speaker-photo">
    {% include figure.html
       img="LiuYang.jpg"
       alt="Photo of Dr. Yang Liu"
       caption=""
       width="100%" %}
  </div>

  <div class="speaker-name">
    Yang Liu
  </div>

  <div class="speaker-affiliation">
    Qualcomm
  </div>

  <div class="speaker-divider"></div>

  <div class="talk-label">
    Keynote Talk
  </div>

  <div class="talk-title">
    To be announced
  </div>

</div>


</div>
