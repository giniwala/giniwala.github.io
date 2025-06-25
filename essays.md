---
layout: page
title: Essays
subtitle: Here are some essays I wrote in an Ethics in Computer Science course at Michigan State University (CSE 300). Give them a read if they interest you!
---

<section id="hft-essay" style="padding: 2rem 1rem;">
  <img src="/assets/img/HFT.jpg" alt="High-Frequency Trading illustration" style="display: block; margin: 0 auto 1rem; width:100%; max-width:600px; border-radius:8px;" />
  <h2>📌 High-Frequency Trading: Ethical Concerns</h2>
  <p>This essay explores how modern financial technologies like high-frequency trading can raise serious ethical concerns for fairness, transparency, and public trust in markets.</p>
  <div id="essay1-container" style="position: relative; max-height: 300px; overflow: hidden; border-radius: 8px; background: #f9f9f9; padding: 1rem; text-align: left;">
    <p>Whether you are a young college student who just began contributing to their retirement account or a 72-year-old who has been investing his whole life, you probably have been negatively affected by the efforts of Wall Street insiders squeezing ordinary people for their own financial gain. Financial institutions like investment banks and hedge funds have been known to engage in malpractice leading to market manipulation. One of the most impactful examples of blatant deceit and fraud was the 2008 financial crisis where banks and credit rating agencies hid risks from investors. The disastrous aftermath that followed included U.S. households losing over $16 trillion in net worth, the value of the stock market being cut in half, and thousands of jobs lost (Gratton, 2024). Global crises like the 2008 crash expose the deeply troubling ethical failures of financial giants and show how they have the ability to destabilize economies and harm millions of lives. Nowadays, the biggest players in finance are employing a more modern approach of breaching ethical guidelines for monetary gain through a strategy called high-frequency trading (HFT).</p>
    <p>High-frequency trading is a subset of quantitative finance, requiring in-depth math, statistics, and programming knowledge to predict financial markets. In short, HFT is the method of computerized buying and selling of assets in high volumes for small profits through lightning-fast connections to financial exchanges. Originally an unpopular strategy in the stock market, HFT quickly grew in the early 2000s into the dominating force it is today. In U.S. equity markets like the New York Stock Exchange (NYSE), for example, HFT makes up more than 50% of trading volume (Gerig, 2013). At first glance, high-speed trading seems like a brilliant technological innovation, but a closer look at its impact on those left behind reveals ethical questions.</p>
    <p>Chicago Booth’s Eric Budish estimated that HFT firms typically earn $5 billion a year in net profits by capitalizing on advantages over other stock market participants (Maiello, 2021). The best way to illustrate this issue is by comparing it to a race where some cars are allowed to start seconds earlier than others, giving them an unfair advantage regardless of skill level. Similarly, HFT firms gain a head start by being both physically close to exchanges and making smarter trades based on the speed at which they receive data. Another comparison is with the invention of the calculator. After the calculator’s creation, any complex math problem could be solved in an instant whereas for people without calculators, the same problem would take hours or days. Unlike calculators, however, HFT is only available to certain investment firms, restricting regular individuals from reaping its financial benefits.</p>
    <p>This disadvantage was especially evident in a recent case where a major stock exchange provided undisclosed advantages to select high-speed trading firms. In 2024, the U.S.-based telecommunications group McKay Brothers filed a complaint with the Securities and Exchange Commission (SEC), accusing Nasdaq—the second-largest U.S. stock exchange—of secretly offering hollow-core fiber optic cables, which carry trading data quicker than standard counterparts, to select firms for $10,000 per month (Steer, 2025). By curating an unfair environment, Nasdaq chose a utilitarian approach that sacrificed traders’ trust to maximize shareholder benefit. Such events can reduce trading activity, weakening the economy. When major companies lose value due to reduced demand, jobs, goods, and services across the economy suffer (Liberto, 2023).</p>
    <p>In response, Nasdaq issued a public statement: “In close consultation with the regulator and our clients, Nasdaq has begun discontinuing the [high-speed trading] service.” Furthermore, the exchange launched an “Equalization Project” to ensure a level playing field for all customers using high-speed technology (Carter, 2025). While this restores equality for large firms, the retail investor still faces inherent disadvantages.</p>
    <div id="essay1-overlay" style="position: absolute; bottom: 0; width: 100%; height: 60px; background: linear-gradient(to top, white, transparent);"></div>
  </div>
  <button id="essay1-btn" onclick="toggleEssay('essay1')" style="margin-top: 1rem;" class="btn">Show More</button>
</section>

<hr />

<section id="data-leak-essay" style="padding: 2rem 1rem;">
  <img src="/assets/img/dataleak.jpeg" alt="Bangladesh data leak illustration" style="display: block; margin: 0 auto 1rem; width:100%; max-width:600px; border-radius:8px;" />
  <h2>🛡️ Data Ethics: The Bangladesh Data Leak</h2>
  <p>This piece analyzes the 2023 Bangladeshi government data leak through the lens of professional ethics in data science.</p>
  <div id="essay2-container" style="position: relative; max-height: 300px; overflow: hidden; border-radius: 8px; background: #f9f9f9; padding: 1rem; text-align: left;">
    <p>Imagine a game of soccer, only this game is special because it doesn’t have any rules. Players could play the game however they want to with the only objective of getting the ball in the opposing team’s goal. What would happen under these circumstances? The short answer is, there would be no order. If there were no limitations as to how players could score a goal, there would be dangerous consequences. Without a rule book to follow, players could make the game unplayable for everyone on the pitch. They could severely injure themselves or others, use their hands at any point, and completely dismantle the idea of what soccer is known as today. In comparison to this hypothetical game of soccer, a professional code of conduct is the backbone of a level and fair playing field. Whether it's medicine, academic research, sports, or anything involving multiple people, rules must be set for people to abide by. Trust needs to be established between parties, fairness must be enforced, and ethical conduct needs to be upheld, otherwise the world would operate in chaos. Similarly, the field of data science requires participants to follow a strict set of rules. These rules are referred to as the Data Science Code of Professional Conduct. This essay examines an incident from 2023 where the Bangladesh government inadvertently leaked personal data of over 50 million citizens.</p>
    <p>On June 27, 2023, Viktor Markopoulos, a cybersecurity consultant affiliated with Bit Crack Cyber Security, discovered a vulnerable Bangladeshi government website (Antoniuk, 2023). While searching Google for programming help, he unintentionally discovered the colossal data leak in a simple search result. The data included full names, addresses, phone numbers, and national ID numbers of millions of Bangladeshi citizens. Digging deeper into the government website, Markopoulos began tinkering with the Application Programming Interface (API) that led him to uncover the sensitive data. To illustrate how exactly Markopoulos found the leak, consider this analogy for an API. Imagine you sit down in a restaurant for lunch. You find a table and look at the menu for all the items you could order. When you find something you like, you would request the waiter for the specific food you are looking forward to eating. Similarly, an API is like a menu. Using an API, you can make requests to the application you are interacting with (the restaurant in this example) to receive some kind of desired response. When you order food at a restaurant, you don’t see the inner workings of how the food is prepared or what utensils they use, you simply place an order and receive your food. This is exactly how an API works. In this case, the API was like a broken menu, meaning it displayed too many options without checking if the person viewing the menu was allowed to see them in the first place. In an interview with technology news publication TechCrunch, Markopoulos said, “All I did was follow the instructions that the vulnerable API was telling me” (Raywood, 2023). According to Markopoulos, the API was returning an error that the word “register” in the URL should be a number instead of a word. By changing “register” to some number like 123456789, the website responded with a birth application of a random person including all private information (Raywood, 2023). Since Markopoulos could have been any regular internet user, the potential for the breached data to be misused was astronomical.</p>
    <p>Immediately after recognizing this issue, Markopoulos alerted the Bangladesh e-Government Computer Incident Response Team (CIRT). TechCrunch, in verifying the legitimacy of the leak, searched public government data sets comparing the leaked data, and in all cases, the information was accurate (TBS, 2023). Fortunately, the CIRT was able to conduct an exhaustive investigation, thoroughly examining all aspects of the vulnerability. In finding out if the data had been misused by any third party, Markopoulos searched dark web forums for any signs of related leaks, but came up empty-handed. However, months later in October, TechCrunch found that over 50 million National ID card holders’ personal information was available in the messaging application Telegram (The Daily Star, 2024). If obtained, a citizen’s national ID can be exploited for passport information, the buying or selling of land, and opening bank accounts (Dhanuka, 2023). On a more global scale, this story drew international media coverage. American news outlets like TechCrunch covered the incident extensively, sending a shockwave through the cybersecurity community. While it’s unknown how long the data had been accessible for, Markopoulos knew that it had been available from June 27 to July 9, 2023. Markopoulos estimated that over 50 million people’s data were involved in this data leak (Raywood, 2023). Changes to legislation following this incident were imminent. In September 2023, the Bangladeshi government released the Cyber Security Act (CSA) which was built on top of the preceding Digital Security Act (DSA) of 2018. However, the new law quickly faced public scrutiny for retaining many of the same provisions as the DSA, which, according to Taqbir Huda, Regional Researcher for South Asia at Amnesty International, “threaten and undermine the rights to freedom of expression, liberty, and privacy in Bangladesh” (Amnesty, 2023). Given the scale of this tragedy, examining the specific rules violated under the code of conduct can help prevent similar events in the future.</p>
    <p>According to the Data Science Code of Professional Conduct, confidential information is information that a data scientist creates or uses in working for a client. This includes information that is not generally available to the public. Private data like the information in the government leak fall under confidential information. The Data Science Code of Professional Conduct states under Rule 5(a) that, “The data scientist has a professional duty to protect all confidential information” (Data Science Association, 2025). Furthermore, Rule 5(f)(1) states that “A data scientist shall make reasonable efforts to prevent the inadvertent or unauthorized disclosure of [...] information relating to the representation of a client,” including not displaying confidential information in public places (Data Science Association, 2025). By allowing confidential information to be publicly accessible to anyone with an internet connection, the Bangladeshi government was in clear violation of Rule 5 under the Data Science Code of Professional Conduct.
    </p>
    <p>As aforementioned, legislative measures have been implemented to prevent similar incidents in the future. Nonetheless, it is important to know how to handle a cyber security crime if you ever come across one. The first cautionary measure you can take to protect yourself is keeping your software up to date. Also, it’s important to refrain from connecting to public Wi-Fi networks, but if you must connect to one, do not conduct any online transactions like online shopping. There are countless resources online about keeping yourself safe from cyber attacks, but if you find yourself to be a victim of cyber-enabled crime, visit ic3.gov to file a report with the Internet Crime Complaint Center (IC3) (FBI, 2025).
    </p>
    <p>Whether it’s as simple as a game of soccer or as complex as a government website hosting tens of millions of confidential citizen records, a strict code of conduct must be adhered to. As shown, the consequences of not playing by the rules can be instantaneous and detrimental. Despite reformative actions being taken under consideration, millions of Bangladeshi residents were harmed in one way or another due to the ethical breach of the Data Science Code of Professional Conduct. This incident was not just a failure of software, but a failure of responsibility. It is a true reminder that in the digital age, ethics is our only true firewall.
    </p>
  </div>
  <button id="essay2-btn" onclick="toggleEssay('essay2')" style="margin-top: 1rem;" class="btn">Show More</button>
</section>

<script>
  function toggleEssay(id) {
    const container = document.getElementById(`${id}-container`);
    const overlay = document.getElementById(`${id}-overlay`);
    const btn = document.getElementById(`${id}-btn`);
    const isCollapsed = container.style.maxHeight === '300px';
    if (isCollapsed) {
      container.style.maxHeight = 'none';
      container.style.overflow = 'visible';
      overlay.style.display = 'none';
      btn.textContent = 'Show Less';
    } else {
      container.style.maxHeight = '300px';
      container.style.overflow = 'hidden';
      overlay.style.display = 'block';
      btn.textContent = 'Show More';
    }
  }
</script>
  function toggleEssay(id) {
    const container = document.getElementById(`${id}-container`);
    const overlay = document.getElementById(`${id}-overlay`);
    const btn = document.getElementById(`${id}-btn`);
    const isCollapsed = container.style.maxHeight === '300px';
    if (isCollapsed) {
      container.style.maxHeight = 'none';
      container.style.overflow = 'visible';
      overlay.style.display = 'none';
      btn.textContent = 'Show Less';
    } else {
      container.style.maxHeight = '300px';
      container.style.overflow = 'hidden';
      overlay.style.display = 'block';
      btn.textContent = 'Show More';
    }
  }
</script>
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
