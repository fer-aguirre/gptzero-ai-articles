# GPTZero AI Articles
Analysis of AI articles that were created with generative AI models.

### Data

The data was collected from [Media Cloud](https://search.mediacloud.org/), using the collection 'United States - National' for 5,778 news content containing 'chatgpt' from 01-01-23 to 03-01-23.

### Scrapping Data

5,214

### Classification

Created by: Fer Aguirre

---
## Directory Structure
```
├── .gitignore
├── LICENSE
├── Pipfile
├── README.md
├── assets
├── data
│   ├── processed
│   └── raw
├── docs
│   ├── data-dictionary.md
│   └── references
├── gptzero_ai_articles
│   ├── __init__.py
│   ├── data
│   │   ├── __init__.py
│   │   ├── analyze.py
│   │   ├── export.py
│   │   ├── load.py
│   │   └── process.py
│   └── utils
│       ├── __init__.py
│       └── paths.py
├── notebooks
│   ├── 0.0-process.ipynb
│   ├── 1.0-analyze.ipynb
│   └── 2.0-visualize.ipynb
├── outputs
│   ├── figures
│   └── tables
└── setup.py
```
---

## License

This project is released under [MIT License](/LICENSE).

---

This repository was generated with [cookiecutter](https://github.com/cookiecutter/cookiecutter).