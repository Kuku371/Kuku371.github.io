---
layout: single
title: "Home"
author_profile: true
sidebar:
  nav: "main"
classes: wide
---

This is the homepage of Keshav Karumbunathan, a sophomore from Portland, Oregon who is interested in mathematics, computer science, quantum computing, and more. Feel free to check out different tabs on my website to learn more about me, my mathematical accomplishments, my research & studies, and organizations I am part of. I am reachable as <span style="position: relative; cursor: help;">
  <span style="text-decoration: underline dotted;">group theory</span>
  <span style="
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
  ">
    A field of abstract algebra studying algebraic structures called groups.
  </span>
</span>

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
