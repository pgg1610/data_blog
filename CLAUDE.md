# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a personal data science blog built with Quarto, focusing on machine learning, chemical informatics, and data analysis tutorials. The blog contains a mix of Jupyter notebooks and Markdown posts covering topics from basic ML concepts to advanced chemical informatics applications.

## Build and Development Commands

**Core Quarto commands:**
- `quarto render` - Render the entire website to the `docs/` directory
- `quarto preview` - Start a local development server with live reload
- `quarto render posts/filename.qmd` - Render a specific post
- `quarto render posts/filename.ipynb` - Render a specific Jupyter notebook post

**Publishing:**
- The site is built to the `docs/` directory (configured in `_quarto.yml`)
- Static files are served from the `docs/` folder for GitHub Pages or similar hosting

## Content Architecture

**Post Types:**
- **Jupyter Notebooks** (`.ipynb`): Interactive data analysis and tutorials with code execution
- **Markdown Posts** (`.md`): Resource lists, theoretical explanations, and non-computational content
- **Quarto Markdown** (`.qmd`): Hybrid posts with embedded code blocks

**Content Categories:**
- `chemical-science`: Cheminformatics, RDKit, SMILES, molecular analysis
- `machine-learning`: Neural networks, classification, optimization
- `exploratory-data-analysis`: Statistical analysis, visualization
- `python`: Programming tutorials and examples
- `resources`: Curated lists of tools, papers, and references

**Key Directories:**
- `posts/`: All blog content (notebooks, markdown files, supporting data)
- `posts/data/`: Datasets, CSV files, and data processing utilities
- `docs/`: Generated static website (build output)
- `posts/images/`: Static images and diagrams

## Configuration Files

**`_quarto.yml`**: Main site configuration
- Website metadata, navigation, and theming
- Output directory set to `docs/`
- Cosmo theme with dark mode support

**`posts/_metadata.yml`**: Post-level defaults
- Enables computational output freezing
- Sets banner-style title blocks for all posts

## Content Patterns

**Chemical Informatics Posts:**
- Heavy use of RDKit for molecular manipulation
- SMILES notation and chemical structure analysis
- Integration with PubChem and other chemical databases
- Molecular fingerprinting and similarity analysis

**Machine Learning Posts:**
- PyTorch and scikit-learn implementations
- End-to-end ML workflows from data to deployment
- Visualization with matplotlib and seaborn
- Both theoretical explanations and practical implementations

**Data Analysis Posts:**
- Pandas-based data manipulation
- Statistical analysis and hypothesis testing
- Network analysis and graph theory applications
- Real-world datasets (housing, BRFSS, financial data)

## Development Notes

- Posts use computational output freezing to avoid re-executing code on every build
- Many notebooks include custom utility functions and classes
- Chemical posts require RDKit and related chemistry libraries
- ML posts typically use PyTorch, scikit-learn, and standard data science stack
- Posts include both educational content and practical code examples that can be adapted for other projects