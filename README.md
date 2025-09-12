# ML - Template

A simple, well-structured Machine Learning project template.

You can use this template as a starting point for any ML project, regardless of framework (scikit-learn, TensorFlow, PyTorch, etc.).

## Project structure

```
ml-template/
├── data/ # Datasets (raw and processed)
├── experiments/ # To track experiments (results, notes, configs, and models)
├── notebooks/ # Jupyter notebooks for exploration and prototyping
├── src/ # Source code (data, models, utils)
├── tests/ # Unit tests for code validation (optional)
├── .gitignore # Files and folders ignored by git
├── LICENSE # License for the repo (MIT)
├── README.md # Repo overview and instructions
└── requirements.txt # Python dependencies
```

## Information

This repository is a template for starting any Machine Learning project.  
It provides a well-structured folder layout and placeholder files to help you organize your project efficiently.  

Key points:
- Framework-agnostic: works with scikit-learn, TensorFlow, PyTorch, or any other ML library.
- Ready-to-use structure for data, experiments, notebooks, source code, and tests.
- Designed for both research experiments and production-ready projects.
- Includes a README.md in each folder explaining it's purpose.

Use this template as a starting point to create reproducible, clean, and maintainable ML projects.

## Getting started
1. Clone the repository:
   ```bash
   git clone https://github.com/thomastschinkel/ml-template.git
   cd ml-template
   ```
2. Create a virtual environment
   ```bash
   python -m venv .venv
  source .venv/bin/activate   # Linux/Mac
  .venv\Scripts\activate      # Windows
  ```
3. Install dependencies
  ```bash
  pip install -r requirements.txt
  ```

Now you are ready to start your ML-Project. 
