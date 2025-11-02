---
permalink: /camps/
title: "Camps and Programs"
author_profile: true
sidebar:
  nav: "main"
classes: wide
---
<style>
  .org-container {
    display: flex;
    flex-direction: column;
    gap: 20px;
    width: 100%;
    max-width: none;
    margin: 0 auto;
  }

  .org-card {
    display: flex;
    border: 1px solid #ddd;
    border-radius: 12px;
    padding: 16px;
    background: #266e30;
    box-shadow: 0 2px 5px rgba(0,0,0,0.08);
    align-items: flex-start;
    position: relative;
  }

  .org-logo {
    width: 80px;
    height: 80px;
    border-radius: 50%;
    object-fit: cover;
    margin-right: 16px;
  }

  .org-content {
    font-size: 0.75rem;
    flex: 1;
  }

  .org-title {
    font-size: 1.2rem;
    font-weight: bold;
    margin-bottom: 8px;
  }

  .org-description {
    max-height: 100px;
    overflow: hidden;
    transition: max-height 0.3s ease;
    position: relative;
  }

  .org-description.expanded {
    max-height: 1000px;
  }

  .read-more-btn {
    background: none;
    border: none;
    color: #083820;
    cursor: pointer;
    padding: 4px 0;
    font-weight: bold;
    font-size: 0.9rem;
  }
</style>

<div class="org-card">
  <img class="org-logo" src="https://cdn.discordapp.com/icons/1361181397762572340/b068cc98d0d7f4fd2447c214f6aa80fb.png?size=64" alt="MOP Logo">
  <div class="org-content">
    <div class="org-title">Mathematical Olympiad Summer Program (MOP) Participant</div>
    <div class="org-description" id="desc-1">
    <p>The Mathematical Olympiad Program (MOP), formerly called the Mathematical Olympiad Summer Program (MOSP), is an intensive summer program sponsored by the Mathematical Association of America. The main purpose of MOP, held since 1974, is to select and train the six members of the U.S. team for the International Mathematical Olympiad (IMO).</p>
    <p>I qualified for the Green group at MOP by scoring a 28 on the USA Math olympiad, earning a silver medal. At MOP, I earned a silver medal on the ELMO contest for first-time participants, went through hours of rigorous math training courses on a daily basis, and took mock olympiads almost every other day.</p>
    </div>
    <button class="read-more-btn" onclick="toggleDescription('desc-1', this)">Read more</button>
  </div>
</div>

<div class="org-card">
  <img class="org-logo" src="https://mathquantum.umd.edu/media/logo_hufe77ac44593b2476901cdeb3aa4f9e3d_30646_0x70_resize_lanczos_3.png" alt="MathQuantum Logo">
  <div class="org-content">
    <div class="org-title">MathQuantum RTG High School Fellow</div>
    <div class="org-description" id="desc-2">
    <p>MathQuantum is a Research Training Group (RTG) focused on enabling Mathematicians to enter the world of Quantum Information Science (QIS). We are housed at IPST and funded by NSF. With MathQuantum, we are building an educational program that will blend with collaborative research, such that education and research enhance each other in a vertically integrated training group. The research draws from a set of Mathematical areas where our faculty have expertise, and advance these by tackling QIS challenges under three themes. High school fellowships are offered during summer to about 10 students, who will participate together as a cohort. Fellowships consist of a ~2-week online program of math and quantum information science lectures, seminars, professional development workshops, hands-on activities, discussions, and a mini-project. For more information, check out <a href="https://mathquantum.umd.edu/" target="_blank">this link</a>.</p>
    <p>I joined as part of the 2025 High School Fellowship cohort. Through MathQuantum, I have had mentored research, coursework, and seminars in applying mathematics to QIS problems. I also have access to internship opportunities at quantum companies & labs, various outreach activities, and networking opportunities.</p>
    </div>
    <button class="read-more-btn" onclick="toggleDescription('desc-2', this)">Read more</button>
  </div>
</div>


<script>
  function toggleDescription(id, btn) {
    const el = document.getElementById(id);
    el.classList.toggle('expanded');
    btn.textContent = el.classList.contains('expanded') ? 'Collapse' : 'Read more';
  }
</script>
