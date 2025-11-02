---
layout: single
title: "Home"
author_profile: true
sidebar:
  nav: "main"
---

<style>
/* Tooltip styles */
span[style*='position: relative'] span + span {
  visibility: hidden;
  background-color: black;
  color: white;
  text-align: center;
  border-radius: 6px;
  padding: 6px;
  position: absolute;
  z-index: 1;
  bottom: 125%;
  left: 50%;
  transform: translateX(-50%);
  white-space: nowrap;
  opacity: 0;
  transition: opacity 0.3s;
}

/* Video container */
.video-container {
  display: flex;
  justify-content: center;
  margin: 20px auto;
  max-width: 560px; /* limits width */
  width: 90%; /* makes it responsive */
}

.video-container iframe {
  width: 100%;
  aspect-ratio: 16 / 9; /* maintains correct proportions */
  border-radius: 8px;
  border: none;
}
</style>

This is the homepage of Keshav Karumbunathan, a sophomore from Portland, Oregon who is interested in mathematics, computer science, quantum computing, and more. Feel free to check out different tabs on my website to learn more about me, my mathematical accomplishments, my research & studies, and organizations I am part of. 

I am reachable on <span style="position: relative; cursor: help;">
  <span style="text-decoration: underline dotted;">Discord,</span>
  <span>username: ke5hav</span>
</span><span style="position: relative; cursor: help;">
  <span style="text-decoration: underline dotted;">E-mail,</span>
  <span>home account: keshavkarumbu0@gmail.com, school account: kkarumb28@jesuitmail.org</span>
</span><span style="position: relative; cursor: help;">
  <span style="text-decoration: underline dotted;">Instagram,</span>
  <span>username: kayshavk</span>
</span>and <span style="position: relative; cursor: help;">
  <span style="text-decoration: underline dotted;">AoPS.</span>
  <span>username: CrunchyCucumber</span>
</span> Every day I try to live by these inspirational words (which are on a poster next to my bed):

> "It's a constant quest to try to be better today than you were yesterday and better tomorrow than you were the day before." — Kobe Bryant

Somewhat unrelated, but my favorite mathematical concept is the (unsolved) problem of how the digits of $\pi$ are related to colliding blocks of different masses. The problem and solution are well-described by the YouTube channel 3Blue1Brown in the video below.

<div class="video-container">
  <iframe 
    src="https://www.youtube.com/embed/6dTyOl1fmDo?si=SzuU6gW4dZN6RoPx" 
    title="YouTube video player" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    referrerpolicy="strict-origin-when-cross-origin" 
    allowfullscreen>
  </iframe>
</div>

<script>
  document.querySelectorAll("span[style*='position: relative']").forEach(el => {
    const tooltip = el.querySelector("span + span");
    el.addEventListener("mouseover", () => {
      tooltip.style.visibility = "visible";
      tooltip.style.opacity = "1";
    });
    el.addEventListener("mouseout", () => {
      tooltip.style.visibility = "hidden";
      tooltip.style.opacity = "0";
    });
  });
</script>
