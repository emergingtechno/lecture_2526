# Lecture

Implementation is based on [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics).

# Usage 

Execute planning by `./start.sh`.

# TODO

Each marked with # TODO in source code.

- Adjust Planning and Control Cost in `PathPlanning/HybridAStar/hybrid_a_star.py`: Line 22 - 30.
- Implement collsion checking function in `PathPlanning/HybridAStar/car.py`: Line 27 - 41.
- Implement planning cost function in `PathPlanning/HybridAStar/hybrid_a_star.py`: Line 322 -327.

# Output

Check `hybrid_a_star.gif`for visualization.

```
Evaluation Results:
Path length:
77.33672897329505
Path smoothness:
0.013179421616456638
Computation time:
0.3115086555480957
------------------------------------
Teamscore
379.9050344446234
```