

### 1. Foundation Math — 1–2 weeks

Make sure you're comfortable with:

* Fractions, percentages, ratios
* Powers and roots
* Exponents and logarithms
* Functions: \(f(x)\)
* Graphs
* Summations: \(\sum\)
* Basic equations and inequalities

You don't need to spend months here. Learn enough to understand later concepts.

### 2. Linear Algebra — 3–4 weeks ⭐

This is probably the **most important starting point for ML mathematics**.

Learn:

* Scalars
* Vectors
* Matrices
* Tensors
* Vector addition
* Dot product
* Matrix multiplication
* Transpose
* Identity matrix
* Inverse
* Linear independence
* Rank
* Basis
* Norms
* Eigenvalues
* Eigenvectors
* Orthogonality
* Projections
* Singular Value Decomposition (SVD)

You'll later understand why ML code contains things like:

```python
import numpy as np

x = np.array([1, 2, 3])
w = np.array([0.5, 0.2, 0.8])

result = np.dot(x, w)
```

Instead of just knowing that `np.dot()` works, you'll understand **what it mathematically represents and why ML models use it**.

### 3. Calculus — 3–4 weeks ⭐

You don't need extremely advanced calculus initially. Focus on calculus used for optimization.

Learn:

* Functions
* Limits
* Derivatives
* Derivative rules
* Partial derivatives
* Chain rule ⭐
* Gradients ⭐
* Directional derivatives
* Minima and maxima
* Multivariable calculus
* Jacobian
* Hessian — basic understanding

This eventually leads you to one of the most important ideas in ML:

**Gradient Descent**

For example:

$$
w_{new} = w_{old} - \eta \frac{\partial L}{\partial w}
$$

When you eventually study neural networks and backpropagation, calculus will make these concepts much easier.

### 4. Probability — 3–4 weeks ⭐

Learn:

* Random experiments
* Sample spaces
* Events
* Probability rules
* Conditional probability
* Independence
* Bayes' theorem ⭐
* Random variables
* Discrete vs continuous variables
* Probability distributions
* Bernoulli distribution
* Binomial distribution
* Gaussian/Normal distribution ⭐
* Uniform distribution
* Probability density function
* Cumulative distribution function
* Expected value
* Variance
* Covariance

Probability becomes extremely important when you start understanding classification, Bayesian models, uncertainty, and generative AI.

### 5. Statistics — 3–4 weeks ⭐

After probability, move into statistics.

Study:

* Population vs sample
* Mean, median, mode
* Variance
* Standard deviation
* Percentiles
* Quartiles
* Covariance
* Correlation
* Outliers
* Sampling
* Central Limit Theorem
* Confidence intervals
* Hypothesis testing
* Null/alternative hypotheses
* p-values
* Z-test
* t-test
* Chi-square test
* Maximum Likelihood Estimation (MLE) ⭐
* Maximum A Posteriori (MAP)
* Bias and variance

This becomes especially important for **data science and ML interviews**.

### 6. Optimization — 2–3 weeks

Once calculus and linear algebra are comfortable, study:

* Objective/loss functions
* Convex vs non-convex functions
* Local vs global minima
* Gradient descent ⭐
* Stochastic Gradient Descent
* Mini-batch Gradient Descent
* Learning rate
* Momentum
* Adam
* Constraints
* Lagrange multipliers — basic understanding

This connects your mathematics directly to neural networks.

### Recommended course sequence

You don't actually need six completely separate courses. A good progression is:

**Phase 1**

[Khan Academy Algebra](https://www.khanacademy.org/math/algebra?utm_source=chatgpt.com)

Use it only to fill gaps in your basic algebra.

**Phase 2**

[Mathematics for Machine Learning — Coursera](https://www.coursera.org/specializations/mathematics-machine-learning?utm_source=chatgpt.com)

This is a very good ML-oriented mathematical foundation, especially for linear algebra and calculus.

**Phase 3**

[3Blue1Brown — Essence of Linear Algebra](https://www.3blue1brown.com/topics/linear-algebra?utm_source=chatgpt.com)

I strongly recommend this alongside your linear algebra study because the visual explanations make vectors, matrices, determinants, eigenvectors, etc. much more intuitive.

**Phase 4**

[Khan Academy Statistics and Probability](https://www.khanacademy.org/math/statistics-probability?utm_source=chatgpt.com)

Use this for probability and statistics.

### Your roadmap

I would structure your learning roughly like this:

```text
MONTH 1
│
├── Basic Algebra                 1 week
└── Linear Algebra               3 weeks
        ↓
MONTH 2
│
└── Calculus                     4 weeks
        ↓
MONTH 3
│
├── Probability                  2 weeks
└── Statistics                   2 weeks
        ↓
MONTH 4
│
├── Optimization                 2 weeks
└── ML Mathematics Practice      2 weeks
        ↓
   MACHINE LEARNING
        ↓
Linear Regression
Logistic Regression
Decision Trees
SVM
PCA
Clustering
        ↓
   DEEP LEARNING
        ↓
Neural Networks
Backpropagation
CNNs
Transformers
LLMs
```

One thing I'd **strongly avoid** is spending 6–12 months studying pure mathematics before touching ML.

For example, when learning **linear regression**, derive the equation mathematically and then implement it yourself in Python/NumPy. When learning **gradient descent**, calculate a few iterations by hand and then implement it. This combination of **math → intuition → Python → ML application** will be much more effective for your goal.

For your FAANG AI/ML goal, I'd budget roughly **3–4 months for ML-focused mathematics**, while continuing Python practice alongside it. After that, mathematics should continue *inside* your ML studies rather than as a completely separate subject.
