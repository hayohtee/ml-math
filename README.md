# 📐 Mathematics for Machine Learning

A personal learning repository documenting my journey through the essential mathematics behind machine learning — covering linear algebra, calculus, and statistics with hands-on Jupyter notebooks.

## 📁 Project Structure

```
ml-math/
├── linear_algebra/       # Linear algebra concepts and exercises
│   └── vectors.ipynb     # Vectors: geometric & algebraic interpretation, operations
├── calculus/              # Calculus concepts (coming soon)
├── statistics/            # Statistics concepts (coming soon)
├── pyproject.toml
└── README.md
```

## 📚 Topics

### Linear Algebra

| Notebook | Topics Covered |
|----------|---------------|
| [vectors.ipynb](linear_algebra/vectors.ipynb) | Geometric & algebraic interpretation, vector orientation, transpose, addition & subtraction, scalar multiplication |

### Calculus
🚧 *Coming soon*

### Statistics
🚧 *Coming soon*

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
