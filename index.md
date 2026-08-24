# FUTURE_PE_01 — Zen Cafe Prompt Engineering Project

## Project Overview

This project is part of the **Future Interns Prompt Engineering Internship — Task 1**.

The goal is to create a structured AI prompt system for generating website copy for a local business.

## Business Profile

**Business Name:** Zen Cafe
**Business Type:** Cafe
**Location:** Mangalore

### Target Audience

* Students
* Young adults
* Families
* Local customers

### Main Services

* Dine-In
* Takeaway
* Food & Beverages

### Food Categories

* Pizza
* Pasta
* Sandwiches
* Chinese and fast food
* Desserts
* Fresh juices

### Brand Tone

Friendly, welcoming, modern, and simple.

## Prompt Workflow

The project follows this workflow:

**Business Information → Structured Prompt → AI Generation → Output Review → Final Website Copy**

## Prompt System

### 1. Homepage Prompt

The homepage prompt generates:

* Hero section
* Value proposition
* About section
* Featured offerings
* Why Choose Zen Cafe
* Final CTA

**Prompt file:** `prompts/homepage_prompt.md`

**Generated output:** `outputs/homepage.md`

### 2. Services Prompt

The services prompt generates:

* Services introduction
* Dine-In section
* Takeaway section
* Food & Beverage section
* Food category descriptions
* Customer benefits
* Services CTA

**Prompt file:** `prompts/services_prompt.md`

**Generated output:** `outputs/services.md`

### 3. CTA Prompt

The CTA prompt generates:

* Main CTA heading
* Supporting text
* Primary CTA
* Secondary CTA
* Local CTA
* Gentle urgency CTA

**Prompt file:** `prompts/cta_prompt.md`

**Generated output:** `outputs/cta.md`

## Prompt Logic

Each prompt uses the following structure:

1. Define the AI role.
2. Provide business information.
3. Define the target audience.
4. Define the brand tone.
5. Define the website/content goal.
6. Specify the required content sections.
7. Add constraints to avoid unsupported claims.
8. Define the expected output format.

## Tools Used

* **ChatGPT** — Prompt creation and AI content generation
* **GitHub** — Prompt and output documentation

## Final Deliverable

The complete website copy is available in:

`final_website_copy.md`

The individual prompts and their generated outputs are also documented separately for review.

## Repository Structure

```text
## Task 2 – AI Content Marketing using UGC Ads

### Business
Zen Cafe – Mangalore

### Prompt
[View UGC Ad Prompt](task2/prompts/ugc_ad_prompt.md)

### Generated UGC Ad Content
[View UGC Ad Content Pack](task2/outputs/zen_cafe_ugc_ads.md)

### Documentation
[View Task 2 README](task2/README.md)
FUTURE_PE_01/
├── README.md
├── index.md
├── final_website_copy.md
├── prompts/
│   ├── homepage_prompt.md
│   ├── services_prompt.md
│   └── cta_prompt.md
└── outputs/
    ├── homepage.md
    ├── services.md
    └── cta.md
```
