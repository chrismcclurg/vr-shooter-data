# VR Shooter Data

This repository contains the dataset associated with a virtual reality study in which human participants role-played as school shooters in a simulated school environment. The study was designed to support empirical modeling of attacker movement, decision-making, and responses to robot-based intervention strategies.

![Environment](https://github.com/chrismcclurg/VR-Shooter-Data/blob/main/visual/iso.png)

## Overview

Evaluating interventions for school shootings is ethically and practically difficult. Real-world experimentation is infeasible, and retrospective incident reports often lack the high-resolution behavioral data needed to model within-event movement and decision-making.

To address this gap, this study used immersive virtual reality to collect spatial, temporal, and behavioral data from participants acting in a controlled adversarial role-play scenario. Participants navigated a simulated school environment while responding to different intervention conditions, including robot-based interventions intended to affect attention, movement, and firing behavior.

The resulting dataset supports research on:

- Human behavior modeling in high-risk, adversarial scenarios
- Shooter movement prediction
- Virtual reality as a data collection method for rare or unethical-to-observe events
- Simulation-based evaluation of school security interventions
- Human-robot interaction in emergency response contexts

## Dataset

This repository includes participant data from the VR shooter study, along with supporting files for interpreting the dataset.

Typical contents include:

- Participant trajectory data
- Event logs from the VR environment
- Experimental condition labels
- Scenario metadata
- Visual references for the simulated environment
- Documentation describing the structure of the dataset

Depending on the file, the dataset may include variables such as:

- Participant identifier
- Trial or scenario identifier
- Experimental condition
- Timestamped position data
- Firing-related events
- Victim-related events
- Robot positions

The exact file structure may vary by release. Researchers should review the accompanying data dictionary or file-specific documentation for details on variable names, units, and data formats.

## Pre-Registration and Publications

The study hypotheses and analysis plan were pre-registered on OSF:

[Pre-registered hypotheses on OSF](https://osf.io/hxfjq)

This dataset accompanies the following paper:

[Paper link placeholder](LINK_TO_PAPER)

### Primary Dataset Citation

If you use this dataset, please cite:

> C. A. McClurg and A. R. Wagner, “Studying the Effects of Robot Intervention on School Shooters in Virtual Reality,” *International Joint Conference on Artificial Intelligence (IJCAI’26)*, Bremen, Germany, Aug. 2026.

### Related Publications

This dataset and study are part of a broader line of work on using virtual reality and simulation to model school shooter behavior and evaluate intervention strategies:

> C. A. McClurg and A. R. Wagner, “Using Virtual Reality to Simulate and Study the Movements of School Shooters,” in *Proc. 2025 Annu. Modeling Simulation Conf. (ANNSIM’25)*, Madrid, Spain, May 2025.

> C. A. McClurg and A. R. Wagner, “Developing Shooter Movement Models from Virtual Reality Simulation,” *SIMULATION: Transactions of the Society for Modeling and Simulation International*, accepted for publication, 2026.

## Responsible Use

This dataset concerns a sensitive topic: school shootings and the evaluation of interventions intended to reduce harm. The data were collected in a controlled virtual environment using human subjects acting in a role-play capacity. They do not represent real attacker data.

Researchers using this dataset should avoid interpretations that overstate ecological validity or imply that VR behavior perfectly reproduces real-world violence. The data are best interpreted as behavior elicited under a specific VR role-play protocol, not as direct observations of real-world attackers.

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
