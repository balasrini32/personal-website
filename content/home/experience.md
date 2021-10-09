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
  - title: Graduate Research Assistant
    company: Purdue University
    company_url: ''
    company_logo: org-purdue
    date_start: '2018-08-01'
    date_end: ''
    description: Working on Graph representation learning, Equivariant and Invariant representation learning
        
  - title: Applied Scientist Intern
    company: Amazon
    company_url: ''
    company_logo: org-amazon
    date_start: '2021-05-01'
    date_end: '2021-08-01'
    description: Proposed a message passing neural network to capture non rigidity of protein molecules.  We defined conditional transformations (via conditional group equivariances and invariances) that can better describe non-rigidity and conformations of different proteins, while respecting the restrictions posed by constraints on dihedral (torsion) angles and steric repulsions of atoms. We demonstrated performance gains over existing baselines and also provided a model agnostic strategy to improve baseline models.

  - title: Applied Scientist Intern
    company: Amazon
    company_url: ''
    company_logo: org-amazon
    date_start: '2020-06-01'
    date_end: '2020-09-01'
    description: Proposed a hypergraph neural network which exploited the incidence structure and hence worked on real world sparse hypergraphs. Provided provably expressive representations of vertices and hyperedges, as well as that of the complete hypergraph which preserved properties of hypergraph isomorphism. Introduced a new task on hypergraphs -- namely variable sized hyperedge expansion and also performed variable sized hyperedge classification and demonstrated improved performance over existing baselines.

  - title: Software Engineer Intern
    company: Salesforce
    company_url: ''
    company_logo: org-salesforce
    date_start: '2017-06-01'
    date_end: '2017-09-01'
    description: Performed anomaly detection on experienced page load time data accumulated from high traffic network logs with over 100 million data points over 30-days across all continents. Performed incremental spectral clustering to analyze attribute based anomalies using Spark and discovered correlations among various metrics using spectral decomposition as a part of root cause analysis. Built an online random forests model on Spark for real time root cause analysis.

  - title: Software Engineer
    company: ARM
    company_url: ''
    company_logo: org-arm
    date_start: '2015-07-01'
    date_end: '2016-06-01'
    description: Analyzed SPEC (via clustering techniques) and streaming workload performance for mobile and enterprise systems with strong emphasis on big. LITTLE clusters, interconnect and memory. Developed and characterized benchmarks for the cache hierarchy and memory controllers Developed a light weight architecture agnostic Power Model with an accuracy of 97\% represented by a multivariate linear regression of various PMU counters, learnt from carefully selected micros. Developed a scheduler for a shared emulator, modeled as a constraint satisfaction problem.

  - title: Research Intern
    company: Indian Institute of Science
    company_url: ''
    date_start: '2015-01-01'
    date_end: '2015-05-01'
    description: Designed a Runtime Resource Manager for a Massively Parallel Dynamically Reconfigurable Accelerator to efficiently map code and data to a distributed memory for the acceleration of specific compute kernels. Developed kernel modules and a host user application to provide support for a device driver to facilitate communication over a PCIe Interface. A simulator for the whole system was also implemented.

design:
  columns: '2'
---
