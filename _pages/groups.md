---
permalink: /groups/
title: "Groups and Community Work"
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
    background: #7ea3c2;
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
    color: #007acc;
    cursor: pointer;
    padding: 4px 0;
    font-weight: bold;
    font-size: 0.9rem;
  }
</style>

<div class="org-container">

<div class="org-card">
  <img class="org-logo" src="https://www.oregonmathcircle.org/logo/OMCLOGO.png" alt="Oregon Math Circle Logo">
  <div class="org-content">
    <div class="org-title">Oregon Math Circle Co-Leader</div>
    <div class="org-description" id="desc-1">
      <p>We are an Oregon-wide math circle for high school students interested in math. We run weekly meetings, problem-of-the-days (computational and proof), annual contests, and also have an active and engaging Discord server. While our primary focus is on competition math, we also have a strong emphasis on non-competition topics and encourage students to explore all areas of mathematics. We are a student-run organization, and our leaders are dedicated to providing a fun and engaging environment for all students. Each year, we attend in-person competitions including the American Regional Mathematics League(ARML), the Harvard-MIT Math Tournament(HMMT), and the Stanford Math Tournanment(SMT). For more information about our math circle, you can go to <a href="https://www.oregonmathcircle.org" target="_blank">this link</a>. </p>
      <p>I have been a member of the math circle since 2022, and a leader of the math circle since 2024. I am involved in running meetings, sending out club information emails, and planning our trips. I also have been writing Problem of the Days for our club, which are free-access problems posted daily on our Discord server that model competition problems.</p>
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

<div class="org-card">
  <img class="org-logo" src="https://www.dolphinswimteam.org/osmjcc/team-logo/default/teamlogo-610-1368249799577_009622-t-thumb.jpg" alt="The Dolphins Logo">
  <div class="org-content">
    <div class="org-title">The Dolphins Portland Swimmer</div>
    <div class="org-description" id="desc-3">
    <p>The Dolphins Portland Swimming (TDPS) is a coach-owned club sanctioned by USA Swimming. The USA Swimming and Oregon Swimming, Inc. (OSI) organizations govern our club. TDPS has been serving Beaverton, OR, and surrounding communities for nineteen years, providing a year-round program for athletes. The club also provides a swim program in Gresham, OR. For more information, check out <a href="https://www.dolphinswimteam.org" target="_blank">this link</a>.</p>
    <p>I have been a member of the Dolphins swim team since 2015. I started swimming competitively in 2017, and since then, I have qualified for every OSI state short-course championship in multiple events. My latest accomplishment was getting a 10th place overall finish in the 100 yard backstroke finals at the state meet this March. I have been part of the Green Squad, the Dolphins highest level swimming group, since 2023.</p>
    </div>
    <button class="read-more-btn" onclick="toggleDescription('desc-3', this)">Read more</button>
  </div>
</div>

<div class="org-card">
  <img class="org-logo" src="https://i0.wp.com/troop728.com/wp-content/uploads/2024/10/WebBanner_728_5728.png?w=482&ssl=1" alt="Troop 728 and 5728 Logo">
  <div class="org-content">
    <div class="org-title">Troop 728 Life Scout</div>
    <div class="org-description" id="desc-4">
    <p>Troops 728 is part of the Scouting America in the Cascade Pacific Council. Our mission is to provide opportunities for young men to have a fun, challenging, supportive and exciting scouting experience. This is achieved through a balance of scouts who are active and enthusiastic, supported by parents who are involved and supportive, in a program that is boy led and outdoor focused. FOr more information, visit <a href="https://www.troop728.com" target="_blank">this link</a>.</p>
    <p>I have been a member of troop 728 since I joined during 2021. I have been actively participing in the troop throughout, spending over 50 nights camping. I have attended the National Youth Leadership Training(NYLT) and served as the Assistant Senior Patrol Leader(ASPL) during the 2025 summer term. I am currently a life scout, which is the second highest rank behind being an Eagle Scout.</p>
    </div>
    <button class="read-more-btn" onclick="toggleDescription('desc-4', this)">Read more</button>
  </div>
</div>

<script>
  function toggleDescription(id, btn) {
    const el = document.getElementById(id);
    el.classList.toggle('expanded');
    btn.textContent = el.classList.contains('expanded') ? 'Collapse' : 'Read more';
  }
</script>
