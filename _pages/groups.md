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
  <img class="org-logo" src="https://www.dolphinswimteam.org/osmjcc/team-logo/default/teamlogo-610-1368249799577_009622-t-thumb.jpg" alt="The Dolphins Logo">
  <div class="org-content">
    <div class="org-title">The Dolphins Portland Swimmer</div>
    <div class="org-description" id="desc-2">
    <p>The Dolphins Portland Swimming (TDPS) is a coach-owned club sanctioned by USA Swimming. The USA Swimming and Oregon Swimming, Inc. (OSI) organizations govern our club. TDPS has been serving Beaverton, OR, and surrounding communities for nineteen years, providing a year-round program for athletes. The club also provides a swim program in Gresham, OR. For more information, check out <a href="https://www.dolphinswimteam.org" target="_blank">this link</a>.</p>
      <p>I have been a member of the Dolphins swim team since 2015. I started swimming competitively in 2017, and since then, I have qualified for every OSI state short-course championship in multiple events. My latest accomplishment was getting a 10th place overall finish in the 100 yard backstroke finals at the state meet this March. I have been part of the Green Squad, the Dolphins highest level swimming group, since 2023.</p>
    </div>
    <button class="read-more-btn" onclick="toggleDescription('desc-2', this)">Read more</button>
  </div>
</div>

</div>

<script>
  function toggleDescription(id, btn) {
    const el = document.getElementById(id);
    el.classList.toggle('expanded');
    btn.textContent = el.classList.contains('expanded') ? 'Collapse' : 'Read more';
  }
</script>
