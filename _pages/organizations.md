---
permalink: /organizations/
title: "Organizations and Community Work"
---
<style>
  .org-container {
    display: flex;
    flex-direction: column;
    gap: 20px;
    max-width: 75%;
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
  <img class="org-logo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4a/Commons-logo.svg/1024px-Commons-logo.svg.png" alt="Math Club Logo">
  <div class="org-content">
    <div class="org-title">Math Club</div>
    <div class="org-description" id="desc-1">
      Math Club meets weekly to explore mathematical ideas and solve complex problems. We participate in competitions, offer tutoring, and promote fun through problem-solving challenges. Events include Pi Day, speaker series, and student-led tutorials. At the end of each semester, we host a “Mathlympics” open to all students.
    </div>
    <button class="read-more-btn" onclick="toggleDescription('desc-1', this)">Read more</button>
  </div>
</div>

<div class="org-card">
  <img class="org-logo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0b/Red_Cross_logo.svg/1024px-Red_Cross_logo.svg.png" alt="Red Cross Logo">
  <div class="org-content">
    <div class="org-title">Red Cross Club</div>
    <div class="org-description" id="desc-2">
      Red Cross Club is dedicated to humanitarian aid, disaster relief, and community service. We organize blood drives, earthquake preparedness workshops, and fundraisers. Members gain volunteer hours and hands-on leadership experience while contributing to real-world causes.
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
