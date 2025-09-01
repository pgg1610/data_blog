# Omnis Tempus Datum - Data Science Blog

A Quarto-based blog documenting data science explorations, machine learning insights, and chemical informatics resources. This repository contains 60+ posts covering topics from ML fundamentals to advanced scientific computing, serving as both a personal reference and learning resource for the data science community.

## 🚀 Features

- **60+ Technical Posts**: Jupyter notebooks and markdown articles covering ML, data science, and chemical informatics
- **Interactive Content**: Executable code examples with visualizations using matplotlib, seaborn, and scientific libraries
- **Multi-format Support**: Mix of `.ipynb`, `.qmd`, and `.md` files for flexible content creation
- **Dark Mode Support**: Cosmo theme with automatic dark/light mode switching
- **Automated Publishing**: GitHub Actions workflow for seamless deployment to GitHub Pages
- **Search & Filtering**: Built-in content discovery with category-based filtering and full-text search
- **Responsive Design**: Mobile-friendly layout with table-based post listings

## 📋 Prerequisites

Before running this blog locally, ensure you have:

- **Quarto** >= 1.3.0 ([installation guide](https://quarto.org/docs/get-started/))
- **Python** >= 3.9 with scientific computing libraries
- **Git** for version control
- **Node.js** (optional, for advanced customizations)

## 🔧 Installation

### Option 1: Local Development Setup

```bash
# Clone the repository
git clone https://github.com/pgg1610/data_blog.git
cd data_blog

# Install Python dependencies
pip install jupyter matplotlib seaborn pandas numpy scikit-learn torch torchvision
```

### Option 2: Conda Environment Setup

```bash
# Create conda environment with dependencies
conda create -n quarto-blog python=3.9 jupyter matplotlib seaborn pandas numpy scikit-learn pytorch torchvision -c conda-forge -c pytorch
conda activate quarto-blog
```

## ⚡ Quick Start

1. **Clone and setup**:
   ```bash
   git clone https://github.com/pgg1610/data_blog.git
   cd data_blog
   pip install jupyter matplotlib seaborn pandas numpy scikit-learn torch torchvision
   ```

2. **Preview the blog locally**:
   ```bash
   quarto preview
   ```

3. **Open your browser** to `http://localhost:4200` to view the live preview

4. **Make changes** to posts in the `posts/` directory and see them update automatically

## 💻 Usage

### Creating New Posts

Create new content in the `posts/` directory using any of these formats:

#### Jupyter Notebook (.ipynb)
```bash
# Create a new notebook
jupyter notebook posts/2025-01-15-new-analysis.ipynb
```

#### Quarto Markdown (.qmd)
```markdown
---
title: "My New Post"
date: "2025-01-15"
categories: [machine-learning, tutorial]
description: "Brief description of the post"
---

# Your content here
```

#### Standard Markdown (.md)
```markdown
---
title: "Resource Collection"
categories: [resources, reference]
date: "2025-01-15"
description: "Useful resources and links"
---

Your markdown content here
```

### Available Categories

Posts are organized by categories including:
- `machine-learning` - ML algorithms, tutorials, and applications
- `chemical-science` - Chemical informatics and computational chemistry
- `resources` - Curated lists and references
- `data-science` - General data analysis and visualization
- `AI` - Artificial intelligence and deep learning topics

## 🛠️ Development

### Available Commands

```bash
quarto preview          # Start live preview server
quarto render          # Generate static site in docs/
quarto publish         # Publish to hosting platform
quarto check           # Validate project configuration
```

### Project Structure

```
data_blog/
├── _quarto.yml         # Main Quarto configuration
├── index.qmd          # Homepage with post listings
├── about.qmd          # About page
├── posts/             # Blog posts directory
│   ├── _metadata.yml  # Default settings for all posts
│   ├── *.ipynb        # Jupyter notebook posts
│   ├── *.qmd          # Quarto markdown posts
│   └── *.md           # Standard markdown posts
├── docs/              # Generated site output
├── .github/
│   └── workflows/
│       └── quarto-publish.yml  # GitHub Actions workflow
└── theme-dark.scss    # Dark mode theme customizations
```

### Development Notes

- **Content Freezing**: Computational outputs are frozen (`freeze: true`) to prevent re-execution on every build
- **Banner Titles**: All posts use banner-style title blocks for consistent visual design
- **Table Layout**: Homepage uses table format for better post discovery and metadata display
- **GitHub Integration**: Automatic deployment on push to main branch via GitHub Actions

## 🧪 Content Guidelines

### Post Frontmatter Template

```yaml
---
title: "Your Post Title"
date: "YYYY-MM-DD"
categories: [category1, category2]
description: "Brief description for SEO and listings"
toc: true                    # Table of contents
title-block-banner: true     # Banner style title
---
```

### Code Examples

The blog supports executable code in multiple languages:

```python
import pandas as pd
import matplotlib.pyplot as plt

# Your Python code here
```

```r
library(ggplot2)
# Your R code here
```

## 📦 Deployment

### GitHub Pages (Automated)

The repository includes a GitHub Actions workflow that automatically:

1. **Triggers** on push to `main` branch
2. **Sets up** Quarto and Python environment
3. **Installs** scientific computing dependencies
4. **Renders** the complete site
5. **Deploys** to GitHub Pages via `gh-pages` branch

### Manual Deployment

```bash
# Render the site
quarto render

# The generated site is in docs/ directory
# Upload docs/ contents to your hosting platform
```

### Environment Variables

For GitHub Actions deployment, ensure your repository has:

```env
GITHUB_TOKEN=automatically_provided_by_github
```

## 🔗 Links & Social

- **Live Blog**: [GitHub Pages URL]
- **GitHub**: [@pgg1610](https://github.com/pgg1610)
- **Twitter**: [@mepgg](https://twitter.com/mepgg)
- **LinkedIn**: [Pushkar Ghanekar](https://www.linkedin.com/in/pushkarghanekar/)
- **Personal Website**: [pushkarghanekar.com](https://pushkarghanekar.com/)

## 🤝 Contributing

Contributions are welcome! To contribute:

1. **Fork** the repository
2. **Create** your feature branch (`git checkout -b feature/new-post`)
3. **Add** your post to the `posts/` directory following the naming convention `YYYY-MM-DD-title.ext`
4. **Commit** your changes (`git commit -m 'Add new post on [topic]'`)
5. **Push** to the branch (`git push origin feature/new-post`)
6. **Open** a Pull Request

### Content Contribution Guidelines

- Follow the existing naming convention for posts
- Include proper frontmatter with categories and description
- Test locally with `quarto preview` before submitting
- Ensure code examples are executable and well-documented

## 📊 Status

![Quarto](https://img.shields.io/badge/Quarto-75AADB?style=flat&logo=quarto&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=flat&logo=python&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-222222?style=flat&logo=github&logoColor=white)
![Posts](https://img.shields.io/badge/Posts-60+-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

---

*"Omnis tempus datum" - All time is given. This blog serves as a repository of knowledge, continuously growing with each exploration in the vast landscape of data science and machine learning.*