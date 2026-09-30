<!-- =========================================
     AI Challenge Section
     ========================================= -->
---
title: Call for Papers
nav: true
---

<style>

/* ---------- Challenge Section ---------- */

.challenge-section {
  background: #ffffff;
  padding: 55px 30px 65px;
}

.challenge-container {
  max-width: 1150px;
  margin: 0 auto;
}


/* ---------- Section Header ---------- */

.challenge-header {
  text-align: center;
  margin-bottom: 38px;
}

.challenge-header h2 {
  font-size: 2rem;
  font-weight: 700;
  color: #0b3c6f;
  margin-bottom: 12px;
}

.challenge-header p {
  max-width: 850px;
  margin: 0 auto;
  color: #556575;
  font-size: 1.03rem;
  line-height: 1.7;
}


/* ---------- Main Challenge Description ---------- */

.challenge-intro {
  background: #f7fafc;
  border: 1px solid #e2eaf0;
  border-radius: 18px;
  padding: 28px 32px;
  margin-bottom: 35px;
}

.challenge-intro h3 {
  color: #0b3c6f;
  font-size: 1.35rem;
  margin-top: 0;
  margin-bottom: 12px;
}

.challenge-intro p {
  color: #445566;
  line-height: 1.75;
  margin-bottom: 0;
}


/* ---------- Benchmark Statistics ---------- */

.challenge-stats {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 18px;
  margin-bottom: 38px;
}

.challenge-stat-card {
  background: #ffffff;
  border: 1px solid #dce6ed;
  border-radius: 16px;
  padding: 22px 18px;
  text-align: center;
  box-shadow: 0 5px 18px rgba(15, 55, 85, 0.05);
}

.challenge-stat-number {
  font-size: 1.65rem;
  font-weight: 700;
  color: #008faf;
  margin-bottom: 6px;
}

.challenge-stat-label {
  font-size: 0.92rem;
  color: #5c6b78;
  line-height: 1.4;
}


/* ---------- Information Cards ---------- */

.challenge-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 22px;
  margin-bottom: 38px;
}

.challenge-card {
  border: 1px solid #dce6ed;
  border-radius: 18px;
  padding: 26px 28px;
  background: #ffffff;
}

.challenge-card h3 {
  margin-top: 0;
  margin-bottom: 12px;
  color: #0b3c6f;
  font-size: 1.25rem;
}

.challenge-card p {
  margin: 0;
  color: #4f6070;
  line-height: 1.7;
}

.challenge-card ul {
  margin: 0;
  padding-left: 20px;
  color: #4f6070;
  line-height: 1.8;
}


/* ---------- Codabench CTA ---------- */

.challenge-cta {
  margin-top: 10px;
  text-align: center;
  background: #f5fafc;
  border-radius: 18px;
  padding: 30px 25px;
}

.challenge-cta h3 {
  color: #0b3c6f;
  margin-top: 0;
  margin-bottom: 8px;
}

.challenge-cta p {
  color: #5b6976;
  margin-bottom: 20px;
}

.challenge-button {
  display: inline-block;
  background: #087fa0;
  color: #ffffff !important;
  padding: 12px 26px;
  border-radius: 8px;
  text-decoration: none !important;
  font-weight: 600;
  transition: all 0.2s ease;
}

.challenge-button:hover {
  background: #056d8a;
  transform: translateY(-2px);
}


/* ---------- Responsive ---------- */

@media (max-width: 900px) {

  .challenge-stats {
    grid-template-columns: repeat(2, 1fr);
  }

}


@media (max-width: 720px) {

  .challenge-section {
    padding: 40px 20px 50px;
  }

  .challenge-grid {
    grid-template-columns: 1fr;
  }

  .challenge-stats {
    grid-template-columns: repeat(2, 1fr);
  }

  .challenge-intro {
    padding: 24px 22px;
  }

}


@media (max-width: 450px) {

  .challenge-stats {
    grid-template-columns: 1fr;
  }

}

</style>


<section id="challenge" class="challenge-section">

  <div class="challenge-container">


    <!-- =====================================
         Header
         ===================================== -->

    <div class="challenge-header">

      <h2>AI Challenge: VQA on Drone Videos</h2>

      <p>
        The MAVU workshop will host an AI challenge on
        <strong>Video Question Answering (VQA) for drone videos</strong>,
        designed to benchmark recent advances in video understanding,
        spatiotemporal reasoning, and remote sensing.
      </p>

    </div>


    <!-- =====================================
         Challenge Task
         ===================================== -->

    <div class="challenge-intro">

      <h3>What is the Challenge About?</h3>

      <p>
        Participants will develop models that answer natural-language
        questions about high-resolution aerial video sequences captured by
        drones. The questions require models to understand objects, scenes,
        events, activities, spatial relationships, and temporal changes across
        video frames. The goal is to evaluate how well modern video-language
        models can reason about complex aerial scenes rather than relying only
        on information from individual frames.
      </p>

    </div>


    <!-- =====================================
         Benchmark Overview
         ===================================== -->

    <div class="challenge-stats">

      <div class="challenge-stat-card">
        <div class="challenge-stat-number">4,000</div>
        <div class="challenge-stat-label">
          Question-Answer Pairs
        </div>
      </div>

      <div class="challenge-stat-card">
        <div class="challenge-stat-number">1,014</div>
        <div class="challenge-stat-label">
          Drone Videos
        </div>
      </div>

      <div class="challenge-stat-card">
        <div class="challenge-stat-number">18</div>
        <div class="challenge-stat-label">
          Cities Worldwide
        </div>
      </div>

      <div class="challenge-stat-card">
        <div class="challenge-stat-number">~15 sec</div>
        <div class="challenge-stat-label">
          Average Video Length
        </div>
      </div>

    </div>


    <!-- =====================================
         Detailed Information
         ===================================== -->

    <div class="challenge-grid">


      <!-- Task -->

      <div class="challenge-card">

        <h3>Task</h3>

        <p>
          Given a drone video together with a natural-language
          multiple-choice question, participants must predict the correct
          answer. Questions cover visual understanding and reasoning over both
          spatial and temporal information in aerial scenes.
        </p>

      </div>


      <!-- Evaluation -->

      <div class="challenge-card">

        <h3>Evaluation</h3>

        <ul>
          <li>
            Primary metric:
            <strong>overall multiple-choice accuracy</strong>
          </li>

          <li>
            Performance will also be reported for individual reasoning tasks.
          </li>

          <li>
            Final rankings will be determined using predictions on the
            challenge test set.
          </li>
        </ul>

      </div>


      <!-- Example -->

      <div class="challenge-card">

        <h3>Example Question</h3>

        <p>
          Questions require models to reason about information distributed
          across the video. For example:
          <br><br>
          <em>
            “How long does the yellow taxi remain visible in the video frame?”
          </em>
        </p>

      </div>


      <!-- Baselines -->

      <div class="challenge-card">

        <h3>Baselines & Resources</h3>

        <p>
          We will provide benchmark data, evaluation instructions, and example
          solutions to help participants get started. General-domain video
          question answering models, such as <strong>BIMBA</strong>, can serve
          as initial baselines for the challenge.
        </p>

      </div>


      <!-- Participation -->

      <div class="challenge-card">

        <h3>Participation</h3>

        <p>
          The challenge is open to researchers and practitioners interested in
          video understanding, multimodal learning, and remote sensing. Teams
          can submit predictions to the public evaluation platform and compare
          their results on the leaderboard.
        </p>

      </div>


      <!-- Awards -->

      <div class="challenge-card">

        <h3>Awards & Workshop Presentation</h3>

        <p>
          Top-performing teams will be recognized during the MAVU workshop.
          Selected teams will be invited to present their approaches and
          findings at WACV 2027, providing an opportunity to share successful
          methods with the broader research community.
        </p>

      </div>

    </div>


    <!-- =====================================
         Codabench
         ===================================== -->

    <div class="challenge-cta">

      <h3>Participate in the Challenge</h3>

      <p>
        Challenge submissions and leaderboard evaluation will be hosted on
        Codabench.
      </p>

      <a
        class="challenge-button"
        href="https://www.codabench.org/competitions/18274/"
        target="_blank"
        rel="noopener noreferrer">
        Go to Codabench →
      </a>

    </div>


  </div>

</section>
