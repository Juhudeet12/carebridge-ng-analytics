
# CareBridge NG Analytics

**An open-source healthcare operations analytics prototype for Lagos, Nigeria.**

## Overview
CareBridge NG Analytics explores how healthcare operations data can help clinics understand patient flow, visit demand and waiting times.

This project includes a mobile-friendly dashboard built with HTML, CSS and JavaScript, plus a reusable AI skill that guides compatible AI models in interpreting operational metrics responsibly.

## Problem
Healthcare teams need clear ways to understand patient demand and identify periods that may require additional operational support. This prototype demonstrates how simple analytics and AI-assisted explanations could support those discussions.

## Features
- Patient visit and average waiting-time KPI cards.
- Clinic selector for illustrative clinic data.
- Visit-volume chart by time period.
- Operational insights and suggested areas for investigation.
- Reusable CareBridge Insight AI skill.
- Responsible-use guidance that discourages invented statistics and protects patient privacy.

## AI component
The `skills/carebridge-insight/SKILL.md` file defines instructions for a compatible AI model to explain supplied healthcare operations metrics, suggest practical operational actions and state limitations.

The skill is an instruction-based prototype. The dashboard does not currently call an AI model or AI API automatically.

## Technology
- HTML
- CSS
- JavaScript
- GitHub
- Agent Skills format
- Synthetic demonstration data

## How to try the dashboard
1. Open `index.html` in a web browser.
2. Select a clinic from the dropdown.
3. Explore the example visit counts, waiting times and operational insights.

## Data and limitations
All figures are synthetic and intended for demonstration only. They are not real hospital records and should not be used to make clinical or staffing decisions.

The dashboard currently uses example data. Its chart is illustrative and does not automatically recalculate for each clinic selection.

## Responsible AI
- Do not submit patient-identifying information.
- Use only supplied or properly anonymized data.
- Never invent statistics or causes.
- Separate observed patterns from possible explanations.
- Do not use the skill for diagnosis or medical treatment recommendations.

## Future improvements
- Connect the dashboard to a tested open-weight AI model.
- Add validated datasets and automated data-quality checks.
- Add date filters, clinic comparisons and more operational KPIs.
- Develop a documented deployment workflow.

## Project status
Portfolio prototype in development.

Project demo deployment in progress.
