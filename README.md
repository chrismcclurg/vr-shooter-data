# VR Shooter Data

This repository contains the dataset associated with a virtual reality study in which human participants role-played as school shooters in a simulated school environment. The study was designed to support empirical modeling of attacker movement and decision-making during active shooting scenarios, with the broader goal of evaluating school security and robot intervention strategies in simulation.

![Environment](https://github.com/chrismcclurg/VR-Shooter-Data/blob/main/visual/iso.png)

## Overview

Evaluating interventions for school shootings is ethically and practically difficult. Real-world experimentation is infeasible, and retrospective incident reports often lack the high-resolution behavioral data needed to model within-event movement and decision-making.

To address this gap, this study used immersive virtual reality to collect spatial, temporal, and behavioral data from participants acting as school shooters in a controlled school environment. Participants navigated a simulated school while responding to different intervention conditions, including robot-based interventions intended to affect attention, movement, and firing behavior.

The resulting dataset supports research on:

- Human behavior modeling in high-risk, adversarial scenarios
- Shooter movement prediction
- Virtual reality as a data collection method for rare or unethical-to-observe events
- Simulation-based evaluation of school security interventions
- Human-robot interaction in emergency response contexts

## Study Context

This dataset is part of a broader dissertation project developing a simulation framework for modeling school shooter behavior and evaluating security interventions. The framework combines:

1. **Virtual reality experimentation** to collect high-resolution behavioral data
2. **Adversarial role-play** to elicit strategic attacker behavior
3. **Machine learning models** to predict shooter movement
4. **Discrete-event simulation** to evaluate intervention strategies at scale

The VR study provides the empirical foundation for modeling how attackers move through a school environment and how robot interventions may affect shooter behavior.

## Pre-Registration

The study hypotheses and analysis plan were pre-registered on OSF:

[Pre-registered hypotheses on OSF](https://osf.io/hxfjq)

## Paper

This dataset accompanies the following paper:

[Paper link placeholder](LINK_TO_PAPER)

## Citation

If you use this dataset, please cite:

> C. A. McClurg and A. R. Wagner, “Studying the Effects of Robot Intervention on School Shooters in Virtual Reality,” *International Joint Conference on Artificial Intelligence (IJCAI’26)*, Bremen, Germany, Aug. 2026.

## Repository Contents

This repository includes data collected from participants in the VR shooter study, along with supporting files for interpreting the dataset.

Typical contents include:

- Participant trajectory data
- Event logs from the VR environment
- Condition labels
- Scenario metadata
- Visual references for the simulated environment
- Documentation describing the structure of the dataset

The exact file structure may vary by release. See the repository files and accompanying documentation for details on variable names, units, and data formats.

## Data Description

Participants completed trials in a simulated school environment. During each trial, the system recorded behavioral data such as movement through the environment and interaction with scenario elements. These data were used to analyze how different intervention conditions influenced shooter behavior.

Depending on the file, the dataset may include variables such as:

- Participant identifier
- Trial or scenario identifier
- Experimental condition
- Timestamped position data
- Firing-related events
- Victim-related events
- Robot positions

Researchers should review the accompanying data dictionary or file-specific documentation before analysis.

## Ethical and Responsible Use

This dataset concerns a sensitive topic: school shootings and the evaluation of interventions intended to reduce harm. The data were collected in a controlled virtual environment using human subjects acting in a role-play capacity. They do not represent real attacker data.

Users of this dataset should avoid interpretations that overstate ecological validity or imply that VR behavior perfectly reproduces real-world violence. The dataset is intended for research on modeling, simulation, intervention evaluation, and human behavior under constrained experimental conditions.

Appropriate uses include:

- Reproducing analyses from the associated paper
- Developing or evaluating movement prediction models
- Studying behavior in immersive virtual environments
- Testing simulation methods for intervention evaluation
- Comparing VR-elicited behavior with other behavioral modeling approaches

Inappropriate uses include:

- Treating the data as direct evidence of real attacker intent
- Using the data to optimize harmful behavior
- Presenting the dataset as a complete representation of school shooting dynamics

## Recommended Use

Researchers using this dataset should consider the experimental context carefully. The data are best interpreted as behavior elicited under a specific VR role-play protocol, not as direct observations of real-world attackers.

For modeling purposes, we recommend:

1. Preserving the distinction between participant behavior and real-world incident behavior
2. Accounting for experimental condition when analyzing trajectories or outcomes
3. Validating models against held-out participant data before simulation use
4. Being cautious when generalizing beyond the study environment
5. Clearly documenting any preprocessing or filtering steps

## License

Please see the repository license for permitted uses of the data and associated materials.

## Contact

For questions about the dataset, paper, or study design, please contact the repository authors.
