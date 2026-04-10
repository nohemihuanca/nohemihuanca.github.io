---
title: "SeedLearn"
permalink: /seedlearn/
author_profile: true
---

<style>
.seedlearn-hero {
  margin: 0 0 2rem 0;
  padding: 2.75rem 2rem;
  border-radius: 18px;
  background: linear-gradient(135deg, #f4f1e6 0%, #dce9d5 55%, #c6dcc4 100%);
  border: 1px solid rgba(73, 108, 64, 0.16);
}

.seedlearn-hero h1 {
  margin-top: 0;
  margin-bottom: 0.35rem;
}

.seedlearn-tagline {
  font-size: 1.15rem;
  font-weight: 600;
  color: #2f5b38;
  margin-bottom: 1rem;
}

.seedlearn-box {
  margin: 1.5rem 0;
  padding: 1rem;
  border-radius: 14px;
  background: #f8faf6;
  border: 1px solid #d9e3d2;
}

.seedlearn-box p {
  margin: 0.35rem 0 0 0;
}

.seedlearn-box img {
  width: 100%;
  max-width: 420px;
  display: block;
  border-radius: 12px;
  margin-top: 0.85rem;
}

.seedlearn-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 0.9rem;
  margin: 1.25rem 0;
}

.seedlearn-card {
  min-height: 155px;
  border-radius: 14px;
  background: linear-gradient(180deg, #f7f3e8 0%, #eef5ea 100%);
  border: 1px solid #dde7d8;
  overflow: hidden;
}

.seedlearn-card img {
  display: block;
  width: 100%;
  height: 210px;
  object-fit: cover;
}

.seedlearn-card-caption {
  padding: 0.75rem 0.9rem 0.9rem 0.9rem;
  color: #48624a;
  font-weight: 600;
  font-size: 0.92rem;
}

.seedlearn-pipeline {
  margin: 1.25rem 0 1.75rem 0;
  padding: 1rem;
  border-radius: 14px;
  background: #fbfcf8;
  border: 1px dashed #b9c9b3;
}

.seedlearn-pipeline strong {
  color: #2f5b38;
}

.seedlearn-note {
  font-size: 0.95rem;
  color: #5e6d5f;
  margin-top: -0.5rem;
}
</style>

<section class="seedlearn-hero">
  <h1>🌱 SeedLearn</h1>
  <div class="seedlearn-tagline">Building AI tools for plant identification, grounded in ecology and botanical expertise</div>
  <p>SeedLearn is an interdisciplinary research project developing AI approaches for plant identification using field images, botanical knowledge, and ecological data. Our current foundation is tropical tree seedlings, where identification is especially difficult and where we already have a strong expert-curated dataset.</p>
</section>

## Overview

SeedLearn is designed as a broader framework for plant identification in ecologically complex systems. We are starting with tropical tree seedlings because they are one of the most difficult life stages to identify in tropical forests, yet they are critical for understanding forest regeneration, biodiversity, and restoration outcomes.

This first step allows us to build and test the project on a real, expert-curated dataset before expanding to additional plant stages, data types, and applications. In other words, seedlings are the current focus, but they are also the entry point for a larger long-term effort.

<div class="seedlearn-box">
  <strong>Example seedling</strong>
  <p><em>Capparidastrum frondosum</em> (Capparaceae)</p>
  <img src="/images/seedlearn-capparidastrum-frondosum.jpg" alt="Seedling of Capparidastrum frondosum">
</div>

## Research Team

SeedLearn is led by Nohemi Huanca-Nunez and brings together an interdisciplinary team spanning ecology, artificial intelligence, and computer vision.

- <a href="https://nohemihuanca.github.io/">Nohemi Huanca-Nunez</a> — project lead; tropical forest ecology and integration of ecological knowledge into AI systems
- <a href="https://environment.yale.edu/directory/faculty/liza-comita" target="_blank" rel="noopener noreferrer">Liza Comita</a> — tropical forest ecology and long-term forest datasets
- <a href="https://striresearch.si.edu/quantitative-forest-ecology/lab-member/helene-muller-landau/" target="_blank" rel="noopener noreferrer">Helene Muller-Landau</a> — forest ecology and trait data integration
- <a href="https://www.nybg.org/person/fabian-a-michelangeli/" target="_blank" rel="noopener noreferrer">Fabian Michelangeli</a> — tropical botany, systematics, and biodiversity research
- <a href="https://engineering.yale.edu/research-and-faculty/faculty-directory/arman-cohan" target="_blank" rel="noopener noreferrer">Arman Cohan</a> — computer vision and AI methods
- <a href="https://engineering.yale.edu/research-and-faculty/faculty-directory/holly-rushmeier" target="_blank" rel="noopener noreferrer">Holly Rushmeier</a> — Yale University; computer graphics and visual computing
- <a href="https://environment.yale.edu/directory/staff/mitchell-horn" target="_blank" rel="noopener noreferrer">Mitch Horn</a> — AI and data science development and modeling pipeline
- <a href="https://nlp.cs.yale.edu/team" target="_blank" rel="noopener noreferrer">Kaili Liu</a> — multimodal AI and knowledge integration
- <a href="https://environment.yale.edu/directory/faculty/luke-browne" target="_blank" rel="noopener noreferrer">Luke Browne</a> — ecological data processing and data integration

## Why This Matters

Tropical forests can contain over 300 species per hectare, and many seedlings look nearly identical despite belonging to different species with distinct ecological roles.

This creates a major bottleneck for:

- biodiversity monitoring
- forest restoration
- ecological research

Current AI systems are typically trained on internet images and are not designed for these highly complex and data-limited environments. SeedLearn aims to bridge this gap.

## Current Scope and Long-Term Vision

SeedLearn begins with seedling identification because seedlings are among the hardest plant life stages to identify in the field, with many closely related species appearing remarkably similar at this stage.

Our current scope includes:

- tropical tree seedling images
- expert-validated species identifications
- initial multimodal AI model development

Our long-term vision is to expand toward more general plant identification workflows by integrating additional life stages, richer trait information, and complementary data sources such as species descriptions, ecological context, and other plant measurements.

This phased approach helps keep the project scientifically grounded while building toward a more general system over time.

## The Challenge

<div class="seedlearn-grid">
  <div class="seedlearn-card">
    <img src="/images/seedlearn-aphelandra-scabra.jpg" alt="Seedling of Aphelandra scabra">
    <div class="seedlearn-card-caption"><em>Aphelandra scabra</em><br>Acanthaceae</div>
  </div>
  <div class="seedlearn-card">
    <img src="/images/seedlearn-miconia-simplex.jpg" alt="Seedling of Miconia simplex">
    <div class="seedlearn-card-caption"><em>Miconia simplex</em><br>Melastomataceae</div>
  </div>
  <div class="seedlearn-card">
    <img src="/images/seedlearn-cojoba-rufescens.jpg" alt="Seedling of Cojoba rufescens">
    <div class="seedlearn-card-caption"><em>Cojoba rufescens</em><br>Fabaceae</div>
  </div>
  <div class="seedlearn-card">
    <img src="/images/seedlearn-alseis-blackiana.jpg" alt="Seedling of Alseis blackiana">
    <div class="seedlearn-card-caption"><em>Alseis blackiana</em><br>Rubiaceae</div>
  </div>
</div>

<p class="seedlearn-note"><em>Examples of tropical tree seedlings included in the SeedLearn image dataset.</em></p>

## Dataset

The current project is built on a curated dataset of tropical seedling images collected through long-term ecological research.

- thousands of images of individual seedlings
- multiple images per individual
- broad taxonomic coverage across species, genera, and families
- expert-validated identifications

These data provide a strong foundation for developing and evaluating AI models in real-world ecological settings, and they serve as the first stage of a broader identification framework.

## Current Progress

- curated and organized a large seedling image dataset
- developed initial AI modeling pipelines
- ongoing model development and evaluation
- defining how the framework can expand beyond seedlings as new datasets become available

## Project Support

This project is supported by the <a href="https://ai.yale.edu/seed-grant-awards-2025">2025 Yale AI Seed Grant</a>, which enabled the initial development of the SeedLearn pipeline, with seedlings as the first use case.

## Contact

If you are interested in collaboration, datasets, or applications of this work, please feel free to reach out.

Nohemi Huanca-Nunez  
<a href="mailto:nohemi.huanca@yale.edu">nohemi.huanca@yale.edu</a>
