---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-container">

<h2 class="cv-section-title">01. Standard CV</h2>
<div class="text-center">
    <a href="/assets/documents/CV_Laetitia_Solombrino.pdf" class="btn btn--primary btn--large" target="_blank">
        <i class="fas fa-file-download"></i> Download CV (PDF)
    </a>
</div>

<hr style="margin: 3em 0;">

<h2 class="cv-section-title">02. Visual Journey</h2>
<div class="visual-cv">
    <div class="timeline">
        <div class="timeline-event">
            <div class="timeline-dot"></div>
            <div class="timeline-content">
                <span class="timeline-date">2019</span>
                <h3>Started B.F.A.</h3>
                <p>Park University, USA</p>
            </div>
        </div>
        <div class="timeline-event">
            <div class="timeline-dot"></div>
            <div class="timeline-content">
                <span class="timeline-date">2022</span>
                <h3>Freelance Design</h3>
                <p>"Ortszeit" Exhibition Identity</p>
            </div>
        </div>
        <div class="timeline-event">
            <div class="timeline-dot"></div>
            <div class="timeline-content">
                <span class="timeline-date">2023</span>
                <h3>Signs By Tomorrow</h3>
                <p>Project Management & Large Format</p>
            </div>
        </div>
        <div class="timeline-event">
            <div class="timeline-dot"></div>
            <div class="timeline-content">
                <span class="timeline-date">2025</span>
                <h3>M.Sc. UX Design</h3>
                <p>Technische Hochschule Ingolstadt</p>
            </div>
        </div>
    </div>
</div>

<hr style="margin: 3em 0;">

<h2 class="cv-section-title">03. Audio Intro</h2>
<div class="audio-cv">
    <div class="podcast-card">
        <div class="podcast-icon">
             <i class="fa-solid fa-microphone-lines"></i>
        </div>
        <div class="podcast-details">
            <h3>Designing with Empathy</h3>
            <p>A quick introduction to my design philosophy and background.</p>
            <audio controls>
                <source src="#" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
        </div>
    </div>
</div>

</div>

<style>
/* Local styles for CV specifics, moving to SCSS recommended for production */
.cv-section-title {
    color: #2E8B57; /* Forest Green */
    border-bottom: 2px solid #d1d6da;
    padding-bottom: 0.5em;
    margin-bottom: 1.5em;
}

/* Visual CV Timeline */
.timeline {
    position: relative;
    padding-left: 20px;
    border-left: 2px solid #d1d6da;
    margin-left: 10px;
}
.timeline-event {
    margin-bottom: 2em;
    position: relative;
}
.timeline-dot {
    width: 12px;
    height: 12px;
    background: #2E8B57;
    border-radius: 50%;
    position: absolute;
    left: -27px;
    top: 5px;
    box-shadow: 0 0 0 4px #E8EEF2;
}
.timeline-date {
    font-weight: bold;
    color: #607D8B;
    font-size: 0.9em;
}

/* Audio CV */
.podcast-card {
    display: flex;
    align-items: center;
    gap: 1.5em;
    background: #fff;
    padding: 1.5em;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
    border: 1px solid #d1d6da;
}
.podcast-icon {
    font-size: 2.5em;
    color: #2E8B57;
}
.podcast-details h3 {
    margin-top: 0;
    color: #607D8B;
}
audio {
    width: 100%;
    margin-top: 0.5em;
}
</style>
