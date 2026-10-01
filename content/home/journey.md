---
widget: journey
headless: true
weight: 28
title: Education & Experience
design:
  columns: '2'

# One entry per row, newest first. `small: true` gives a compact row without bullets.
# `bullets` is a plain list; `sections` (name + bullets) splits it under small labels.
# Optional `links` (name, url, icon) show as buttons, under the entry or under one section.
# Optional `supervisor` (name, url) shows as a line under the dates.
# Logos are square tiles in static/img/orgs/.
items:
  - title: PhD, Generative Modelling for Materials
    org: University College London, MDI Group
    url: https://mdi-group.github.io/
    location: London, UK
    dates: 2024 - present
    supervisor: {name: Keith T. Butler, url: 'https://mdi-group.github.io/'}
    logo: ucl.png
    sections:
      - name: Research
        bullets:
          - "Building [CrystaLLM-π](https://github.com/C-Bone-UCL/CrystaLLM-pi), a conditional transformer for property-guided crystal structure generation."
      - name: Talks
        bullets:
          - "Talk on CrystaLLM-π at [AI4AM 2026](news/2026-05-ai4am-talk.html), Madrid."
      - name: Teaching
        bullets:
          - "Teaching assistant on Mathematical Foundations of ML, on Machine Learning Methods, as well as a few computational chemistry courses"
          - "Co-organised the [CrystaLLM-π workshop](news/2026-07-psdi-royce-workshop.html) at the PSDI & Royce Materials Data Summit, Manchester 2026."
          - "Supervised two students from under-represented backgrounds for a summer research project"
          - "Mentored Jamie Swaine's bachelor's project, now a paper in J. Mater. Chem. C."
      - name: Awards
        bullets:
          - "[150k GPU-hours on Isambard-AI](news/2026-09-isambard-ai-gpu-hours.html), through UKRI's AIRR AI Open Access call."

  - title: MSci Chemistry with a Year in Industry
    org: Imperial College London
    url: https://www.imperial.ac.uk/
    location: London, UK
    dates: 2019 - 2024
    supervisor: {name: Kim Jelfs, url: 'https://www.jelfs-group.org/'}
    logo: imperial.png
    sections:
      - name: Thesis
        bullets:
          - "MSci thesis, *Evaluating the potential of Geometric Graph Neural Networks to predict the properties of Organic Semiconductors for Photovoltaic applications*: benchmarked and studied failure modes of invariant (SchNet, DimeNet) against equivariant (PaiNN, Equiformer) graph neural networks for organic semiconductor properties. [Code](https://github.com/C-Bone-UCL/Geom3D), [dashboard](https://cyprienmsci.onrender.com/) (it can take a minute to wake up)."
        links:
          - name: Thesis available on request
            url: "mailto:cyprien.bone.24@ucl.ac.uk?subject=MSci%20thesis%20request"
            icon: file-alt
      - name: Teaching
        bullets:
          - "Tutor in physics, maths, chemistry and literature for students in Years 8 to 10 (French 5ème to 3ème)."
      - name: Awards
        bullets:
          - "1st Class Honours, Dean's List (Final Year)."
          - "1st place at the [Energy Idea Challenge 2023](news/2023-energy-idea-hackathon.html), sponsored by Octopus Energy, KPMG and Guidehouse."

  - title: Industrial placement year, Analytical Science Group
    org: Syngenta
    location: Jealott's Hill, UK
    dates: 2022 - 2023
    supervisor: {name: Louise Bacon, url: 'https://www.linkedin.com/in/louise-bacon-b737a9240/'}
    logo: syngenta.png
    bullets:
      - "Built a Design of Experiments model with PCA to optimise X-ray fluorescence sample preparation."
---
