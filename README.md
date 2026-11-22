# AISR Lab: Algorithms for Intelligent Systems and Robotics

Lab experiments for **CSAI4014 Algorithms for Intelligent Systems and Robotics (AISR)**, UPES Dehradun.

## Experiments

| # | Topic | Location | Tools |
|---|-------|----------|-------|
| 1 | Signal analysis with the FFT: time domain, frequency spectrum and amplitude scaling of a noisy multi-tone signal | [Experiment_1.ipynb](Experiment_1.ipynb) | NumPy, Matplotlib |
| 2 | Eight queens problem: generate-and-test vs. backtracking with pruning | [Experiment_2.ipynb](Experiment_2.ipynb) | Python |
| 3 | Breadth-first and depth-first search | [Experiment_3.ipynb](Experiment_3.ipynb) | Python |
| 4 | Hill climbing | [Experiment_4.ipynb](Experiment_4.ipynb) | Python |
| 5 | Reinforcement learning: environment, Q-learning, exploration rate and reading the policy | [Experiment_5.ipynb](Experiment_5.ipynb) | NumPy, Matplotlib |
| 6 | A simple neural network: forward pass, backpropagation, learning rate and decision boundary | [Experiment_6.ipynb](Experiment_6.ipynb) | NumPy, Matplotlib |
| 7 | Webots robotics simulations: swarm of e-pucks (Braitenberg avoidance) and Pioneer 3-DX with lidar (follow-the-gap navigation) | [Experiment 7/](Experiment%207/) | Webots R2025a, Python |
| 8 | Cross-embodiment transfer: moving a pick-and-place skill between KUKA iiwa, Franka Panda, xArm6 and a scaled KUKA | [Experiment 8/](Experiment%208/) | PyBullet, PyTorch |

## Running the experiments

**Experiments 1 to 6** are Jupyter notebooks. Open them in VS Code, JupyterLab or Google Colab and run all cells.

```bash
pip install numpy matplotlib jupyter
jupyter notebook
```

**Experiment 7** needs Webots R2025a. See [Experiment 7/README.md](Experiment%207/README.md) and its [GUIDE.md](Experiment%207/GUIDE.md).

**Experiment 8** needs a Python environment with PyBullet (conda recommended). See [Experiment 8/README.md](Experiment%208/README.md) and [MANUAL.md](Experiment%208/MANUAL.md).

## Repository layout

```
Experiment_1.ipynb ... Experiment_6.ipynb   Python notebooks
Experiment 7/                               Webots worlds, controllers, analysis tools
Experiment 8/                               PyBullet cross-embodiment transfer lab
```

The course report guidelines and lab report files are not tracked in this repository (see [.gitignore](.gitignore)).
