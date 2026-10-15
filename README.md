# Aditya K. Koundinya: Portfolio

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/readme/01_hero_dark.svg">
  <img src="docs/readme/01_hero_light.svg" width="100%" alt="Aditya K. Koundinya, product portfolio: AI Product and Product Analytics. Computer Science graduate and NextLeap Product Management Fellow. I build AI products end to end: grounded in real sources, with guardrails in front of the model, and designed to stay quiet when the evidence is thin. Before that, I turned manufacturing data into decisions at Bosch. Open to Associate Product Manager, Product Analyst, AI Product, Product Operations, Business Analyst and Growth Analytics roles. The animation shows the six step product loop every project goes through: Problem, Users, Insights, Product, Metrics, Iteration. A loop, not a launch.">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/readme/02_fundbot_dark.svg">
  <img src="docs/readme/02_fundbot_light.svg" width="100%" alt="Featured AI product: FundBot, a mutual fund assistant that refuses to guess. A facts only FAQ assistant over four Mirae Asset schemes; every answer is short and carries the official source link and the date that source was last read. Pipeline: guardrails (PII, scope, advice) run first; hybrid BM25F and TF IDF retrieval over 47 curated documents; DeepSeek via OpenRouter only rephrases the retrieved passage; the answer carries the source and date. The model never supplies a fact. Release gate results against their floors: top 1 retrieval accuracy 92.7 percent (floor 85), top 3 retrieval accuracy 100 percent (floor 95), answered above the confidence floor 97.6 percent (floor 90), off topic rejected 100 percent (floor 100), competitor questions scoped out 100 percent (floor 100). The confidence floor 0.06 came from a threshold sweep, with zero false answers. CI runs the gate on every push alongside 111 unit tests.">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/readme/03_nykaafit_dark.svg">
  <img src="docs/readme/03_nykaafit_light.svg" width="100%" alt="Latest build, September 2026: Nykaa Fit, size guidance that declines to guess. A fashion storefront with a fit recommendation on the product page. It gives a size, shows its full working, and names no size when the evidence is too thin. Score equals completeness times (closeness times 0.5 plus separation times 0.5). Deterministic and offline: no model, no API call, no randomness. One profile (35, 29.5, 38.5, regular fit) against five brands' charts gives four different letters: Kazo Sequin Party Dress, slim, L, high; AND Belted Shirt Dress, regular, M, high; ONLY Puff Sleeve Dress, regular, M, high; W for Woman Tiered Midi, relaxed, S, high; Libas Anarkali Maxi, regular, S, medium. No confidence percentage is shown. Experiment: control is the existing product page, treatment adds Nykaa Fit, primary metric is product view to add to bag, with deterministic hash bucketing. Built with React 19, TypeScript, Vite 7 and Vitest on Vercel. Not affiliated with Nykaa; size charts are mock data.">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/readme/04_cases_dark.svg">
  <img src="docs/readme/04_cases_light.svg" width="100%" alt="More builds and case studies. AI Discovery Engine: collects reviews and comments from six public sources (Google Play, YouTube, Steam, GitHub Issues, Hacker News and RSS) and turns them into ranked pain points and opportunities. AI Grocery Shopping Assistant: AI constrained to the live catalog, deployed and publicly usable, with a FastAPI companion build. Wealth Coach AI: a planning tool for first time Indian investors, deployed on Streamlit Cloud. ChatGPT voice input growth strategy: from 30 plus surveyed users, 42 percent knew voice existed, 28 percent had tried it, 6 percent used it regularly; North Star target 6 to 25 percent weekly active voice users in three months. n8n onboarding teardown: the largest estimated drop, 27 points, sits between entering the dashboard and creating a first node. Engati and Canara Bank: a Day 0 pitch to Day 180 renewal business case with a six KPI scorecard agreed up front. Eureka by ALLEN: a localisation first fix to a monetisation timing problem. Funnel numbers in case studies are estimates or scenario assumptions.">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/readme/05_bosch_dark.svg">
  <img src="docs/readme/05_bosch_light.svg" width="100%" alt="Experience: Data Analyst Intern, Bosch Automotive Electronics, manufacturing digitalisation, June to December 2024. Three teams kept separate manual KPI reports for the same floor. I ran discovery with 8 plus line engineers and quality leads, then built unified Tableau dashboards with an automated Python ETL over Oracle SQL and HiveQL, and four reliability KPIs (MTTR, MTBF, technical availability, technical loss). Results: 3 teams adopted the dashboards within 3 weeks; about 85 percent less recurring manual reporting (about 10 hours a week, estimated); 15 plus machines across 5 production lines; contributed to an 18 percent reduction in unplanned downtime. Skills. Product: discovery, user research, PRDs, MVP scoping, RICE, roadmapping, North Star metrics, A/B experiments, teardowns. Data: SQL, Oracle SQL, HiveQL, Hadoop, Python and Pandas, ETL, Tableau, Power BI, KPI design. AI: LLM applications, RAG and retrieval, prompt engineering, evaluation, guardrails, embeddings, sentiment and theme analysis. Development: Git, REST APIs, FastAPI, Flask, Streamlit, React, Next.js, TypeScript, SQLite, Firestore, Docker, Pytest, Vitest, GitHub Actions. Education: B.Tech in Computer Science and Engineering, VIT Bhopal, 2021 to 2025; NextLeap Product Management Fellowship, Cohort 47.">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/readme/06_site_dark.svg">
  <img src="docs/readme/06_site_light.svg" width="100%" alt="About this repository: the portfolio is a single static page. No framework, no build step, no dependencies, no tracking. index.html is the whole site, with inline CSS and about 70 lines of vanilla JavaScript. assets holds the résumé PDF and the Open Graph image. assets/fonts holds self hosted Syne, Sora and DM Mono, so there is no third party font request. _redirects sends the legacy Netlify path to the home page, and .nojekyll tells GitHub Pages to serve assets as they are. Live at koundinya2003.github.io/Portfolio.">
</picture>

Product portfolio for **Aditya K. Koundinya**: AI Product and Product Analytics.

## Live

* https://koundinya2003.github.io/Portfolio/
* [Résumé (PDF)](assets/Aditya-K-Koundinya-Resume.pdf)
* [LinkedIn](https://www.linkedin.com/in/adityakkoundinya/) and [GitHub](https://github.com/Koundinya2003)

## Projects shown on the site

* [FundBot, mutual fund FAQ assistant](https://github.com/Koundinya2003/MF_FAQ_CB)
* [Nykaa Fit](https://github.com/Koundinya2003/nykaa-fit-mvp) ([live demo](https://nykaa-fit-mvp.vercel.app/), [fit profile](https://nykaa-fit-mvp.vercel.app/fit-profile))
* [AI Discovery Engine](https://github.com/Koundinya2003/AI-Discovery-Engine)
* [AI Grocery Shopping Assistant](https://github.com/Koundinya2003/Blinkit-Ai_assistantV1) ([live demo](https://blinkit-ai-assistantv1.vercel.app)) and its [FastAPI build](https://github.com/Koundinya2003/Shopping-Ai_assistant)
* [Wealth Coach AI](https://github.com/Koundinya2003/wealth-monitor-review-intelligence) ([live demo](https://wealth-monitor-review-intelligence-9oixsvognm4vryrrlagbta.streamlit.app/))
* [Engati and Canara Bank business case](https://github.com/Koundinya2003/Engati-Pitch-PRD)
* [ChatGPT voice input growth strategy](https://github.com/Koundinya2003/Prioritization-Metrics-Growth) ([live deck](https://gilded-mousse-b37ea5.netlify.app/))
* [n8n onboarding teardown](https://github.com/Koundinya2003/n8n-product-teardown)
* [Eureka by ALLEN teardown](https://github.com/Koundinya2003/Eureka_PRD)

## Stack

A single static page. No framework, no build step, no dependencies, no tracking.

```
index.html      the whole site (inline CSS and about 70 lines of vanilla JS)
assets/         résumé PDF, Open Graph image
assets/fonts/   self hosted Syne, Sora and DM Mono, so no third party font request
_redirects      Netlify: legacy /aditya_portfolio.html to /
.nojekyll       GitHub Pages: serve assets/ as is, skip Jekyll processing
docs/readme/    the panels on this page and the script that builds them
```

To run it locally, open `index.html` in a browser.

## Rebuilding the panels

The images at the top are panels from `docs/readme/one_sheet.html`, frozen into SVG with fonts embedded and CSS animations. Edit that page, then run:

```bash
node docs/readme/build_readme_svgs.js docs/readme/one_sheet.html docs/readme 960
```

This needs Node with Playwright and curl.
