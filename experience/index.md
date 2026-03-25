---
title: Experience
nav:
  order: 2
  tooltip: Research & professional experiences
---

# {% include icon.html icon="fa-solid fa-microscope" %}Experience

See my work & research experiences.

<div class="exp-container">

  <h2>Research Experience</h2>

  <!-- Lab 1 -->
  <details class = "exp-card research">
    <summary class = "exp-header">
      <div class = "experience-image">
        <img
          class = "img-fluid"
          src = "images/icon.png"
          alt = "Image"
          />
      </div>
      <div class="experience-info">
        <div class="exp-title">
          Center for Self-assembly and Complexity (CSC)
        </div>
        <div class="exp-period">
          Jun 2022 — Feb 2023, Oct 2025 — Present
        </div>
        <div class="exp-role">
          Undergraduate researcher, Researcher
        </div>
    </summary>
    <div class="exp-body">
      <p class="exp-section-title">Problem</p>
      <p>
        Understanding adhesion behavior in polymer thin films under varying conditions.
      </p>
      <p class="exp-section-title">Approach</p>
      <p>
        Deposited polymer thin films via initiated chemical vapor deposition (iCVD) and characterized interfacial interactions.
      </p>
      <p class="exp-section-title">Insight</p>
      <p>
        Identified key parameters governing adhesion performance and their dependence on deposition conditions.
      </p>
    </div>
  </details>
  <hr />
  
  <!-- Lab 2 -->
  <details class="exp-card research">
    <summary class="exp-header">
      <strong class="exp-title">Soft Materials Lab, XXX Institute (4 months)</strong><br>
      <span class="exp-summary">
        Designed physically crosslinked hydrogel networks for adaptive adhesion
      </span>
    </summary>

    <div class="exp-body">
      <p class="exp-section-title">Problem</p>
      <p>
        Developing hydrogel systems that balance strong adhesion with mechanical adaptability.
      </p>

      <p class="exp-section-title">Approach</p>
      <p>
        Designed and synthesized physically crosslinked polymer networks and evaluated their viscoelastic and adhesive properties.
      </p>

      <p class="exp-section-title">Insight</p>
      <p>
        Revealed how network structure influences adhesion performance under dynamic conditions.
      </p>
    </div>
  </details>


  <h2 style="margin-top:40px;">Professional Experience</h2>

  <!-- Internship -->
  <details class="exp-card professional">
    <summary class="exp-header">
      <strong class="exp-title">Ministry of Science and ICT (Intern, 2026–Present)</strong><br>
      <span class="exp-summary">
        Exploring science policy and the interface between research and application
      </span>
    </summary>

    <div class="exp-body">
      <p class="exp-section-title">Context</p>
      <p>
        Working within a national science and technology policy environment.
      </p>

      <p class="exp-section-title">Focus</p>
      <p>
        Examining how fundamental research translates into real-world applications and policy decisions.
      </p>

      <p class="exp-section-title">Perspective</p>
      <p>
        Gaining insight into the broader impact of scientific research beyond the laboratory.
      </p>
    </div>
  </details>

</div>


<style>
/* 전체 폭 제한 */
.exp-container {
  max-width: 800px;
  margin: 0 auto;
}

  /* 카드 */
.exp-card {
  /* border: 1px solid #e5e5e5;
  border-radius: 10px;
  padding: 16px;
  margin-bottom: 18px; */
  background: #fafafa;
  transition: 0.2s;
}

.exp-card:hover {
  background: #f5f5f5;
}


/* 헤더 */
.exp-header {
  cursor: pointer;
  list-style: none;
}

.exp-header::-webkit-details-marker {
  display: none;
}

/* 제목 */
.exp-title {
  font-size: 20px;
  font-weight: 600;
}

/* 한 줄 요약 */
/*
.exp-info {
  font-size:16px;
  color: #600;
}
*/

.exp-summary {
  font-size:16px;
  color: #666;
}

/* 열렸을 때 간격 */
.exp-card[open] .exp-header {
  margin-bottom: 10px;
}

/* 본문 */
.exp-body {
  font-size: 16px;
  color: #444;
  line-height: 1.6;
}

/* 섹션 제목 */
.exp-section-title {
  font-weight: 600;
  margin-top: 10px;
  color: #111;
}

/* Research vs Professional 구분 */
.research {
  border-left: 4px solid #ddd;
}

.professional {
  border-left: 4px solid #bbb;
}

/* 제목 스타일 */
h2 {
  font-size: 22px;
  font-weight: 600;
  margin-bottom: 12px;
}
</style>
