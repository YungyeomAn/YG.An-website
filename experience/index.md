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

<div class="experience-container">
  
  <!-- 왼쪽 탭 -->
  <div class="experience-tabs">
    <button class="tab active" onclick="openTab(event, 'lab1')">Lab A</button>
    <button class="tab" onclick="openTab(event, 'lab2')">Lab B</button>
    <button class="tab" onclick="openTab(event, 'lab3')">Lab C</button>
    <button class="tab" onclick="openTab(event, 'lab4')">Lab D</button>
    <button class="tab" onclick="openTab(event, 'lab5')">Lab E</button>
    <button class="tab" onclick="openTab(event, 'intern')">MSIT Intern</button>
  </div>

  <!-- 오른쪽 내용 -->
  <div class="experience-content">
    
    <div id="lab1" class="tab-content active">
      <h3>Lab A (3 months)</h3>
      <p>Polymer thin film deposition via iCVD; analyzed interfacial adhesion.</p>
    </div>

    <div id="lab2" class="tab-content">
      <h3>Lab B (4 months)</h3>
      <p>Designed physically crosslinked hydrogel networks for adaptive adhesion.</p>
    </div>

    <div id="lab3" class="tab-content">
      <h3>Lab C</h3>
      <p>Nanomaterial-based system for biomedical interface studies.</p>
    </div>

    <div id="lab4" class="tab-content">
      <h3>Lab D</h3>
      <p>Surface/interface engineering with polymer coatings.</p>
    </div>

    <div id="lab5" class="tab-content">
      <h3>Lab E</h3>
      <p>Functional thin film design and characterization.</p>
    </div>

    <div id="intern" class="tab-content">
      <h3>Ministry of Science and ICT (Intern, 2026–Present)</h3>
      <p>Exploring science policy and the interface between research and application.</p>
    </div>

  </div>
</div>

<script>
function openTab(evt, tabName) {
  const contents = document.getElementsByClassName("tab-content");
  const tabs = document.getElementsByClassName("tab");

  for (let i = 0; i < contents.length; i++) {
    contents[i].classList.remove("active");
  }

  for (let i = 0; i < tabs.length; i++) {
    tabs[i].classList.remove("active");
  }

  document.getElementById(tabName).classList.add("active");
  evt.currentTarget.classList.add("active");
}
</script>

## Highlighted

{% include citation.html lookup="Open collaborative writing with Manubot" style="rich" %}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

