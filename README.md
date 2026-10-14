<a href="https://cs.nyu.edu/ms-cei/index.html" title="MS-CEI at NYU"><img align="right" src="https://yt3.ggpht.com/-RZYi5isxH_M/AAAAAAAAAAI/AAAAAAAAAAA/rmWpoe2qZzI/s900-c-k-no/photo.jpg" width="100px"/></a>

### Hello there! <img src="https://raw.githubusercontent.com/iampavangandhi/iampavangandhi/master/gifs/Hi.gif" width="30px">

# I'm Dhruv Shetty

Founding engineer at **TrueMark**. Empowering educators to foster critical thinking with AI.

I'm the only engineer on the team. I joined when 2 teachers were using the product. Two years later it's **2,300+ teachers** and **45,000+ students** across **229 schools**.

<br>

<a href="https://truemark.ai" title="TrueMark"><img align="left" src="truemark.png" width="80px"/></a>

**What I've built at TrueMark**

- The student writing editor, on TipTap and ProseMirror, with a pagination engine that lays essays out as real pages while students type: editable headers, page numbers, footnotes that stay on their page. Started from an open-source extension and outgrew it; TipTap shipped its own Pages extension 6 months later. 130,000+ essays run through it.
- AI grading and feedback: rubric parsing, per-criterion feedback, and a Socratic tutor that guides instead of answering. Evals on production traces (Langfuse) gate every prompt change. One teacher complaint that the tutor "writes for students" became a measured 13% vs 5.5% in 2 days, then a fix.
- Moved rubric parsing from gpt-4o to Gemini at ~65x lower cost, against an eval baseline so quality didn't slip.
- Integrations for 7 LMS platforms (Canvas, Schoology, Google Classroom, Microsoft Teams, Blackbaud, ManageBac, Genius SIS): SSO, rostering, grade sync.
- Split submit from grading: submit enqueues a Cloud Tasks job, Cloud Run workers generate the report. Load-tested to 5,000 concurrent students. On one district's benchmark day: 4,338 essays, 44 submits a minute at peak, 0 failures a student could see.

Full write-ups: [dhruvshetty.com/work/truemark](https://dhruvshetty.com/work/truemark)

<br>

<a href="https://pyramiddeveloper.com/" title="Pyramid Developers"><img align="left" src="WhiteLogoTransparent.png" width="80px"/></a>

**Before TrueMark**

- **Snacc**: co-founded an AI calorie tracker (Flutter, OpenAI vision). Beta in 2 months, ~1,000 users, $30k raised.
- **Pyramid Developers**: founded and ran a studio of up to 30 engineers for 5 years, 40+ products for startups.
- **Maigrate**: no-code RAG chatbot builder, embeddable with one script tag, on AWS ECS.
- **NYU**: MS in Computing, Entrepreneurship and Innovation. TA for DevOps and Agile. 2nd place in Yann LeCun's deep learning class challenge with WNet, a dual-UNet video segmentation model.

<br>

## 🛠 Tech Stack

#### Languages
<img alt="Python" src="https://img.shields.io/badge/Python-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white"/>  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-%23007ACC.svg?&style=for-the-badge&logo=typescript&logoColor=white"/>  <img alt="Dart" src="https://img.shields.io/badge/Dart-%230175C2.svg?&style=for-the-badge&logo=dart&logoColor=white"/>  <img alt="SQL" src="https://img.shields.io/badge/SQL-%23025E8C.svg?&style=for-the-badge&logo=postgresql&logoColor=white"/>

#### Frontend
<img alt="React" src="https://img.shields.io/badge/React-%2320232a.svg?&style=for-the-badge&logo=react&logoColor=white"/>  <img alt="Next.js" src="https://img.shields.io/badge/Next%2Ejs-%23000000.svg?&style=for-the-badge&logo=nextdotjs&logoColor=white"/>  <img alt="Flutter" src="https://img.shields.io/badge/Flutter-%2302569B.svg?&style=for-the-badge&logo=flutter&logoColor=white"/>  <img alt="TipTap" src="https://img.shields.io/badge/TipTap-%23000000.svg?&style=for-the-badge&logo=&logoColor=white"/>

#### Backend
<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-%23009688.svg?&style=for-the-badge&logo=fastapi&logoColor=white"/>  <img alt="Django" src="https://img.shields.io/badge/Django-%23092E20.svg?&style=for-the-badge&logo=django&logoColor=white"/>  <img alt="Node.js" src="https://img.shields.io/badge/Node%2Ejs-%2343853D.svg?&style=for-the-badge&logo=nodedotjs&logoColor=white"/>  <img alt="Firebase" src="https://img.shields.io/badge/Firebase-%23FFCA28.svg?&style=for-the-badge&logo=firebase&logoColor=white"/>

#### Cloud
<img alt="Google Cloud" src="https://img.shields.io/badge/Google%20Cloud-%234285F4.svg?&style=for-the-badge&logo=googlecloud&logoColor=white"/>  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-%23326CE5.svg?&style=for-the-badge&logo=kubernetes&logoColor=white"/>  <img alt="Docker" src="https://img.shields.io/badge/Docker-%232496ED.svg?&style=for-the-badge&logo=docker&logoColor=white"/>  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-%232088FF.svg?&style=for-the-badge&logo=githubactions&logoColor=white"/>

#### AI
<img alt="Gemini" src="https://img.shields.io/badge/Gemini-%238E75B2.svg?&style=for-the-badge&logo=googlegemini&logoColor=white"/>  <img alt="Claude" src="https://img.shields.io/badge/Claude-%23D97757.svg?&style=for-the-badge&logo=claude&logoColor=white"/>  <img alt="OpenAI" src="https://img.shields.io/badge/OpenAI-%23412991.svg?&style=for-the-badge&logo=openai&logoColor=white"/>  <img alt="Langfuse" src="https://img.shields.io/badge/Langfuse-%23000000.svg?&style=for-the-badge&logo=&logoColor=white"/>

#### Observability
<img alt="Sentry" src="https://img.shields.io/badge/Sentry-%23362D59.svg?&style=for-the-badge&logo=sentry&logoColor=white"/>  <img alt="PostHog" src="https://img.shields.io/badge/PostHog-%231D4AFF.svg?&style=for-the-badge&logo=posthog&logoColor=white"/>  <img alt="Prometheus" src="https://img.shields.io/badge/Prometheus-%23E6522C.svg?&style=for-the-badge&logo=prometheus&logoColor=white"/>  <img alt="Playwright" src="https://img.shields.io/badge/Playwright-%232EAD33.svg?&style=for-the-badge&logo=playwright&logoColor=white"/>

## 🎲 Things I built for myself

- [DKS Sports Day '27](https://27.dhruvshetty.com): my 27th birthday as a 6-a-side tournament. Teams, check-in, a 15-minute fixture grid, live scores, and a schedule that rebuilds itself if a venue falls through.
- [apt-search](https://dhruvshetty.com/apt-search/): built at a 6-person hackathon I hosted. Ranks NYC rentals in our zone by $/person and pings Discord when a new one appears.
- [We're Not Really Strangers](https://wnrs.dhruvshetty.com): the card game as a website, so it's always in the room.
- [Statement-Analyzer](https://github.com/Some1Somewhere/Statement-Analyzer): Gemini reads credit-card PDF statements, categorises every line, merges Splitwise, writes one CSV.

<br>

**Reach me:**
<p>
<a href="https://dhruvshetty.com"><img alt="Website" src="https://img.shields.io/badge/dhruvshetty.com-%23000000.svg?&style=for-the-badge&logo=googlechrome&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/dhruv-k-shetty/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:dhruvshetty.business@gmail.com?subject=From your GitHub profile"><img alt="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>
<hr>

[![trophy](https://github-profile-trophy.vercel.app/?username=Some1Somewhere&column=4&margin-w=15&margin-h=15&rank=SSS,SS,S,AAA,AA,A,B,C)](https://github.com/ryo-ma/github-profile-trophy)

![Dhruv Shetty's GitHub stats](https://github-readme-stats.vercel.app/api?username=Some1Somewhere&count_private=true&theme=tokyonight&show_icons=true)
[![GitHub Streak](https://streak-stats.demolab.com/?user=Some1Somewhere&theme=tokyonight)](https://github.com/DenverCoder1/github-readme-streak-stats)
