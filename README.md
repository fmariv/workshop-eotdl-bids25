# Mastering EOTDL: A Tutorial on Crafting Training Datasets and Developing Machine Learning Models

Thank you for joining this session! The goal of this workshop is to provide a hands-on and practical introduction to the [Earth Observation Training Data Lab (EOTDL)](https://www.eotdl.com/).

The EOTDL addresses one of the biggest barriers to scaling AI in Earth Observation (EO): the lack of accessible, high-quality training datasets. Creating such datasets is costly and complex, requiring manual labeling, expert input, and even in-situ validation—factors that slow down innovation and the development of EO-based solutions.

EOTDL overcomes these challenges by offering an open, collaborative platform equipped with:

- A cloud-based repository with more than 100 curated datasets covering a wide range of EO applications, from classification and object detection to parameter estimation and 3D analysis.

- A repository of pre-trained machine learning models, providing ready-to-use starting points that accelerate experimentation and model development.

- Tools for dataset generation, curation, and ingestion, enabling users to build and share AI-ready datasets in a reproducible and collaborative way.

## Agenda

This tutorial will guide you step by step through the EOTDL ecosystem:

1. [Introduction to the EOTDL](00_eotdl.ipynb)
2. [Explore and stage datasets and pre-trained models](01_exploring.ipynb)
3. [Ingesting a dataset](02_ingesting_dataset.ipynb)
4. [How the EOTDL uses the STAC specification](04_stac.ipynb)
5. [Private datasets in the EOTDL](05_private_datasets.ipynb)
6. [Creating a dataset with the EOTDL](06_creating.ipynb)
7. [Training a ML model](07_training.ipynb)
8. [Ingesting a model](09_inference.ipynb)
9. [How to contribute](10_contributing.ipynb)

## Getting Started

You can follow the tutorial in two ways:

- Watch the live demonstration and run the notebooks later at your own pace.

- Follow along interactively on your own machine:

  - Register as a user at EOTDL by clicking Sign in.

  - Clone this repository:

    `git clone https://github.com/fmariv/workshop-eotdl-bids25.git`

    - Install Python (minimum version 3.12) and create a virtual environment using [uv](https://docs.astral.sh/uv/). If you don't have `uv` installed, you can follow the instructions [here](https://docs.astral.sh/uv/getting-started/installation/)

    - Synchronize the environment:

      `uv sync`

    - Open the notebooks in Visual Studio Code or your preferred IDE.

Any questions? Let’s get started with the first notebook!

## Community

We invite you to join our Discord server to ask questions, connect with other participants, and receive updates about the EOTDL project even after the event.

<div style="text-align: center;"> <img src="images/discord-qr.png" width=350> </div>

Scan the QR code to join our Discord channel!

## Additional Resources

- [EOTDL Website](https://www.eotdl.com/)
- [EOTDL Documentation](https://www.eotdl.com/docs)
- [EOTDL Tutorials](https://www.eotdl.com/tutorials)
