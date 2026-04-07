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
  <div class="seedlearn-tagline">AI-powered identification of tropical tree seedlings</div>
  <p>SeedLearn is an interdisciplinary project developing AI tools to identify tropical tree seedlings using field images, botanical knowledge, and ecological data.</p>
</section>

## Overview

Seedlings are one of the most difficult life stages to identify in tropical forests, yet they are critical for understanding forest regeneration, biodiversity, and restoration outcomes. SeedLearn addresses this challenge by combining expert-curated ecological datasets with multimodal artificial intelligence approaches.

<div class="seedlearn-box">
  <strong>Example seedling</strong>
  <p><em>Capparidastrum frondosum</em> (Capparaceae)</p>
  <img src="/images/seedlearn-capparidastrum-frondosum.jpg" alt="Seedling of Capparidastrum frondosum">
</div>

## Why This Matters

Tropical forests can contain over 300 species per hectare, and many seedlings look nearly identical despite belonging to different species with distinct ecological roles.

This creates a major bottleneck for:

- biodiversity monitoring
- forest restoration
- ecological research

Current AI systems are typically trained on internet images and are not designed for these highly complex and data-limited environments. SeedLearn aims to bridge this gap.

## Research Team

SeedLearn is an interdisciplinary collaboration integrating ecology, artificial intelligence, and computer vision.

- <a href="https://nohemihuanca.github.io/">Nohemi Huanca-Nunez</a> — tropical forest ecology and integration of ecological knowledge into AI systems
- <a href="https://environment.yale.edu/directory/faculty/liza-comita" target="_blank" rel="noopener noreferrer">Liza Comita</a> — tropical forest ecology and long-term forest datasets
- <a href="https://striresearch.si.edu/quantitative-forest-ecology/lab-member/helene-muller-landau/" target="_blank" rel="noopener noreferrer">Helene Muller-Landau</a> — forest ecology and trait and spectral data integration
- <a href="https://engineering.yale.edu/research-and-faculty/faculty-directory/arman-cohan" target="_blank" rel="noopener noreferrer">Arman Cohan</a> — computer vision and AI methods
- <a href="https://engineering.yale.edu/research-and-faculty/faculty-directory/holly-rushmeier" target="_blank" rel="noopener noreferrer">Holly Rushmeier</a> — computer graphics and visual computing
- <a href="https://environment.yale.edu/directory/staff/mitchell-horn" target="_blank" rel="noopener noreferrer">Mitch Horn</a> — AI and data science development and modeling pipeline
- <a href="https://nlp.cs.yale.edu/team" target="_blank" rel="noopener noreferrer">Kaili Liu</a> — multimodal AI and knowledge integration
- <a href="https://environment.yale.edu/directory/faculty/luke-browne" target="_blank" rel="noopener noreferrer">Luke Browne</a> — ecological data processing and data integration

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
    <div class="seedlearn-card-caption"><em>Cojoba rufescens</em><br>Fabaceae mimosoideae</div>
  </div>
  <div class="seedlearn-card">
    <img src="/images/seedlearn-alseis-blackiana.jpg" alt="Seedling of Alseis blackiana">
    <div class="seedlearn-card-caption"><em>Alseis blackiana</em><br>Rubiaceae</div>
  </div>
</div>

<p class="seedlearn-note"><em>Examples of tropical tree seedlings included in the SeedLearn image dataset.</em></p>

## Dataset

The project is built on a curated dataset of tropical seedling images collected through long-term ecological research.

- thousands of images of individual seedlings
- multiple images per individual
- broad taxonomic coverage across species, genera, and families
- expert-validated identifications

These data provide a unique foundation for developing and evaluating AI models in real-world ecological settings.

## Project Foundation

This project builds on prior work supported by the <a href="https://ai.yale.edu/seed-grant-awards-2025">2025 Yale AI Seed Grant program</a>, which helped support early development of the SeedLearn pipeline for AI-based seedling identification. Related work has also been shared through Yale AI venues including the <a href="https://ai.yale.edu/symposium-2025">Yale AI Symposium</a> and in academic research settings.

## Current Progress

- curated and organized a large seedling image dataset
- developed initial AI modeling pipelines
- ongoing model development and evaluation

## Contact

If you are interested in collaboration, datasets, or applications of this work, please feel free to reach out.

Nohemi Huanca-Nunez  
<a href="mailto:nohemi.huanca@yale.edu">nohemi.huanca@yale.edu</a>
