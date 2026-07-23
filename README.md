# CStream

CStream is the research artifact for adaptive stream compression on modern
multicore processors. It contains the pipeline-stage implementation,
roofline-analysis tools, datasets, experiment configurations, energy-meter
support, and scripts used to evaluate CStream.

## Project status

This is a DataSys stream-processing research artifact accompanying the
[CStream paper](https://doi.org/10.1109/TKDE.2024.3386862). It is organized for
reproducibility rather than as a general-purpose compression library.

## Repository layout

- `1.Fine-grained-stages/`: fine-grained compression pipeline stages.
- `2-Roofline-acquiring/`: roofline measurement tools.
- `3-Dataset/`: dataset preparation assets.
- `4-Config-files/`: experiment configurations.
- `5-Energy-meter/`: host and microcontroller energy-measurement support.
- `6-Scripts/`: experiment scripts.
- `7-enrichedForTKDE/`: material added for the TKDE evaluation.

See the README in each component directory for its prerequisites and commands.

## License

The repository is licensed under Apache License 2.0. Third-party components and
drivers retain their own notices.
