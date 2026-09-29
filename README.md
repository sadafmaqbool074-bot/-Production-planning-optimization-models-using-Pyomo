# Production Planning & Optimization Models with Pyomo

A collection of **Operations Research and production planning optimization models** developed in Python using **Pyomo**. The repository demonstrates how mathematical optimization can be applied to production, inventory, resource allocation, and capacity planning problems.

Each project uses a structured optimization model, a dedicated dataset, and an appropriate solver to obtain and analyze optimal decisions.

## 🧠 Optimization Concepts

* Linear Programming (LP)
* Mixed-Integer Linear Programming (MILP)
* Production planning and product-mix optimization
* Make-or-Buy decisions
* Inventory management and backlogging
* Fixed and setup cost modeling
* Resource and machine capacity constraints
* Resource allocation
* Bottleneck and capacity analysis
* Multi-period production planning
* Data-driven mathematical modeling

## 🛠️ Technologies & Tools

* **Python 3.14+**
* **Pyomo** — mathematical optimization modeling
* **Pandas** — data processing and input management
* **Matplotlib** — optimization results visualization
* **GLPK / Gurobi** — optimization solvers
* **Jupyter Notebook / Google Colab**

## 📁 Repository Structure

| Notebook                           | Problem                         | Main Concepts                             |
| ---------------------------------- | ------------------------------- | ----------------------------------------- |
| `Make_or_Buy_Lp.ipynb`             | Make-or-Buy Optimization        | LP, sourcing decisions, cost minimization |
| `Production+Inventory model.ipynb` | Production & Inventory Planning | Production, inventory, demand             |
| `backlogging_model.ipynb`          | Production with Backlogging     | Inventory, unmet demand                   |
| `fixed_setup_costs.ipynb`          | Production with Setup Costs     | MILP, binary variables, setup decisions   |
| `production_analysis.ipynb`        | Production Analysis             | Capacity utilization, visualization       |

## 🎯 Project Objectives

The models in this repository focus on using optimization to answer practical production-planning questions such as:

* How much should each product be produced?
* Which components should be manufactured or purchased?
* How should limited machine capacity be allocated?
* When should production setups be activated?
* How can inventory and backlogging be managed?
* Where are production bottlenecks?
* How can total production or operational cost be minimized?

## 📊 Approach

Each optimization project follows a common workflow:

**Data → Mathematical Model → Decision Variables → Constraints → Objective Function → Solver → Optimal Solution → Analysis & Visualization**

## 🚀 Future Projects

The repository will be expanded with more advanced Operations Research models, including:

* Multi-product production planning
* Machine allocation optimization
* Bottleneck analysis
* Aggregate production planning
* Production scheduling
* Multi-period lot sizing
* Resource-constrained optimization
* Supply chain and logistics optimization

