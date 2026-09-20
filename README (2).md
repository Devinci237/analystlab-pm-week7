# HealthConnect Clinic Experience Lab, Week 7

**AnalystLab Africa, Project Management Internship, Week 7**
**Author:** Leonel Devinci Ebaha Djoki ([LinkedIn](https://linkedin.com/in/ebaha-devinci))

## Overview

This folder contains the Week 7 deliverables of the AnalystLab Africa Project Management Internship Programme, covering the HealthConnect Clinic Experience Lab.

Week 4 established the governance foundation. Week 5 moved the project into execution and progress monitoring. Week 6 focused on integration between the technical tracks. Week 7 shifts the focus to testing, refinement, and end to end validation: determining whether what was built and integrated in previous weeks actually works, and refining it based on evidence rather than assumption.

**Central project question:** How can HealthConnect Clinic use data and AI to reduce missed appointments and improve the patient support experience?

All figures tied to HealthConnect's operations are fictional, provided for the purpose of this exercise.

## Week 7: Testing Coordination and Project Readiness

The Project Management track's responsibility in Week 7 is to coordinate testing across the four technical tracks, track issues found during testing, close or validate the risks that have been open since earlier weeks, and formally assess whether the project is ready for the Week 8 final integration and presentation.

| Document | Description |
|---|---|
| [Testing Coordination and Project Readiness Package](W7_Testing_Package_HealthConnect.docx) | Full Week 7 deliverable: transition from Week 6, testing readiness, consolidated testing results across all four tracks, updated risk and dependency registers, issue log, decision log, coordination record, status report, Week 8 readiness assessment, and the mandatory HC-POD cross-track testing evidence |
| [Testing Activity Tracker](W7_Testing_Activity_Tracker_HealthConnect.xlsx) | Four test records, one per technical track, each with objective, expected and actual result, pass or fail status, issue raised, action taken, and retest outcome |
| [Updated Timeline](W7_Updated_Timeline_HealthConnect.xlsx) | Gantt view showing Weeks 4 through 6 as complete, Week 7 as in progress, and Week 8 as planned |
| [Week 7 Project Summary](W7_Project_Summary_HealthConnect.docx) | Standalone summary covering what was planned, tested, found, refined, and the focus for Week 8 |

## Notable Design Decisions

- **A limitation was accepted and documented, not hidden.** Testing the Data Science model revealed a slight recall decrease on one patient segment, a direct consequence of the feature engineering trade-off made in Week 6. Rather than reopening that work under time pressure, the decision was to document the limitation clearly (risk R9, issue ISS-04) and carry it into the Week 8 presentation as a known result. A tested limitation is more valuable than an untested claim of success.
- **Risks were closed on evidence, not on the calendar.** Six risks that had been open since Week 4 or Week 5 (R1, R2, R3, R5, R6, R8) were only closed once testing confirmed that the conditions behind them never materialized, not simply because time had passed. This keeps the risk register an accurate record of what was verified rather than a list that empties itself by default.
- **The testing tracker consolidates all four tracks, not just one.** Earlier weeks sometimes concentrated on a single cross track exchange. Week 7 required proof that every track's output was actually tested, so the tracker records one full test cycle, objective, result, issue, action, and retest, for Data Analytics, Data Science, ML Engineering, and Generative AI individually.

## Methodology

This work continues the PMBOK aligned approach established in Weeks 4 through 6: reviewing prior deliverables, converting integration outcomes into tested and validated results, and updating risk and dependency status strictly based on evidence gathered during testing. AI tools were used to assist with drafting and formatting, in line with the internship's guidelines; all reasoning, decisions, and final content were reviewed and validated by the author.

## Programme Context

Produced as part of the AnalystLab Africa Project Management Internship Programme (August to October 2026).

---

*This project is an academic exercise conducted within a structured internship programme. It does not represent an engagement commissioned by any real healthcare provider.*
