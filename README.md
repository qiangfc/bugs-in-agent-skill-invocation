# Bugs in Agent Skill Invocation

## About This Repository

This repository contains the dataset for a study of 901 failure reports from five open-source projects where agents invoke skills or use tools. The projects are OpenClaw, Hermes Agent, Dify, Open WebUI, and pi.

The study examines failure symptoms (RQ1), root causes (RQ2), task impact and user observability (RQ3), and documented corrective actions and repair cost (RQ4). The dataset supports replication and further research on the reliability of agent skill invocation.

## Dataset

- [Full_Sample_Labels.csv](Full_Sample_Labels.csv) contains one row per report, with issue metadata, sample assignments, symptom and root-cause labels, invocation stages, components, task impact, user observability, and available repair information.

## Kappa Results

- [Kappa Results and Interpretation](Kappa_Results_and_Interpretation.md) describes the reliability samples and reports Cohen’s κ for the annotated fields and repair strategies.

## Acknowledgments

We thank the maintainers and contributors of the five projects for reporting, discussing, and investigating the failures included in this study.
