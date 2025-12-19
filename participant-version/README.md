Overview

This repository contains the participant version of the Barkley Sound Data Labs for the BMSC program. The materials are designed as a guided, notebook based workflow that introduces participants to working with oceanographic and ecological data from Barkley Sound, using real datasets and reproducible analysis techniques.

The project is structured around a small set of Jupyter notebooks that are meant to be completed in a specific order, supported by shared helper modules for data access, plotting, and seasonal context.

These notebooks were developed for use in Deepnote. They may require minor adaptation to run smoothly in other IDEs or local Jupyter environments.


Notebook Structure and Order

  There are four notebooks, numbered and intended to be completed sequentially:
  
    Glossary.ipynb
    Introduces key terminology, variables, and concepts used throughout the project. This notebook is meant to be referenced alongside the others.
    
    (2) Plotting-Tutorial.ipynb
    A hands on tutorial focused on plotting and visualization techniques used in later analyses. This notebook establishes shared plotting patterns and conventions.
    
    (3) Folger-Passage-Low-Oxygen.ipynb
    An applied case study examining low oxygen conditions in Folger Passage. Participants combine data access, visualization, and interpretation.
    
    (4) Barkley-Sound-Phytoplankton-Bloom.ipynb
    A second case study focused on phytoplankton bloom dynamics in Barkley Sound, building on skills developed in the previous notebooks.
  
  Each notebook assumes familiarity with concepts and code introduced earlier, so completing them in order is strongly recommended.


Helper Modules

  Three helper Python files support the notebooks and are imported as needed:
  
    ONC_client.py
    Handles interactions with the Ocean Networks Canada (ONC) API and data retrieval.
    
    onc_plotting.py
    Contains shared plotting utilities and formatting functions used across notebooks.
    
    summer_helper.py
    Provides helper functions related to seasonal context and data handling specific to summer field conditions.
    
    These files are not intended to be run directly.


Image Assets

Three of the notebooks include image blocks:

(2) Plotting-Tutorial.ipynb

(3) Folger-Passage-Low-Oxygen.ipynb

(4) Barkley-Sound-Phytoplankton-Bloom.ipynb


For each of these notebooks:

  Images are stored in a dedicated directory located alongside the notebooks.
  Each image directory includes an image_order.txt file.
  The image_order.txt file documents the sequence in which images appear in the notebook, which is especially helpful when viewing or adapting the notebooks outside of Deepnote.
  The images must remain in their original directories for the notebooks to render correctly.
  

Troubleshooting Environment and Platform Notes

  The notebooks are designed and tested in Deepnote.
  
  Running them in other environments, such as local Jupyter, VS Code, or JupyterLab, may require:
  
    Adjusting file paths
    Installing additional dependencies
    Modifying environment setup cells
