# synbio-learn-showcase
Project showcase for SynBio Learn, a scientific software prototype for microplate data analysis and synthetic biology experiment management. Source code maintained privately.

> **Prototype under active development.** The application source code is maintained privately. This repository presents the project through an illustrated guide.

## Illustrated guide

**[Project Overview & Illustrated User Guide (PDF, 23 pages)](SynBio_Learn_Project_Overview_and_User_Guide.pdf)**

The guide explains the workflow and each screen of the application, with screenshots, step-by-step instructions, the meaning of every output column, a glossary and the development roadmap. The application interface is in Spanish; the guide is in English and gives the Spanish labels in parentheses.

## What the prototype does

SynBio Learn links microplate readings to wells, constructs and experimental conditions, and keeps the analyses together with the experiment.

- **Organise:** projects, experiments, descriptive experimental context and a library of constructs.
- **Import and validate:** CSV or Excel readings and plate maps, checked against each other and previewed before they are confirmed.
- **Analyse growth:** corrected-OD curves, growth-rate and doubling-time estimates, fit windows, quality indicators and reduction against a control.
- **Analyse fluorescence:** OD-normalised fluorescence with validity counts, when the data include fluorescence columns.
- **Compare and export:** saved analyses side by side by construct, access to the original files and CSV outputs.

## Development status

| Area | Status |
|---|---|
| Experiment management, data import, growth analysis, fluorescence, comparisons, exports, construct library | In the current prototype |
| Sequence viewer | In progress |
| Machine learning (recommender) | In development |
| Biophysical models | In development |
| Jobs (background monitoring of long calculations) | Planned, after the sequence module |

## About the examples

The screenshots in the guide come from example experiments used to illustrate the interface. They are not presented as experimental findings, and no claim is made about predictive performance or about compatibility with every instrument export.

## Availability

The source code is maintained privately and is not included in this repository. A demonstration and selected results are available on request. Any access to the source code would be considered separately.

## About the author

Developed by Miquel Carbonell Abella, biologist with a research MSc in Molecular, Cellular and Genetic Biology (Universitat de València). Contact details are available on the GitHub profile.

## Rights

All rights reserved. This repository is a project showcase, not an open-source distribution. No licence to use, modify or redistribute the software is granted.
