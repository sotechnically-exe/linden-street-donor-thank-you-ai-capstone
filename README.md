# Linden Street Donor Thank-You Assistant

An OptimaNova AI Tech Corps capstone created with Kevon Priester and Lorraine Mercado. This repository documents my contribution to our team project.

Linden Street was a simulated nonprofit case study. Testing used fictional information.

## The Problem

Our discovery interviews showed that one staff member handled development and communications, including donor thank-you letters.

- Approximately 120 donations arrived each month.
- Each thank-you letter took about 12 minutes to write.
- Letters were running two to three weeks behind.

Assuming one letter per donation, this represents approximately 24 hours of writing each month.

Source: simulated interview with Priya Raman, Development and Communications Manager.

## The Build

Our team developed a workflow using Google Sheets, Google Apps Script, and Gmail to help prepare donor thank-you drafts.

The workflow:
- Tracks gift information in Google Sheets.
- Creates drafts in English, Spanish, or Haitian Creole.
- Supports first-time and returning donor messages.
- Flags missing information rather than guessing.
- Creates Gmail drafts for staff review.
- Keeps a review status and space for staff notes.

The tool does not send letters automatically.

## My Contribution

I led discovery research and coordinated our capstone presentation. I interviewed staff, documented workflows, and identified workload estimates that helped explain why donor thank-you letters were a useful starting point.

Before the team build, I also created and tested a separate Claude thank-you drafting assistant using fictional examples.

### Team Contributions

- **La’China Barnes:** Discovery research and presentation coordination.
- **Kevon Priester:** Main technical build and live demonstration.
- **Lorraine Mercado:** Diagnosis, handoff, and training materials.

## The Human Check

A staff member reviews every draft before sending it.

The reviewer checks:
- Donor name and gift amount against the source.
- Accuracy of program details.
- Warmth and appropriate organizational tone.
- Missing information or warnings.
- Privacy and sensitive information.

Spanish and Haitian Creole drafts require a fluent language review before use.

## Before-and-After Numbers

| Measure | Before | After |
| --- | --- | --- |
| Time per letter | Approximately 12 minutes | Team workflow timing still to be added |
| Monthly volume | Approximately 120 donations | Same volume used for comparison |
| Estimated monthly writing time | 24 hours | Depends on measured drafting and review time |

Baseline calculation: 120 letters × 12 minutes ÷ 60 = 24 hours per month.

For the team workflow, monthly time will be calculated as:
120 × measured minutes per reviewed letter ÷ 60.

These are prototype estimates, not confirmed savings from a live deployment.

### Earlier Individual Prototype

One fictional test of my separate Claude assistant took 28.2 seconds, including my review. This was a single test and does not establish the performance of our team's Google Sheets and Gmail workflow.

## Screenshots

Screenshots to add:
1. Google Sheets gift tracker using fictional information.
2. Generated Gmail thank-you draft.
3. Human review status and missing-information warning.

## Demo Video

Demo video link: [Watch our capstone demo](https://drive.google.com/file/d/1JweMkjPQfKyHp5X5g7wk8tBFDNeqZbZ3/view?usp=sharing)

## What I Learned

This project helped me connect discovery interviews to a practical solution. I learned to document the problem, test assumptions, and keep a person responsible for checking AI-generated work.

## Acknowledgments

Thank you to my teammates, Kevon Priester and Lorraine Mercado, and to OptimaNova AI, AI Tech Corps, and The Knowledge House.
