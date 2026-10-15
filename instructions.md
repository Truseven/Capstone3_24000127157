# Master Implementation Guide: African Architecture Observatory & Atlas

## 📋 Project Overview
Evolve the existing MASc Capstone (`african-architecture.vercel.app` & GitHub repository `Truseven/Capstone3_24000127157.git`) from a static digital prototype into a rigorous, open-access **Academic Observatory (Option 2)** that automatically drives a **Public Visual Atlas (Option 1)**.

---

## 🚀 Milestone Checklist

- [ ] **Milestone 1: Unified Relational Database Schema & Backend Structure**
  - [ ] 1.1 Design the master database schema (`core_typologies`, `bioclimatic_matrix`, `archival_provenance`, `discourse_and_futures`).
  - [ ] 1.2 Unify existing GitHub CSVs (`architectural_tweets.csv`, `architectural_tweets_lemmatized.csv`, `architectural_tweets_sentiment.csv`) into the new database tables.
  - [ ] 1.3 Write a migration script to map current hardcoded country entries from the Vercel prototype into relational JSON records.

- [ ] **Milestone 2: Upgraded Python Ingestion & NLP/Vision Pipeline**
  - [ ] 2.1 Refactor `Capstone Social Media Research.ipynb` to replace flat VADER scoring with an aspect-based climate/colonial critique classifier.
  - [ ] 2.2 Implement an automated image filter in Python to separate non-architectural noise (Blue) from traditional (Pink) and modern hybrid (Green) structural images.
  - [ ] 2.3 Set up a structured metadata ingest template for Library of Congress postcards applying Gillian Rose's 4 Sites framework.

- [ ] **Milestone 3: Academic Observatory Frontend (For Researchers & Policy Makers)**
  - [ ] 3.1 Build a multi-faceted search & filter interface (by material, climate mechanism, archival era, and Afrofuturist theme).
  - [ ] 3.2 Develop the "Concrete vs. Vernacular" Evidence Matrix dashboard contrasting thermal performance against Western glass/concrete boxes.
  - [ ] 3.3 Add automated citation generators (BibTeX/APA) and open-access data download triggers for reproducible research.

- [ ] **Milestone 4: Public Visual Atlas (Auto-Generated Editorial Experience)**
  - [ ] 4.1 Transform the interactive country map into a dynamic scrollytelling interface.
  - [ ] 4.2 Build the "Time-Slider" profile view linking Colonial Gaze (1890–1936), Present Social Pulse (2024–2026), and Afrofuturist Horizon (2050).
  - [ ] 4.3 Deploy the unified application live to Vercel with responsive mobile and desktop layouts.

- [ ] **Milestone 5: Crowdsourced Field Inventory & Institutional Extension**
  - [ ] 5.1 Create a standardized Field Contribution Form following ICOMOS and ethnological inventory guidelines to bridge the rural-urban data divide.
  - [ ] 5.2 Establish documentation for partner university architecture departments (e.g., African Futures Institute) to submit verified regional case studies.