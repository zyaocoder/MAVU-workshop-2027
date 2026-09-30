<!-- =========================================
     AI Challenge Section
     ========================================= -->

<style>

/* ---------- Challenge Section ---------- */

.challenge-section {
  background: #ffffff;
  padding: 0px 30px 25px;
}

.challenge-container {
  max-width: 1150px;
  margin: 0 auto;
}


/* ---------- Section Header ---------- */

.challenge-header {
  text-align: center;
  margin-bottom: 25px;
}

.challenge-header h2 {
  font-size: 2rem;
  font-weight: 700;
  color: #0b3c6f;
  margin-top: 0;
  margin-bottom: 10px;
}

.challenge-header p {
  max-width: 850px;
  margin: 0 auto;
  color: #556575;
  font-size: 1.03rem;
  line-height: 1.6;
}


/* ---------- Main Challenge Description ---------- */

.challenge-intro {
  background: #f7fafc;
  border: 1px solid #e2eaf0;
  border-radius: 16px;
  padding: 22px 28px;
  margin-bottom: 22px;
}

.challenge-intro h3 {
  color: #0b3c6f;
  font-size: 1.3rem;
  margin-top: 0;
  margin-bottom: 10px;
}

.challenge-intro p {
  color: #445566;
  line-height: 1.65;
  margin: 0;
}


/* ---------- Main Information Cards ---------- */

.challenge-grid-main {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 18px;
  margin-bottom: 18px;
}


/* ---------- Secondary Cards ---------- */

.challenge-grid-secondary {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 18px;
  margin-bottom: 22px;
}


.challenge-card {
  border: 1px solid #dce6ed;
  border-radius: 16px;
  padding: 22px 24px;
  background: #ffffff;
  box-shadow: 0 4px 14px rgba(15, 55, 85, 0.04);
}

.challenge-card h3 {
  margin-top: 0;
  margin-bottom: 10px;
  color: #0b3c6f;
  font-size: 1.2rem;
}

.challenge-card p {
  margin: 0;
  color: #4f6070;
  line-height: 1.65;
}

.challenge-card ul {
  margin: 0;
  padding-left: 20px;
  color: #4f6070;
  line-height: 1.7;
}

.challenge-card li {
  margin-bottom: 5px;
}


/* ---------- Codabench ---------- */

.challenge-cta {
  text-align: center;
  background: #f5fafc;
  border-radius: 16px;
  padding: 22px 20px;
}

.challenge-cta h3 {
  color: #0b3c6f;
  margin-top: 0;
  margin-bottom: 5px;
}

.challenge-cta p {
  color: #5b6976;
  margin: 0 0 15px;
}

.challenge-button {
  display: inline-block;
  background: #087fa0;
  color: #ffffff !important;
  padding: 11px 24px;
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

  .challenge-grid-main {
    grid-template-columns: 1fr;
  }

  .challenge-grid-secondary {
    grid-template-columns: 1fr;
  }

}


@media (max-width: 720px) {

  .challenge-section {
    padding: 30px 20px 40px;
  }

  .challenge-intro {
    padding: 20px;
  }

  .challenge-card {
    padding: 20px;
  }

}

</style>


<div id="challenge" class="challenge-section">

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
         Challenge Introduction
         ===================================== -->

    <div class="challenge-intro">

      <h3>What is the Challenge About?</h3>

      <p>
        Participants will develop models that answer natural-language
        questions about high-resolution aerial video sequences captured by
        drones. The questions require models to understand objects, scenes,
        events, spatial relationships, and temporal changes across video
        frames. The goal is to evaluate how well modern video-language models
        can reason about complex aerial scenes.
      </p>

    </div>


    <!-- =====================================
         Main Information
         ===================================== -->

    <div class="challenge-grid-main">


      <!-- Task -->

      <div class="challenge-card">

        <h3>Task</h3>

        <p>
          Given a drone video and a natural-language multiple-choice question,
          participants must predict the correct answer. Questions require
          understanding and reasoning over both spatial and temporal
          information in aerial scenes.
        </p>

      </div>


      <!-- Details -->

      <div class="challenge-card">

        <h3>Details</h3>

        <ul>
          <li>
            <strong>4,000</strong> question-answer pairs from
            <strong>1,014</strong> drone videos
          </li>

          <li>
            Videos collected across <strong>18 cities worldwide</strong>
          </li>

          <li>
            Average video length: <strong>~15 seconds</strong>
          </li>

          <li>
            Baseline model: <strong>BIMBA</strong>
          </li>
        </ul>

      </div>


      <!-- Evaluation -->

      <div class="challenge-card">

        <h3>Evaluation</h3>

        <ul>
          <li>
            Prizes sponsored by <strong>Qualcomm</strong>:<br>
            <p>&nbsp;&nbsp;</p><strong>Champion🥇— $1,000</strong><br>
            <p>&nbsp;&nbsp;</p><strong>2nd Place🥈— $500</strong><br>
            <p>&nbsp;&nbsp;</p><strong>3rd Place🥉— $200</strong>
          </li>
          <li>
            Primary metric:
            <strong>overall multiple-choice accuracy</strong>
          </li>
        </ul>

      </div>

    </div>


    <!-- =====================================
         Example + Awards
         ===================================== -->

    <div class="challenge-grid-secondary">


      <!-- Example -->

      <div class="challenge-card">

        <h3>Example Question</h3>

        <p>
          Questions may require reasoning across multiple video frames.
          For example:
          <em>
            “How long does the yellow taxi remain visible in the video frame?”
          </em>
        </p>

      </div>


      <!-- Awards -->

      <div class="challenge-card">

        <h3>Workshop Presentation</h3>

        <p>
          Top-performing teams will be recognized during the MAVU workshop.
          Selected teams will be invited to present their solutions and
          findings at WACV 2027.
        </p>

      </div>

    </div>


    <!-- =====================================
         Codabench
         ===================================== -->

    <div class="challenge-cta">

      <h3>Participate in the Challenge</h3>

      <p>
        Challenge submissions and leaderboard evaluation are hosted on
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

</div>
