# Meta-Learning for Metaheuristic Selection on the TSP (MSc Project jzjf0647)
 
A meta-learning pipeline that predicts the best-performing metaheuristic for a given Travelling Salesman Problem (TSP) instance, using structural features extracted from the instance rather than exhaustively running every candidate algorithm.

## Algorithm Portfolio
 
| Algorithm | Library | Type |
|---|---|---|
| Genetic Algorithm (GA) | `mealpy` | Evolutionary |
| Simulated Annealing (SA) | `mealpy` | Trajectory-based |
| Particle Swarm Optimisation (PSO) | `mealpy` | Swarm-based |
| Lin-Kernighan (LK) | `elkai` (LKH) | Specialised local search |


# Requirements
Requires Linux to execute. WSL for Windows can be used.

```bash
pip install -r requirements.txt
```
Python 3.10+ recommended (developed on 3.11).


```train_meta_base.csv``` and ```val_meta_base.csv``` were made as a part of the removal study of Lin-Kernighan  

```train_meta.csv``` and ```val_meta.csv``` contain the full dataset including Lin-Kernighan
