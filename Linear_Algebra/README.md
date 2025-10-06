# Linear Algebra Learning Journey

This repository documents my step-by-step learning of **Linear Algebra**, with explanations, code, and visualizations.  
The goal is to build strong mathematical foundations for **Data Science, Machine Learning, and AI** by combining theory with Python coding.

---

## 📚 Topics Covered

### 1. Introduction to Vectors
- Defined vectors as ordered lists of numbers.
- Represented vectors geometrically in 2D and 3D space.
- Applications: representing features (e.g., house price prediction).

### 2. Vector Operations
- **Addition & Subtraction**: Head-to-tail method and algebraic addition.
- **Scalar Multiplication**: Scaling vectors by positive and negative constants.
- **Geometric Intuition**: Scaling changes the magnitude and direction.

### 3. Dot Product
- Defined as `a · b = |a||b|cos(θ)` or sum of element-wise multiplication.
- Applications:
  - Checking orthogonality of vectors.
  - Finding projection of one vector onto another.
  - Used in similarity measures (cosine similarity).

### 4. Cross Product
- Defined in 3D as a vector perpendicular to both inputs.
- Magnitude gives area of the parallelogram formed.
- Applications: geometry, physics (torque, rotational motion).

### 5. Linear Combinations
- Representing one vector as a combination of others.
- Key to understanding **span** of vectors.

### 6. Span and Linear Dependence
- **Span**: Set of all possible linear combinations of given vectors.
- **Linear Dependence**: At least one vector can be written as a combination of others.
- **Linear Independence**: No vector can be represented this way.
- Applications: choosing features, understanding redundancy.

### 7. Basis and Dimension
- **Basis**: Minimal set of independent vectors that span a space.
- **Dimension**: Number of vectors in the basis.
- Applications: coordinate systems, feature spaces.

### 8. Matrix Basics
- Definition: Rectangular array of numbers.
- Represented linear transformations.
- Row space, column space.

### 9. Matrix Operations
- **Addition & Scalar Multiplication**
- **Matrix Multiplication**: Dot product of rows & columns.
- Properties:
  - Not commutative (`AB ≠ BA` generally).
  - Associative and distributive.

### 10. Identity and Inverse Matrices
- **Identity Matrix (I)**: Leaves vectors unchanged.
- **Inverse Matrix (A⁻¹)**: Cancels the effect of `A` such that `AA⁻¹ = I`.
- Application: solving systems of linear equations.

### 11. Transpose of a Matrix
- Rows ↔ Columns.
- Used in symmetric matrices, dot products, covariance matrices.

### 12. Determinant
- Scalar value associated with a square matrix.
- Geometric meaning: area/volume scaling factor under transformation.
- If determinant = 0 → matrix is singular (non-invertible).

### 13. Rank
- Number of linearly independent rows or columns.
- Represents the dimension of the column space.
- Application: checking solvability of systems.

### 14. Eigenvalues and Eigenvectors
- **Eigenvector**: A vector that only scales (not rotates) under transformation.
- **Eigenvalue**: The scale factor.
- Applications: PCA (dimensionality reduction), stability analysis, Markov chains.

### 15. Orthogonality
- Vectors are orthogonal if dot product = 0.
- Orthonormal basis → simplifies many computations.
- Applications: QR decomposition, Fourier series.

### 16. Projections
- Projecting one vector onto another using dot product.
- Used in regression (least squares), dimensionality reduction.

---

## 🛠 Tools & Libraries Used
- **NumPy**: For vector/matrix operations.
- **Matplotlib**: For 2D and 3D visualization.
- **SymPy**: For symbolic algebra (eigenvalues, determinants).
- **Scikit-learn** (later): For PCA and ML applications.

---

## 🚀 Applications to Data Science & AI
- Feature representation and scaling.
- Measuring similarity (cosine similarity in NLP, recommender systems).
- Dimensionality reduction (PCA using eigenvalues/eigenvectors).
- Solving systems of equations in regression.
- Understanding transformations in neural networks.
