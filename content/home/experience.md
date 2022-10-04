---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Assistant in Quantum Computing
    company: AutoQT project, Quantum Informatics group, University of Edinburgh
    company_url: ''
    company_logo: UoE
    location:
    date_start: '2022-09-01'
    date_end: ''
    description:  |2-
        * Paid internship position to continue the work of my MSc dissertation within the national AutoQT project, leading UK research into quantum hardware testing
        * Direct collaboration with industry partners (Riverlane, Mind Foundry, etc.) to adapt my work of verification to noise characterisations of existing devices for use in their testing

  - title: MSc Dissertation
    company: Quantum Informatics group, University of Edinburgh
    company_url: ''
    company_logo: UoE
    location:
    date_start: '2022-06-01'
    date_end: '2022-08-31'
    description:  |2-
        * Worked within the QI research group, supervised by Prof. Elham Kashefi, attending meetings of the group since January
        * Produced one of the first scalable protocols for running BQP computations on noisy devices by adapting an existing verification protocol
        * Developed the theory of the protocol and tested it by developing a classical simulation of the MBQC framework with Python
        * High-level review of existing error mitigation and verification techniques

  - title: Quantum Computing Research Intern
    company: Theoretical Division, Los Alamos National Laboratory
    company_url: ''
    company_logo: LANL
    location:
    date_start: '2021-06-01'
    date_end: '2021-10-31'
    description:  |2-
        *  Highly competitive 10-week paid internship in quantum information research
        * First author in a collaborative paper with post-doc researchers, later published in PRL
        * We solved an outstanding problem in quantum scrambling theory: distinguishing between scrambling and decoherence via detection of a two-stage fidelity decay
        * Gained theoretical experience in randomized benchmarking protocols and quantum scrambling
        * Gained practical experience using Qiskit to generate and simulate random quantum circuits

design:
  columns: '2'
---
