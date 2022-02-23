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
  - title: Teaching Assistant 
    company: Probabilistic AI, ETH Zurich
    company_url: 'https://las.inf.ethz.ch/teaching/pai-f21'
    #company_logo: org-gc
    location: Zurich
    date_start: '2021-09-22'
    date_end: '2022-02-20'
    description: |2-
        Responsibilities include:
        
        * Presented a 2-hour tutorial session to 200 students
        * Prepared homework questions and managed 2 Q&A sessions
        * Assisted 2 lectures and 2 tutorials
     
  - title: Research Project 
    company: Learning and Adaptive Systems lab, ETH Zurich
    company_url: 'https://las.inf.ethz.ch'
    #company_logo: org-gc
    location: Zurich
    date_start: '2021-04-01'
    date_end: ''
    description: |2-
        Contributions include:
        
        * Proposed an algorithm for Movement Penalized episodic contextual Bayesian optimization
        * Theoretically analyzed the performance of the algorithm
        * Ran simulations on both synthetic and real-world data
       
  - title: Research Intern
    company: University of California San Diego
    company_url: 'https://ucsd.edu/'
    #company_logo: org-x
    location: San Diego
    date_start: '2018-06-05'
    date_end: '2018-07-31'
    description: Developed an automated decoding algorithm in C++ to compare kernel permutations efficiently

design:
  columns: '2'
---
