# Responsible AI – Master Checklist

## 0. Scoping
- [ ] Define system scope (recommender, hiring, chatbot, analytics)
- [ ] Identify users (seeker, recruiter, moderator, admin)
- [ ] Map data sources (profile, resume, chat, geolocation/IP, third parties)

## 1. Fairness (F)
- [ ] Training/data sources documented (high level)
- [ ] Matching/ranking aligns to stated user intent
- [ ] Deduplication or spam filtering in place (where relevant)
- [ ] Location inference visible and overridable by user
- [ ] Spot-check adverse impact (names, zip codes, schools) — record notes

## 2. Accountability (A)
- [ ] Named owner for AI behavior and updates
- [ ] Risk register started/updated (see `templates/risk-register.csv`)
- [ ] Incident path defined (how do users report harm?)
- [ ] Issue workflow enabled (bias/privacy/security templates)

## 3. Transparency (T)
- [ ] Plain-language disclosure before evaluation begins
- [ ] Short “reason strings” for results (e.g., "Matched your SOC interest + NC")
- [ ] User controls: edit interests, location, filters; feedback channel present

## 4. Privacy & Security (P/S)
- [ ] Data minimization — only collect what’s needed
- [ ] Encryption in transit/at rest described; key mgmt noted
- [ ] Retention & deletion documented; third-party sharing disclosed
- [ ] Youth/K-12: age-gating & parent/school guidance (if relevant)

## 5. Testing & Evidence
- [ ] Functional & UAT scenarios executed (see evaluation plan)
- [ ] Regression checks for ranking, dedupe, location
- [ ] Redacted evidence added under `/evidence/<system>`
- [ ] Public summary written (non-confidential)

