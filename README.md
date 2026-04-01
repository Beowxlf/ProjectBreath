# ProjectBreath

## Project Title
ProjectBreath

## Purpose
ProjectBreath is a 60 day domain mastery framework for developing practical SOC analyst capability through structured, artifact-driven work.

## Core Objective
Build repeatable analyst skill by generating behaviors in a lab, collecting host telemetry, writing detections, and producing triage-quality investigative outputs. The objective is to prove SOC readiness through artifacts, not vague study claims.

## Domain 1 Scope
Domain 1 focuses on:
- Windows authentication
- Process execution
- PowerShell activity
- Persistence behaviors
- Host telemetry analysis

## Repository Structure
- `docs/`: Concept notes, technical references, and attack mapping documentation used to support analyst decisions.
- `scenarios/`: Controlled lab exercises that produce specific security-relevant behaviors for analysis and detection development.
- `detections/`: Detection content in Sigma and SIEM-native formats.
- `evidence/`: Collected artifacts such as screenshots, sample logs, and timelines.
- `writeups/`: Analyst outputs including triage notes and incident reports.
- `templates/`: Standardized markdown templates for scenarios, detections, triage, and incident reporting.

## Workflow
1. Define a scenario and expected security artifacts.
2. Execute the scenario in a controlled lab.
3. Collect and preserve evidence.
4. Analyze telemetry and map behavior to ATT&CK.
5. Write and validate detections.
6. Produce triage notes and incident-quality reports.

## Scenario Lifecycle
1. Plan scenario objective and expected observations.
2. Execute actions that generate measurable behaviors.
3. Capture logs and supporting evidence.
4. Document observed artifacts and deviations.
5. Build or refine detection logic.
6. Validate detection against generated data.
7. Finalize writeups and lessons learned.

## Deliverables
- Scenario documentation for each exercise.
- Detection content with validation steps.
- Preserved evidence (logs, screenshots, timelines).
- Triage notes for analyst decision support.
- Incident report style summaries.

## Success Criteria
- Scenarios produce reproducible telemetry aligned to intended behavior.
- Evidence is complete enough to reconstruct activity timelines.
- Detection logic is documented, testable, and mapped to ATT&CK.
- Writeups reflect clear technical reasoning and defensible dispositions.
