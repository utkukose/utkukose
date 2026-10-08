<div align="center">
![Prof. Dr. Utku Köse: AI, XAI, Digital Twin](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=3B82F6&center=true&vCenter=true&multiline=true&width=700&height=80&lines=Prof.+Dr.+Utku+K%C3%B6se;AI+%7C+XAI+%7C+Digital+Twin)
Full Professor, Department of Computer Engineering, Süleyman Demirel University, Isparta, Türkiye<br>
Founding Director, AI Application and Research Center (YAZEM), Süleyman Demirel University<br>
Head of the Computer Science Division, Department of Computer Engineering, Süleyman Demirel University<br>
Additional affiliations: University of North Dakota (USA), Universidad Panamericana (Mexico City, Mexico), Vel Tech University (Chennai, India)<br>
IEEE Senior Member · ACM Professional Member · Associate Editor, IEEE Access
ORCID 0000-0002-9652-6415 | utkukose.com | github.com/utkukose
![Profile views](https://komarev.com/ghpvc/?username=utkukose&color=3b82f6&style=flat-square&label=Profile+Views)
![Last update](https://img.shields.io/badge/last%20update-October%202026-3b82f6?style=flat-square)
Research libraries · Open courseware · Simulators and demos · Research code · References
</div>
> [!NOTE]
> **Upcoming workshop, 28 October 2026:** *Explainable Artificial Intelligence in Medical Systems: From Black Box Models to Reliable Clinical Decision Support*. The workshop is part of [IEEE CARS 2026](https://ieee-cars.org/program/workshops/workshop-explainable-artificial-intelligence-in-m), organised by the Center for Cyber Security Research (C2SR) of the University of North Dakota in Grand Forks, ND, USA, and the session is online. The complete material is open in the [workshop repository](https://github.com/utkukose/xai-cars2026-NB-workshop), and the [XAI Lab](https://utkukose.github.io/xai-cars2026-NB-workshop/) runs in the browser.
---
About
Utku Köse is a Full Professor of Computer Engineering and an AI researcher. His work lies at the intersection of explainable AI (XAI), digital twins, interdisciplinary AI applications, AI in biomedical and healthcare settings, and decision support systems. He is the Principal Investigator of STING DSS (TÜBİTAK 1001, Project No. 123E383), a decision support system for drug repositioning in childhood acute lymphoblastic leukemia. He also develops two open-source Python libraries: GEMEX for the geometric explanation of machine learning models and PharmODE for the identification of PK/PD models.
His research interests cover explainable AI with geodesic and Riemannian information geometry methods, clinical decision support, drug repositioning and pediatric oncology. They extend to digital twins, deep learning architectures such as GNN, GAN and Bi-LSTM, and pharmacokinetic and pharmacodynamic modelling with ODEs and Neural ODEs. Further topics are adversarial machine learning, the security of cyber-physical systems, LLM safety and hallucination, edge AI, embedded systems and rehabilitation robotics. Recent repositories add work on the alignment of language models, machine ethics and agent-based simulation for policy analysis.
A large part of the repositories on this page is open courseware. Most courses are published with lecture pages, Colab notebooks and interactive labs that run in the browser, so that the material can be followed in class or studied independently.
<div align="center">
Publications	h-index	PyPI libraries	Open courses and workshops	Interactive simulators and demos
350+	43	2	10	9
</div>
---
Research libraries and clinical systems
The projects below are a clinical decision support platform and two Python libraries. GEMEX and PharmODE are available on PyPI.
```bash
pip install gemex pharmode
```
Project	Description	Links
STING DSS	Clinical decision support system for drug repositioning in childhood acute lymphoblastic leukemia (TÜBİTAK 1001, Project No. 123E383). The full-stack platform, built with FastAPI and React, joins Bi-LSTM drug repositioning, ODE-based PK/PD simulation, genetic algorithm dose optimisation, a GNN digital twin with XAI and GAN-based synthetic patient cohorts.	Overview<br>Project code<br>Project site
GEMEX	Geodesic Entropic Manifold Explainability: A model-agnostic XAI library grounded in Riemannian information geometry. It explains tabular, time series and image models by measuring the curved geometry of the prediction surface [1].	Repository<br>Playground<br>![PyPI](https://img.shields.io/pypi/v/gemex?label=PyPI&color=3775A9)
PharmODE	Automated PK/PD model identification from concentration and time data. One call runs non-compartmental analysis, structure identification over nine candidate ODE systems and parameter estimation with a classical, Bayesian or Neural ODE engine. Identifiability checks and validation then yield a single trust score.	Repository<br>![PyPI](https://img.shields.io/pypi/v/pharmode?label=PyPI&color=3775A9)
---
Open courseware
The courses and workshops below are open under the licences stated in each repository. Every course site runs on GitHub Pages and opens the lecture pages and the interactive labs directly.
Course or workshop	Host and format	Links
Artificial Intelligence Applications in Engineering<br>MUH-920	Süleyman Demirel University, undergraduate faculty-wide common elective designed in line with the MÜDEK accreditation system. The 14 weeks lead from agents, search and fuzzy logic to deep learning, language models and reinforcement learning, with a Python track for beginners.	Repository<br>Course site
Machine Ethics and Artificial Intelligence Safety<br>11118BLG001	Süleyman Demirel University, graduate, 14 weeks, asynchronous. Topics run from normative foundations and artificial moral agents through fairness, robustness and interpretability to language model alignment and security, advanced risks and governance.	Repository<br>Course site
Philosophy of Artificial Intelligence<br>11118BLG003	Süleyman Demirel University, graduate, 14 weeks, asynchronous. Classic arguments such as the Turing test, the Chinese Room and the symbol grounding problem become simulations and are tested against current language models.	Repository<br>Course site
R&D and Project Management in Computer Science<br>11117BLG002	Süleyman Demirel University, graduate, 14 weeks, asynchronous. The course covers research methods, funding programmes in Türkiye and worldwide, proposal writing and project planning with interactive tools.	Repository<br>Course site
Explainable Artificial Intelligence<br>VTR UGE 21	Vel Tech University, Chennai, India, value added course, 5 days. The course moves from interpretable models and model-agnostic methods to deep networks, the reliability of explanations and governance.	Repository<br>Course site
Digital Twin with Python<br>VTR UGE 21	Vel Tech University, Chennai, India, value added course, 5 days. One software twin of a 48 V lithium-ion battery pack is built step by step, from the simulation core and calibration to the intelligence layer and the dashboard.	Repository<br>Course site
Reinforcement Learning and Language Model Alignment<br>VTR UGE 21	Vel Tech University, Chennai, India, value added course, 5 days. One environment, TokenWorld, carries the week from Bellman equations and policy gradients to reward models and direct preference optimisation.	Repository<br>Course site
Digitalization, AI, and XAI: Strategies for the Transformation of the Healthcare Sector	Universidad Panamericana, Mexico City, Mexico, graduate. The 23 Jupyter notebooks in 6 modules cover more than 20 XAI methods, from glass-box models to fetal echocardiography.	Repository
Explainable Artificial Intelligence in Medical Systems<br>IEEE CARS 2026 workshop	IEEE CARS 2026, Grand Forks, ND, USA, organised by the Center for Cyber Security Research (C2SR) of the University of North Dakota. The 2-hour online session on 28 October 2026 uses 7 Colab notebooks, the browser-based XAI Lab and a Streamlit dashboard, all on real open datasets.	Repository<br>XAI Lab
Clinical Decision Support Systems with Generative AI<br>Lecture and workshop	Technology and Artificial Intelligence Literacy Training in Health Sciences, Akdeniz University, Antalya, Türkiye, 16 and 18 September 2026. The 6 workshop notebooks, each in English and Turkish, guide participants to a working prototype with generative AI tools.	Repository
---
Simulators and interactive demos
Most of the applications below run in the browser without installation, several of them as a single HTML file. Where a public address exists, the live version is linked next to the repository.
Project	Description	Links
MoGAIT	Single-file browser platform for rehabilitation robotics and gait analysis. It offers 19 scenarios and combines synthetic patient cohorts, scenario-adaptive and counterfactual XAI, robot device matching and cohort simulation. Developed for the AI Hackathon for People with Disabilities of the King Salman Center for Disability Research.	Repository<br>Live demo
Undergraduate Programmes AI Resilience Simulator	Simulation of 167 undergraduate programme groups in Türkiye under generative AI between 2026 and 2036. It reports a survival index with Monte Carlo uncertainty bands and exact Shapley contributions, and it includes a specialty module for medicine and dentistry.	Repository<br>Live demo (TR)<br>Live demo (EN)
Cyber Duel in Smart Infrastructures	Attack and defence simulation for adversarial machine learning in cyber-physical systems, with SHAP attribution and a digital twin topology layer. Eight scenarios are preloaded in a zero-dependency single HTML file. Presented in the Distinguished Webinar Series in AI and Cyber Security of the University of North Dakota on 27 March 2026.	Repository<br>Webinar recording
MoralLLM-Lab	Browser-only laboratory for probing the moral reasoning of large language models. It poses 15 dilemmas under 6 ethical framings, including Kantian and utilitarian ones, and works offline with 90 cached responses. The interface and the dilemmas are available in English and Turkish.	Repository
XAI Health Demo with Digital Twin	Interactive web application that demonstrates XAI and digital twin concepts on personal health risk analysis. Participants join by QR code, and each receives a risk report with factor attribution and an animated digital twin, in Turkish or English.	Repository
GEMEX Playground	GEMEX explanations in the browser through Pyodide, on medical datasets or an uploaded CSV file, with no installation.	Repository<br>Live demo
Digital Patient Simulator	Enhanced fork of The Computational Patient by Barbiero and Liò (2020). It adds an interactive body visualiser, a risk score, dose-response and sensitivity analyses and virtual cohort simulation on top of the unmodified original model.	Repository<br>Original project
TR-Wellness-Regulation-Sim	Regulatory impact analysis tool for the Wellness Services Regulation of Türkiye in the context of health tourism. Synthetic wellness centres and visitors are matched against rules transcribed from the regulation, and each case is classed as compliant, undefined or non-compliant [2]. The methods include rule-based inference, a Bayesian network learned from data, agent-based simulation and Monte Carlo repetitions. Joint work with Gamze Köse, mirrored from her main repository.	Mirror<br>Main repository<br>Live tool
HTM-ABM<br>Health Tourism Market with Agent-Based Modeling	Agent-based model of a medical tourism market. It asks whether such a market can recognise the true quality of its clinics or ends up rewarding visibility instead. Seven policy scenarios, including AI-assisted matching, load in a browser application in English and Turkish [3]. Joint work with Gamze Köse, documented here as a companion page of her canonical repository.	Companion page<br>Canonical repository<br>Live application
---
Research code and tools
The repositories below hold the companion code of published studies and one event management platform.
Project	Description	Links
Persona Vectors in Controlling Hallucination of LLMs	Companion code of the IEEE CARS 2025 paper on persona settings and hallucination in small LLMs, evaluated on TruthfulQA and the unanswerable subset of SQuAD v2 [4].	Repository
Synthetic Health Tourist Generator and Analyzer	Synthetic health tourist profiling from small data. A few-shot autoencoder and variational autoencoder pipeline generates profiles, a language model scores them, and PCA with KMeans maps the population [5]. Joint work with Gamze Köse.	Repository
ALEV	Adaptive Live Event Venue: A gamification and event management platform that runs hackathons and team events on Telegram, built with FastAPI, PostgreSQL and Docker.	Repository
---
Tech stack
<div align="center">
Languages and frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
AI, machine learning and XAI
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
Tools and platforms
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white)
</div>
---
GitHub activity
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api?username=utkukose&show_icons=true&theme=dark_github">
    <img alt="GitHub statistics of utkukose" height="165" src="https://github-stats-extended.vercel.app/api?username=utkukose&show_icons=true&theme=light_github">
  </picture>
  &nbsp;&nbsp;
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api/top-langs/?username=utkukose&layout=compact&langs_count=6&theme=dark_github">
    <img alt="Most used languages of utkukose" height="165" src="https://github-stats-extended.vercel.app/api/top-langs/?username=utkukose&layout=compact&langs_count=6&theme=light_github">
  </picture>
</p>
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=utkukose&theme=github-dark-blue&border=3d444d&stroke=3d444d">
    <img alt="GitHub contribution streak of utkukose" src="https://streak-stats.demolab.com?user=utkukose&theme=default&background=ffffff&border=d1d9e0&stroke=d1d9e0&ring=0969da&fire=0969da&currStreakLabel=0969da">
  </picture>
</p>
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/utkukose/utkukose/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/utkukose/utkukose/output/github-contribution-grid-snake.svg">
    <img alt="Snake animation over the GitHub contribution grid of utkukose" src="https://raw.githubusercontent.com/utkukose/utkukose/output/github-contribution-grid-snake.svg">
  </picture>
</p>
---
References cited on this page
[1] Kose, U. (2026). GEMEX: Model-agnostic XAI via geodesic entropic manifold analysis. In 8th International Congress on Human-Computer Interaction, Optimization and Robotic Applications (ICHORA 2026). IEEE. https://doi.org/10.1109/ICHORA69329.2026.11537244
[2] Köse, G., & Köse, U. (2026). Measuring uncertainty: An artificial intelligence assisted regulatory impact analysis of the Wellness Services Regulation and health tourism. INNOVAHEALTH 2026, 3rd International Congress on Innovative Approaches in Health Sciences, 2–5 September 2026, Kyrenia, TRNC.
[3] Köse, G., & Köse, U. (2026). Sağlık turizmi piyasasının etmen tabanlı simülasyonu: Bilgi asimetrisi, yönetişim kaldıraçları ve yapay zekâ destekli eşleştirme. In G. Köse & U. Köse (Eds.), Sağlık Turizminde Veri Bilimi ve Yapay Zeka. Detay Yayıncılık.
[4] Kose, U., & Uysal, I. (2025). Persona vectors in controlling hallucination of small large language models: A safety-oriented analysis. In 2025 Cyber Awareness and Research Symposium (CARS). IEEE. https://doi.org/10.1109/CARS67163.2025.11337402
[5] Köse, G., & Köse, U. (2025). Synthetic health tourist profiling with small data and a decision support approach using large language models. 1st International Health, Sports and Tourism Congress (HST Congress 2025), Kırşehir, Türkiye. Available on ResearchGate.
---
<div align="center">
Prof. Dr. Utku Köse<br>
Süleyman Demirel University · University of North Dakota · Universidad Panamericana · Vel Tech University
![Website](https://img.shields.io/badge/Website-utkukose.com-1e293b?style=for-the-badge&logo=firefox&logoColor=white)
![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)
![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=for-the-badge&logo=researchgate&logoColor=white)
![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)
![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)
![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)
![PyPI GEMEX](https://img.shields.io/badge/PyPI-GEMEX-3775A9?style=for-the-badge&logo=pypi&logoColor=white)
![PyPI PharmODE](https://img.shields.io/badge/PyPI-PharmODE-3775A9?style=for-the-badge&logo=pypi&logoColor=white)
utkukose@sdu.edu.tr | utku.kose@und.edu | ukose@up.edu.mx | utkukose@gmail.com
"The goal of explainability is not just to explain a model. It is to make intelligence trustworthy."
If any of these projects is useful, a star on the repository is appreciated.
</div>
Acknowledgments
The STING DSS project is supported by the Scientific and Technological Research Council of Türkiye (TÜBİTAK) under the 1001 Programme, Project No. 123E383. The courses on this page were prepared for Süleyman Demirel University, Vel Tech Rangarajan Dr. Sagunthala R&D Institute of Science and Technology and Universidad Panamericana. The workshops belong to programmes hosted by Akdeniz University and by the Center for Cyber Security Research (C2SR) of the University of North Dakota. The health tourism studies are joint work with Gamze Köse. This page relies on the open-source tools snk, Readme Typing SVG, GitHub Readme Streak Stats, GitHub Stats Extended, GitHub Profile Views Counter and Shields.io.
