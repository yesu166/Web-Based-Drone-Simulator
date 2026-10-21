# Synthetic Threat Simulation Trainer | Project Brief

> **Proposed repository description:** Browser-based 3D training simulator for synthetic drone operations, aerial observation, contact classification, decision-making, and after-action review.

## Overview
This project explores a browser-delivered 3D training environment where a trainee operates a simulated drone, observes synthetic aerial contacts, classifies what is seen, makes bounded decisions, and reviews performance in repeatable scenarios.

## Problem and opportunity
Physical training environments can be expensive and difficult to reproduce consistently. A software simulator can make practice scenarios repeatable and allow the same decision task to be reviewed across runs.

## Proposed approach
- Render a navigable 3D environment with simulated drone movement and observation controls.
- Create synthetic contacts and scenario events that can be repeated for training.
- Record trainee decisions, confidence, timing, and other supported performance measures.
- Provide after-action review to connect decisions to the evidence visible at the time.
- Keep simulation configuration and performance costs visible so the project can be evaluated on ordinary hardware.

## Current scope and maturity
The README describes a browser-based 3D prototype with drone controls, synthetic contacts, decision workflows, scoring, and after-action review. Those features should be treated as software simulation capabilities, not as validated real-world training outcomes.

## Roadmap proposal
1. Establish deterministic scenario resets and repeatable test fixtures.
2. Document controls, objective, scoring, and what information the trainee can observe.
3. Validate the simulation update loop and rendering on modest CPU/GPU hardware.
4. Add tests for scenario transitions, event history, score calculation, and failure handling.
5. Improve accessibility, reduced-motion behaviour, and mobile controls.
6. Evaluate training quality with domain experts before making effectiveness claims.

## Safety and non-goals
All contacts and threat scenarios should remain explicitly synthetic unless a separately reviewed integration is introduced. This project is not a live drone-control system, a sensor feed, or a validated counter-UAS operational tool. The simulator must not imply real-world threat-detection accuracy based on synthetic scoring.

## Collaboration proposal
Good contribution areas include deterministic test scenarios, performance profiling, control usability, reproducibility, documentation, and after-action review. Contributions that alter scoring or training conclusions should explain the rationale and include tests.

## Licensing and reuse
The root license, if present, governs reuse. This brief does not grant additional rights. Confirm the license and third-party asset terms before inviting broad redistribution.
