# Production Planning & Optimization with Pyomo


A collection of **production planning and resource optimization models** built with [Pyomo](http://www.pyomo.org/), covering multiple real-world problem types — product mix optimization, fixed setup costs, and resource-constrained production analysis — each solved with its own dataset.

This repo demonstrates practical **Operations Research / Prescriptive Analytics** skills: formulating business problems as mathematical programs (LP/MILP), modeling constraints and costs, and interpreting optimal solutions.

---

## 🎯 What's Inside

| Problem Type | Notebook | Description |
|---|---|---|
| **Product Mix Optimization** | [`01_product_mix.ipynb`](notebooks/01_product_mix.ipynb) | Determines the optimal quantity of each product to manufacture to maximize profit, subject to limited resources (labor, machine hours, materials). |
| **Fixed Setup Costs** | [`02_fixed_setup_costs.ipynb`](notebooks/02_fixed_setup_costs.ipynb) | Extends the base model with binary setup/changeover decisions — a Mixed-Integer Linear Program (MILP) — to capture fixed costs of starting a production run. |
| **Production Analysis** | [`03_production_analysis.ipynb`](notebooks/03_production_analysis.ipynb) | Deeper analysis of production scenarios: sensitivity analysis, constraint bottlenecks, and comparison across resource configurations. |

Each notebook uses its own dataset under `data/`, so problems can be run and compared independently.

---

## 🧠 Key Concepts Demonstrated

- Linear Programming (LP) & Mixed-Integer Linear Programming (MILP)
- Production planning & product-mix optimization
- Resource allocation under capacity constraints
- Fixed / setup cost modeling with binary decision variables
- Sensitivity & bottleneck analysis
- Mathematical modeling with **Pyomo**
- Data-driven optimization using `pandas` for input handling

---

## 🛠️ Tech Stack

- **Python 3.9+**
- **[Pyomo](http://www.pyomo.org/)** — algebraic modeling language for optimization
- **Solver:** CBC / GLPK 
- **pandas** — data loading & manipulation
- **matplotlib** — visualizing results
- **Jupyter Notebook**

---

## 📁 Repository Structure
