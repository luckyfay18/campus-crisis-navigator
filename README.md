# Campus Crisis Navigator

**Agentic AI-Based Closed-Loop PDCA System for Self-Harm Prevention Among High-Risk Students: A Case Study of High School Counseling Practice**

中文研究題目：基於代理型人工智慧之高風險學生自我傷害防治PDCA閉環系統：以高中輔導實務為例

## Project Overview

Campus Crisis Navigator is an early-stage research and development project grounded in high school counseling practice.

The project aims to develop an AI-assisted system that supports teachers and school counselors in identifying student self-harm crisis indicators, retrieving relevant regulations and guidance, preparing response and documentation drafts, and managing follow-up and reassessment.

The intended system combines controlled agentic AI workflows, retrieval-augmented generation (RAG), human-in-the-loop (HITL) review, and a Plan–Do–Check–Act (PDCA) cycle.

## Research Scope

This study adopts Design Science Research Methodology (DSRM) to guide system design, development, demonstration, evaluation, and communication.

The current research focuses on system output quality and workflow feasibility through standardized fictional scenarios and multidisciplinary expert review.

It does not currently test whether system use reduces student self-harm, teacher anxiety, or administrative workload. The high school counseling context informs system design; this stage does not involve intervention testing with actual students.

## Current Development Status

An initial Dify Chatflow prototype has been developed locally. It includes:

- Knowledge retrieval from selected reference documents
- Preliminary crisis categorization
- Response suggestions
- Draft incident summaries and counseling records

The prototype requires further development and testing. Controlled agentic capabilities, enforceable human approval checkpoints, and persistent PDCA follow-up mechanisms are planned and have not yet been fully implemented.

The Dify workflow has not yet been published in this repository.

## Planned System Functions

- Identify crisis indicators and distinguish known facts from missing information
- Retrieve applicable regulations and school procedures with traceable sources
- Generate response suggestions that clearly communicate evidence and uncertainty
- Prepare incident reporting summaries and counseling record drafts
- Generate parent–teacher communication guidance for professional review
- Require human review at consequential decision points
- Record completed actions and follow-up observations
- Support reassessment and plan revision within a PDCA cycle

## PDCA Workflow

- **Plan:** Organize available information, identify gaps, and prepare a response plan for human confirmation.
- **Do:** Record actions actually completed by authorized personnel.
- **Check:** Review execution, procedural requirements, follow-up observations, and unresolved concerns.
- **Act:** Revise the plan, continue follow-up, or initiate renewed assessment under human oversight.

Generating recommendations alone does not constitute a completed PDCA cycle.

## Evaluation Plan

Standardized fictional scenarios and multidisciplinary expert review will assess:

- Regulatory and procedural compliance
- Appropriateness of crisis response suggestions
- Documentation accuracy and practical usability
- Quality of parent–teacher communication guidance
- Safety, ethical boundaries, and human oversight
- Continuity of execution reporting, follow-up, and reassessment

System versions, test outputs, expert feedback, and revisions will be documented to support reproducibility.

## Safety and Data Boundaries

This research prototype is not a diagnostic tool, an emergency response service, or a replacement for professional judgment.

System use must not delay emergency assistance or established school crisis procedures. Formal reporting and consequential decisions remain the responsibility of authorized personnel.

Crisis categorization is intended to support response prioritization, not to predict future suicide or establish that a student is safe.

Only fictional scenarios are intended for public testing. Student records, personal data, credentials, and third-party documents without redistribution permission will not be included.

## Maintainer

GitHub: @luckyfay18

The project is informed by high school counseling practice and research in education.

## License

An open-source license has not yet been selected. Public visibility alone does not grant permission to reuse or redistribute the materials.
