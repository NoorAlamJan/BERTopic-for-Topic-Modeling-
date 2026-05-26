# Topic Modeling and Information Retrieval

A Python project focused on **Topic Modeling** and **Information Retrieval** using BERTopic.

## Features

- Text preprocessing
- Document embedding generation
- Dimensionality reduction with UMAP
- Clustering with HDBSCAN
- BERTopic-based topic modeling
- Topic visualization and interpretation

## Technologies Used

- Python
- PyTorch
- BERTopic
- Sentence Transformers
- UMAP
- HDBSCAN
- Scikit-learn

## Project Structure

```text
.
├── bertopic_tutorial.ipynb
├── requirements.txt
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

Create a virtual environment (recommended):

```bash
python3 -m venv venv
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
bertopic_tutorial.ipynb
```

## Notes

- macOS users should use Apple Silicon acceleration (MPS) instead of CUDA.
- CUDA-specific PyTorch builds are intended for NVIDIA GPUs only.

## Author

Noor Alam