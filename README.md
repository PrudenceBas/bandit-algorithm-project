
# bandit-algorithm-project
# Reinforcement Learning – Bandit Assignment

This project implements several bandit learning algorithms for a 10-armed testbed in both stationary and non-stationary environments. It includes:

- Greedy and ε-Greedy methods
- Optimistic Initialization
- Gradient Bandit algorithm
- Gradual and abrupt changes to reward distributions

---

## 🔧 How to Run the Program

## 🛠 Recommended Setup (VS Code)

> ✅ Make sure you have **VS Code** installed with the **Python** and **Jupyter** extensions enabled.

### 1. Clone the Repository

```bash
git clone https://github.com/PrudenceBas/bandit-algorithm-project.git
cd bandit-algorithm-project
```

### 2. Set Up a Virtual Environment (Optional but Recommended)

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

### 4. Open the Jupyter Notebook

```bash
jupyter notebook
```

Then open the file:

```
bandit_full_with_report.ipynb
```

Make sure the Python interpreter is set to your virtual environment (.venv).

## Run each cell in order using the ▶️ buttons.

## 🧪 Running the Simulations

- The notebook includes **pilot runs**, **demonstration runs**, and **full simulations**.
- You can start by running pilot and demo cells to test.
- Uncomment full simulation cells to run full experiments (can take several minutes).

---

## 📊 Output

The notebook generates:

- Plots of average reward over time
- Percentage of optimal actions taken
- Commentary on performance of each method

---

## 📦 Requirements

Installed via `requirements.txt`:

```
numpy==1.26.4
matplotlib==3.8.4
jupyter==1.0.0
```

---

## 🙋 Need Help?

- Ensure the **Jupyter extension** is installed in VS Code.
- Restart the notebook kernel if plots don’t render.
- Use `Run All` if running the entire notebook at once.

---

