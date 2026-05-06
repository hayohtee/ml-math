# 📐 Mathematics for Machine Learning

A personal learning repository documenting my journey through the essential mathematics behind machine learning — covering linear algebra, calculus, and statistics with hands-on Jupyter notebooks.

## 📁 Project Structure

```
ml-math/
├── linear_algebra/       # Linear algebra concepts and exercises
│   ├── vectors.ipynb
│   ├── vector_spaces.ipynb
│   └── vector_multiplication.ipynb
├── statistics/            # Statistics concepts and exercises
│   ├── descriptive_statistics.ipynb
│   └── visualizing_data.ipynb
├── pyproject.toml
└── README.md
```

## 📚 Topics

### Linear Algebra

| Notebook | Topics Covered |
|----------|---------------|
| [vectors.ipynb](linear_algebra/vectors.ipynb) | Geometric & algebraic interpretation, vector orientation, transpose, addition & subtraction, scalar multiplication |
| [vector_spaces.ipynb](linear_algebra/vector_spaces.ipynb) | Vector spaces, subspaces, span, linear independence, basis |
| [vector_multiplication.ipynb](linear_algebra/vector_multiplication.ipynb) | Dot product, vector multiplication operations |

### Statistics

| Notebook | Topics Covered |
|----------|---------------|
| [descriptive_statistics.ipynb](statistics/descriptive_statistics.ipynb) | Descriptive vs inferential statistics, data distribution, measures of central tendency |
| [visualizing_data.ipynb](statistics/visualizing_data.ipynb) | Data visualization, bar plots, pie charts |

## 🛠️ Setup

This project uses [uv](https://docs.astral.sh/uv/) for dependency management and requires **Python 3.14+**.

### Dependencies

- NumPy
- Matplotlib
- Pandas
- SciPy
- Statsmodels
- IPyKernel (for Jupyter support)

### Installation

```bash
# Clone the repository
git clone https://github.com/hayohtee/ml-math.git
cd ml-math

# Install dependencies with uv
uv sync
```

### Running Notebooks

```bash
# Launch Jupyter
uv run jupyter notebook
```

## 📝 License

This project is for personal educational purposes.
