---
layout: page
title: Essays
subtitle: Here are some essays I wrote in an Ethics in Computer Science course at Michigan State University (CSE 300). Give them a read if they interest you!
---

<section id="hft-essay" style="padding: 2rem 1rem; text-align: center;">
  <!-- Topic image -->
  <img src="/assets/img/HFT.jpg" alt="High-Frequency Trading illustration" style="display: block; margin: 0 auto 1rem; width:100%; max-width:600px; border-radius:8px;" />
  <h2>📌 High-Frequency Trading: Ethical Concerns</h2>
  <p>This essay explores how modern financial technologies like high-frequency trading can raise serious ethical concerns for fairness, transparency, and public trust in markets.</p>
  <div id="essay1-container" style="position: relative; max-height: 300px; overflow: hidden; border-radius: 8px; background: #f9f9f9; padding: 1rem;">
    <div id="essay1-preview">
      <p>Whether you are a young college student who just began contributing to their retirement account or a 72-year-old who has been investing his whole life, you probably have been negatively affected by the efforts of Wall Street insiders squeezing ordinary people for their own financial gain. Financial institutions like investment banks and hedge funds have been known to engage in malpractice leading to market manipulation. One of the most impactful examples of blatant deceit and fraud was the 2008 financial crisis where banks and credit rating agencies hid risks from investors. The disastrous aftermath that followed included U.S. households losing over $16 trillion in net worth, the value of the stock market being cut in half, and thousands of jobs lost (Gratton, 2024). Global crises like the 2008 crash expose the deeply troubling ethical failures of financial giants and show how they have the ability to destabilize economies and harm millions of lives. Nowadays, the biggest players in finance are employing a more modern approach of breaching ethical guidelines for monetary gain through a strategy called high-frequency trading (HFT).</p>
    </div>
    <div id="essay1-overlay" style="position: absolute; bottom: 0; width: 100%; height: 60px; background: linear-gradient(to top, white, transparent);"></div>
  </div>
  <button id="essay1-btn" onclick="toggleEssay('essay1')" style="margin-top: 1rem;" class="btn">Show More</button>
</section>

<hr />

<section id="data-leak-essay" style="padding: 2rem 1rem; text-align: center;">
  <!-- Topic image -->
  <img src="/assets/img/dataleak.jpeg" alt="Bangladesh data leak illustration" style="display: block; margin: 0 auto 1rem; width:100%; max-width:600px; border-radius:8px;" />
  <h2>🛡️ Data Ethics: The Bangladesh Data Leak</h2>
  <p>This piece analyzes the 2023 Bangladeshi government data leak through the lens of professional ethics in data science.</p>
  <div id="essay2-container" style="position: relative; max-height: 300px; overflow: hidden; border-radius: 8px; background: #f9f9f9; padding: 1rem;">
    <div id="essay2-preview">
      <p>Imagine a game of soccer, only this game is special because it doesn’t have any rules. Players could play the game however they want to with the only objective of getting the ball in the opposing team’s goal. What would happen under these circumstances? The short answer is, there would be no order. If there were no limitations as to how players could score a goal, there would be dangerous consequences...</p>
    </div>
    <div id="essay2-overlay" style="position: absolute; bottom: 0; width: 100%; height: 60px; background: linear-gradient(to top, white, transparent);"></div>
  </div>
  <button id="essay2-btn" onclick="toggleEssay('essay2')" style="margin-top: 1rem;" class="btn">Show More</button>
</section>

<script>
  function toggleEssay(id) {
    const container = document.getElementById(`${id}-container`);
    const preview = document.getElementById(`${id}-preview`);
    const overlay = document.getElementById(`${id}-overlay`);
    const btn = document.getElementById(`${id}-btn`);
    const isCollapsed = container.style.maxHeight === '300px';
    if (isCollapsed) {
      // expand to full
      container.style.maxHeight = 'none';
      container.style.overflow = 'visible';
      overlay.style.display = 'none';
      btn.textContent = 'Show Less';
    } else {
      // collapse back
      container.style.maxHeight = '300px';
      container.style.overflow = 'hidden';
      overlay.style.display = 'block';
      btn.textContent = 'Show More';
    }
  }
</script>
