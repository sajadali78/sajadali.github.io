---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Research Profile
======
Master's-level researcher in electrical engineering with a focus on electromagnetic design and multi-objective optimization of synchronous machines. Lead author of a peer-reviewed publication in Nature Scientific Reports (2026, IF 3.9) on a dual-stator hybrid-rotor synchronous–vernier machine, plus two IEEE conference papers covering torque-ripple minimization of an IPM motor. Hands-on with Ansys Maxwell, Motor-CAD, MATLAB/Simulink, and Python automation. Highly motivated to apply machine-learning surrogate models and multi-objective optimization to the efficiency-driven design of next-generation synchronous machines (PCB motors, SynRMs, IPMs) for electrified mobility, robotics, and sustainable energy systems.

Alignment with the LSEE PhD Topic
======
* **Synchronous machine design** — Master's thesis and Nature Sci. Reports paper on a novel dual-stator brushless synchronous machine; IEEE ELMA 2025 paper on IPM (spoke-type) torque-ripple minimization.
* **FEA and surrogate modelling** — Built large parametric Ansys Maxwell and Motor-CAD design sweeps; developed Python scripts to automate FEA runs and extract performance KPIs (torque, ripple, losses, efficiency).
* **Machine learning readiness** — Working knowledge of Python (NumPy, pandas, scikit-learn, PyTorch basics), regression and classification, and data pipelines for FEA datasets — directly transferable to neural-network, random-forest, and gradient-boosting surrogate models cited in the thesis topic.

Education
======
* **M.E. in Electrical Engineering (Power Systems)**
  * Sukkur IBA University, Sukkur, Pakistan (Jan 2024 – Apr 2026)
  * Thesis: Design of a Dual-Stator Brushless Hybrid-Rotor Machine with Synchronous and Vernier Operation.
  * Outcome: thesis research published in Nature Scientific Reports (2026).

* **B.E. in Electrical Engineering (Power)**
  * Sukkur IBA University, Sukkur, Pakistan (Aug 2018 – Dec 2022)
  * Final-year project on parameter optimization for biogas production from food waste.
  * IEEE SCONEST 2022 Best Abstract Award; Sindh Talent Hunt full merit scholarship (2017).

Research Experience
======
* **Graduate Research Assistant — Electrical Machines Lab** (Aug 2024 – Present)
  * *Sukkur IBA University, Pakistan*
  * Designed and analyzed a novel dual-stator hybrid-rotor synchronous–vernier machine; built parametric Ansys Maxwell models, ran FEA-based design sweeps, and extracted KPIs (torque, ripple, back-EMF, losses, efficiency).
  * Developed an automation pipeline using Python/MATLAB to drive FEA simulations and post-process results — directly applicable to surrogate-model training datasets.
  * Performed comparative analysis of synchronous vs. vernier operating modes for variable-speed applications; co-authored Nature Scientific Reports article reporting the results.
  * Optimized an IPM spoke-type motor for torque-ripple minimization; presented findings at IEEE ELMA 2025 (Sofia, Bulgaria).

Professional Experience
======
* **Field Engineer** (Jan 2023 – Dec 2024)
  * *NETS International, Sukkur, Pakistan*
  * Hands-on commissioning and field-engineering experience on electrical equipment, deepening practical understanding of real-world motor and drive systems.

Technical Skills
======
* **FEA & Machine Design:** Ansys Maxwell, Motor-CAD, electromagnetic 2D/3D FEA, magnetic-circuit modelling, rotor/stator topology design, thermal and loss analysis.
* **Motor Topologies:** Interior PM (IPM), spoke-type IPM, surface PM, dual-stator and hybrid-rotor synchronous machines, vernier machines, brushless synchronous; familiar with PCB-stator and SynRM concepts.
* **Programming & Tools:** MATLAB / Simulink (advanced), Python (NumPy, pandas, matplotlib, scikit-learn — automation & surrogate-model prototyping), C/C++ (basic), PSS/E.
* **Optimization & ML (developing):** Multi-objective optimization for motor design, regression-based surrogate modelling, parametric DOE, exposure to neural networks, random forests and gradient boosting.
* **Languages:** English (fluent, written and oral); Urdu and Sindhi (native); French (beginner — committed to reaching working proficiency).

Awards & Honours
======
* **IEEE SCONEST 2022** — Best Abstract Award (Nov 2022).
* **Sindh Talent Hunt Scholarship** — Full merit scholarship for academic excellence (2017).

Academic References
======
* **Dr. Qasim Ali** — Assistant Professor, Department of Electrical Engineering, Sukkur IBA University. (Qasim.ali@iba-suk.edu.pk)
* **Dr. Hafiz Mudassir Munir** — Assistant Professor, Department of Electrical Engineering, Sukkur IBA University. (mudassir.munir@iba-suk.edu.pk)
* **Dr. Ghulam Akbar** — Assistant Professor, Department of Electrical Engineering, Sukkur IBA University. (Ghulam.akbar@iba-suk.edu.pk)

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
