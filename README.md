# vedakavach_6129
This project evaluates the effectiveness of encryption and anonymisation techniques applied to unit-level National Sample Survey (NSS) data and proposes an improved Safe Data Tool for secure data dissemination. Traditional anonymisation methods are increasingly vulnerable to re-identification attacks when combined with external datasets.
🇮🇳 NSS Safe Data Tool
Evaluation of Effectiveness of Data Encryption and Anonymisation for Unit-Level NSS Data
📌 Project Overview

The NSS Safe Data Tool is a working prototype designed to evaluate the effectiveness of data encryption and anonymisation techniques applied to unit-level National Sample Survey (NSS) data, and to demonstrate an improved, risk-aware safe data release framework suitable for Indian government datasets.

The project addresses the growing challenge of enabling evidence-based policymaking and research while ensuring strong privacy protection for individual survey respondents in the presence of modern re-identification and linkage attacks.

🎯 Problem Statement

Government surveys such as NSS collect rich micro-level socio-economic data that are essential for policy analysis, academic research, and development planning. However, releasing unit-level data poses serious privacy risks, as traditional anonymisation techniques are increasingly vulnerable when combined with external datasets.

This project evaluates:

Whether existing anonymisation and encryption methods are sufficient

How privacy risks can be quantitatively measured

How data utility can be preserved while enforcing strong privacy guarantees

It further proposes an improved Safe Data Tool that dynamically balances privacy protection and analytical usefulness.

🎯 Objectives

Evaluate the privacy effectiveness of current anonymisation practices

Measure re-identification risk using formal privacy metrics

Demonstrate modern privacy-preserving techniques suitable for NSS data

Quantify utility loss vs privacy gain

Provide a deployable, browser-based prototype for safe data dissemination

🔐 Key Features

k-Anonymity Enforcement
Ensures that each quasi-identifier group contains at least k records

l-Diversity Validation
Prevents sensitive attribute disclosure within anonymised groups

Differential Privacy (Laplace Mechanism)
Adds calibrated statistical noise to sensitive variables

AES-256-GCM Encryption
Encrypts anonymised datasets before release or export

Risk & Utility Metrics

Re-identification risk estimation

Variance-based utility retention

Client-Side Processing

No server dependency

No data transmission

Suitable for sensitive datasets

🧠 Technical Approach
Dataset

Simulated NSS-style unit-level data

Quasi-Identifiers: Age, Gender, District

Sensitive Attribute: Income

Privacy Pipeline

Generalization of quasi-identifiers

Suppression of low-frequency groups

k-Anonymity validation

l-Diversity enforcement

Differential privacy noise injection

AES-256 encryption

📊 Evaluation Metrics
Metric	Description
k-Anonymity	Minimum group size for quasi-identifiers
Re-identification Risk	Approx. 1 / k
Utility Retention	Ratio of variance preserved
Privacy–Utility Tradeoff	Quantified analytically
🖥️ Live Demo

The application is hosted using GitHub Pages and runs entirely in the browser.

🔗 Live URL:
https://<your-github-username>.github.io/nss-safe-data-tool/

🚀 Getting Started
Option 1: Run Online

Simply open the live GitHub Pages link.

Option 2: Run Locally

Download or clone the repository

Open index.html in any modern web browser

Click Run Safe Data Tool

No installation or configuration required.

🛠️ Technology Stack

HTML5

CSS3

Vanilla JavaScript (ES6)

Web Crypto API (AES-GCM)

Client-side statistical computation

🏛️ Policy Relevance

This project aligns with:

India’s Digital Personal Data Protection Act (DPDP Act)

Open Government Data (OGD) principles

OECD & international best practices in statistical disclosure control

The framework is extensible to other government datasets such as:

Census

NFHS

PLFS

SECC

⚠️ Disclaimer

This is a demonstration prototype, not an official NSS release tool

Real NSS datasets were not used

Parameters are configurable for research and evaluation purposes

🔮 Future Enhancements

CSV upload for real datasets

Role-based access control

Attack simulation module

Privacy budget tracking

Integration with secure data labs

👤 Author

Team: Elden Lords - 6129
KG Reddy College of Engineering and Technology


📄 License

This project is released for academic and research purposes only.
