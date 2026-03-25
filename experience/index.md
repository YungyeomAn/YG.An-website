---
title: Experience
nav:
  order: 2
  tooltip: Research & professional experiences
---

# {% include icon.html icon="fa-solid fa-microscope" %}Experience

See my work & research experiences.

## Professional Experience


## Research Experience

<div class="exp-item">
  <div class="exp-header" onclick="toggleExp(this)">
    <strong>Lab A, XXX University (3 months)</strong><br>
    <span class="exp-summary">
      Polymer thin film deposition via iCVD; analyzed interfacial adhesion
    </span>
    <span class="exp-toggle">[+]</span>
  </div>

  <div class="exp-details">
    <p><strong>Problem</strong><br>
    Understanding adhesion behavior in polymer thin films</p>

    <p><strong>Approach</strong><br>
    Deposited films via iCVD and analyzed interfacial interactions</p>

    <p><strong>Insight</strong><br>
    Identified key parameters governing adhesion under varying conditions</p>
  </div>
</div>


<div class="exp-item">
  <div class="exp-header" onclick="toggleExp(this)">
    <strong>Lab B, XXX Institute (4 months)</strong><br>
    <span class="exp-summary">
      Designed physically crosslinked hydrogel networks for adaptive adhesion
    </span>
    <span class="exp-toggle">[+]</span>
  </div>

  <div class="exp-details">
    <p><strong>Problem</strong><br>
    Designing hydrogels with both adhesion and flexibility</p>

    <p><strong>Approach</strong><br>
    Developed physically crosslinked polymer networks</p>

    <p><strong>Insight</strong><br>
    Revealed relationship between network structure and adhesion behavior</p>
  </div>
</div>


<div class="exp-item">
  <div class="exp-header" onclick="toggleExp(this)">
    <strong>Ministry of Science and ICT (Intern, 2026–Present)</strong><br>
    <span class="exp-summary">
      Exploring science policy and research–application interface
    </span>
    <span class="exp-toggle">[+]</span>
  </div>

  <div class="exp-details">
    <p><strong>Context</strong><br>
    Science & technology policy environment</p>

    <p><strong>Focus</strong><br>
    Examining how research translates into real-world applications</p>

    <p><strong>Perspective</strong><br>
    Gaining insight into the broader impact of scientific research</p>
  </div>
</div>

<!-- CSS -->
<style>
.exp-item {
  margin-bottom: 25px;
}

.exp-header {
  cursor: pointer;
  position: relative;
}

.exp-summary {
  color: #555;
}

.exp-toggle {
  position: absolute;
  right: 0;
  top: 0;
  color: #888;
}

.exp-details {
  display: none;
  margin-top: 10px;
  padding-left: 10px;
  border-left: 2px solid #ddd;
}

.exp-details p {
  margin: 5px 0;
}
</style>

<style>
.exp-item {
  margin-bottom: 25px;
}

.exp-header {
  cursor: pointer;
  position: relative;
}

.exp-summary {
  color: #555;
}

.exp-toggle {
  position: absolute;
  right: 0;
  top: 0;
  color: #888;
}

.exp-details {
  display: none;
  margin-top: 10px;
  padding-left: 10px;
  border-left: 2px solid #ddd;
}

.exp-details p {
  margin: 5px 0;
}
</style>

<!--Javascript-->
<script>
function toggleExp(element) {
  const details = element.nextElementSibling;
  const toggle = element.querySelector(".exp-toggle");

  if (details.style.display === "block") {
    details.style.display = "none";
    toggle.textContent = "[+]";
  } else {
    details.style.display = "block";
    toggle.textContent = "[-]";
  }
}
</script>

## Highlighted

{% include citation.html lookup="Open collaborative writing with Manubot" style="rich" %}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

