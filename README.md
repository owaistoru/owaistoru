<img src="owais.jpg" width="200" align="right" alt="Portrait of Owais Ahmad, smiling" />

# Hi, I'm Owais 👋

**PhD candidate in Mechanical Engineering at the University of Victoria** in British Columbia, Canada (expected completion 2027).

I research renewable energy and hydrogen systems, and build the software to understand how they perform in the real world. That means simulating them hour by hour, over full years of real weather, rather than designing for average conditions.

[![Website: owaistoru.com](https://img.shields.io/badge/Website-owaistoru.com-0b7285?style=flat-square)](https://owaistoru.com/) [![ORCID: 0000-0002-5445-7212](https://img.shields.io/badge/ORCID-0000--0002--5445--7212-a6ce39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0000-0002-5445-7212) [![LinkedIn profile](https://img.shields.io/badge/LinkedIn-Profile-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/owais-ahmad-965a8a65) [![Email: owaisahmad@uvic.ca](https://img.shields.io/badge/Email-owaisahmad%40uvic.ca-555555?style=flat-square)](mailto:owaisahmad@uvic.ca)

<br clear="right" />

## 🔬 What I work on

- **Offshore green hydrogen.** Wind-powered electrolysis and hydrogen buffering linked to liquid-hydrogen (LH₂) shipping or pipeline export, studied as one coupled system.
- **Remote community microgrids.** Dispatch and sizing of renewable, storage and diesel microgrids, comparing forecast-informed model predictive control (MPC) with conventional load-following. This work builds on PGMcpp, the PRIMED Grid Modelling code developed at UVic.
- **Energy storage.** Batteries, underwater compressed-air storage and hydrogen inventories: when storage improves reliability or cost, and when it does not.
- **Optimization under uncertainty.** Multi-objective design with NSGA-II/III, mixed-integer dispatch, sensitivity and Monte Carlo analysis, and year-to-year weather variability.
- **Research software.** C++ and Python simulation platforms with conservation checks, regression tests and recorded provenance, so that results can be rerun and audited.

## 🌊 Featured: OffshoreLH2

<a href="https://owaistoru.com/offshorelh2/"><img src="https://owaistoru.com/assets/img/offshorelh2/gui-2026/offshore-dashboard.png" alt="OffshoreLH2 desktop dashboard showing the summary of an example research run" width="720" /></a>

<sub>Development dashboard after an example research run. Illustrative interface documentation, not a commercial release or verification evidence.</sub>

OffshoreLH2 is an integrated research platform for offshore green-hydrogen systems, which I design and develop as sole author. It simulates an offshore hydrogen hub hour by hour, following wind and wave data through electrolysis, storage and export to delivered cost, and checks energy and mass balances at every step.

- **One engine, four ways in:** a deterministic C++20 core, a Python SDK (pybind11), a PySide6 desktop application and a command-line tool.
- **Web version:** [offshorelh2.owaistoru.com](https://offshorelh2.owaistoru.com/) runs the same engine in your browser. Accounts are approved on request.
- **Status:** pre-release research software. "Verified" means *internally* verified through unit, analytical, conservation and regression tests; external validation is in progress.
- **Access:** the source repository is private while the first public release is prepared, and there is no public installer yet. Researchers interested in the desktop application, evaluation or collaboration are welcome to [ask for access](mailto:owaisahmad@uvic.ca?subject=OffshoreLH2%20access%20request).

[About the software](https://owaistoru.com/offshorelh2/) · [Step-by-step guide](https://owaistoru.com/offshorelh2/guide/) · [Request a web account](https://offshorelh2.owaistoru.com/register)

## 📄 Latest publication

**[Nonlinear operability thresholds in offshore green hydrogen production: Multi-objective system design under metocean uncertainty](https://doi.org/10.1016/j.ijhydene.2026.157530)**<br />
Owais Ahmad, Curran Crawford, Haris Ishaq · *International Journal of Hydrogen Energy* 277, 157530 (2026) · open access

Eleven years of hourly ERA5 data for a North Atlantic and a North Sea site, an hourly production, storage and vessel model, and tri-objective optimization show how wind–wave transfer limits shape offshore hydrogen design.

Two manuscripts on remote-microgrid dispatch and lifecycle emissions are in preparation and revision. See all [publications](https://owaistoru.com/publications/) or my [ORCID record](https://orcid.org/0000-0002-5445-7212).

## 🛠️ Tools I use

- **Programming:** C++20, Python (NumPy, pandas, matplotlib), MATLAB, pybind11, CMake, PySide6, Git and GitHub Actions
- **Optimization and control:** NSGA-II/III, TOPSIS, mixed-integer linear programming, model predictive control
- **Energy modelling:** MATLAB/Simulink, HOMER Pro, OpenDSS, PVsyst, EasyPower
- **Data:** ERA5 reanalysis (Copernicus), Ocean Networks Canada observations, Census and labour-market datasets

## 🧭 Background

Engineering practice came first. Before starting my PhD in 2023, I spent more than two years as a project engineer on commercial and distributed solar-PV systems in Peshawar, Pakistan, and earlier worked as a power engineer on telecom-site power systems with Huawei. That field experience still shapes how I model: equipment has limits, procedures take time, and an optimistic assumption is eventually paid for on site.

I hold a BSc in Electrical Engineering (Power Systems, with distinction) and an MSc in Renewable Energy Engineering from UET Peshawar.

## 🌱 Off the clock

- I speak Pashto, Urdu and English.
- My chai of choice: chamomile with cardamom.
- Always up for spicy food.

## 🤝 Let's connect

I welcome conversations about research collaboration, evaluating OffshoreLH2, and engineering or research roles in renewable energy and energy-system modelling. The best places to start are [owaistoru.com](https://owaistoru.com/), [LinkedIn](https://www.linkedin.com/in/owais-ahmad-965a8a65) or [email](mailto:owaisahmad@uvic.ca).
