---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Applied Math & Physics, University of South Florida, 2026 (Expected)

Work experience
======
* *Jun 2025 - Aug 2025* / **Merck (Boston, MA)** / Modeling & Informatics Intern 
  * Incorporated physics-based method Schrodinger BioLuminate and custom predictive models into
PepINVENT to optimize binding affinity, potency, and ADME properties in peptide design
  * Fine-tuned peptide language model PeptideCLM for enhanced ADME prediction and descriptorbased model CheMeleon for improved potency prediction, exceeding internal benchmarks.
  * Enhanced PepINVENT with a multi-agent framework that can learn the most impactful residue
positions to optimize and outperforms the original version in multi-parameter peptide optimization.
  *  Enabled pretraining of PepINVENT on internal cyclic peptide data for a production-ready model
by developing an algorithm to convert HELM sequences into structured data and expand datasets
through synthetic generation and augmentation.

* *Mar 2023 - May 2025* / **Moffitt Cancer Center (Tampa, FL)** / AI in Drug Discovery Researcher
  * Led development of generative models to design small-molecule drugs by learning pharmacophoric
interactions between ligands and KRAS G12C/Y96C mutant binding pockets.
  * Researched Graph Attention Network (GAT) and Variational Autoencoder (VAE) for molecular
representation learning, aiming to more accurately simulate atomic interactions within molecules
  * Evaluated reinforcement learning algorithms to integrate domain-specific chemistry knowledge for
molecular properties optimization and diverse generation.
  * Assisted medicinal chemists with virtual screening and building machine learning models and led
paper-explaining workshops for both undergraduate and graduate students

* *Feb 2023 - Aug 2023* / **Robot Perception and Action Lab (USF)** / AI Research Assistant
  * Led a team of 3 to build an AI-powered mobile app (Flutter) that calculates daily nutritional
intake, suggests healthy meal plans, and is optimized for elderly accessibility.
  * Fine-tuned Segment Anything Model (SAM) and ChatGPT to achieve 90% accuracy in extracting
food data from images and user conversations.
  

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
* **"AI for Drug Design,"** *Computational and Quantitative Medicine Department.* City of Hope, Duarte, CA, February 2025

* **"Transformer Graph Variational Autoencoder for Drug Design"**
  * *AI+X Symposium.* University of South Florida, Tampa, FL, October 2024 
  * *EMERGE Research in Progress.* Moffitt Cancer Center, Tampa, FL, May 2024 
  * *Oncological Data Science (ODSi) Meeting.* Moffitt Cancer Center, Tampa, FL, April 2024
  
<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
