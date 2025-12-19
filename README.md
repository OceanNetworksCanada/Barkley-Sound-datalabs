Barkley Sound Data Lab
Overview

This repository contains Jupyter notebooks and supporting files for the Barkley Sound Data Lab project. The materials are organized as a guided, notebook-based workflow focused on working with Ocean Networks Canada data from Barkley Sound.

The notebooks were developed for use in Deepnote and may require some adaptation to run in other IDEs or local Jupyter environments.

Repository Structure

This repository contains the following top-level folder(s):

participant-version/


The participant folder contains the entire project, including notebooks (with uncomplete interactive sections), helper files, and image assets. You can find the complete version of the notebooks here:

https://deepnote.com/workspace/ocean_networks_canada-d8a1a703-3320-4724-96bc-7195228468db/project/BMSC-2025-Complete-925b81e8-0463-4b76-8568-a11fbcf77052/notebook/1-Glossary-ef7ccaae9a4040d6ac874d838867f259?utm_source=share-modal&utm_medium=product-shared-content&utm_campaign=notebook&utm_content=925b81e8-0463-4b76-8568-a11fbcf77052

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
