Barkley Sound Data Lab
Overview

This repository contains Jupyter notebooks and supporting files for the Barkley Sound Data Lab project. The materials are organized as a guided, notebook-based workflow focused on working with Ocean Networks Canada data from Barkley Sound.

See the orignal notebooks linked below:

https://deepnote.com/workspace/Ocean-Networks-Canadas-Workspace-d8a1a703-3320-4724-96bc-7195228468db/project/BMSC-2025-Participant-ade8ed14-1fe0-4dd8-a068-473cbde195a5/notebook/1-Glossary-5cd019a646c2409891b9175de9b87843?utm_source=share-modal&utm_medium=product-shared-content&utm_campaign=notebook&utm_content=ade8ed14-1fe0-4dd8-a068-473cbde195a5 


The notebooks were developed for use in Deepnote and may require some adaptation to run in other IDEs or local Jupyter environments.

Repository Structure

This repository contains two top-level folders:

complete-version/

participant-version/


The participant folder contains the entire project, including notebooks, helper files, and image assets. The instructor folder contains the complete version of the core notebooks— these versions are effectively the answer key to the notebooks in the participant section.


Notebook Order

This project contains four notebooks, numbered and intended to be completed sequentially:

Glossary.ipynb
Reference material for terminology, variables, and concepts used throughout the project.

(2) Plotting-Tutorial.ipynb
A tutorial introducing plotting and visualization techniques used throughout the project.

(3) Folger-Passage-Low-Oxygen.ipynb
A case study examining low-oxygen conditions in Folger Passage.

(4) Barkley-Sound-Phytoplankton-Bloom.ipynb
A case study focused on phytoplankton bloom dynamics in Barkley Sound.

The notebooks are designed to be completed in order.


Helper Files

This project includes the following helper Python files, which are imported by the notebooks as needed:

ONC_client.py

onc_plotting.py

summer_helper.py

These files are not intended to be run directly.


Image Assets

Three notebooks include image blocks:

(2) Plotting-Tutorial.ipynb

(3) Folger-Passage-Low-Oxygen.ipynb

(4) Barkley-Sound-Phytoplankton-Bloom.ipynb

For each notebook:

Images are stored in dedicated directories alongside the notebooks.

Each image directory includes an image_order.txt file that documents the intended image sequence.

Depending on how the repository is downloaded, opened, or moved between environments, images may not automatically render in the notebooks. If this occurs, images may need to be re-inserted into the notebook image cells. The image_order.txt files are provided to make it easy to restore the correct image order.


Environment Notes

The notebooks are designed and tested in Deepnote.

Running them in other environments may require adjusting file paths, installing dependencies, or modifying environment setup cells.
