[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)

# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">

- Docs: https://minitorch.github.io/

- Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py

## Task 2.5 Training

### Simple Dataset

- `Layers`: 2
- `Learning Rate`: 0.1
- `Epochs`: 1000
- `Time per epoch`: 0.039s

![Simple Dataset Learning Rate](./assets/simple-setup-2.png)
![Simple Dataset Loss](./assets/simple-loss-2.png)

### Diagonal Dataset

- `Layers`: 5
- `Learning Rate`: 0.5
- `Epochs`: 1000
- `Time per epoch`: 0.102s

![Diagonal Dataset Learning Rate](./assets/diag-setup-5.png)
![Diagonal Dataset Loss](./assets/diag-loss-5.png)

### Split Dataset

- `Layers`: 5
- `Learning Rate`: 0.1
- `Epochs`: 1000
- `Time per epoch`: 0.102s

![Split Dataset Learning Rate](./assets/split-setup-5.png)
![Split Dataset Loss](./assets/split-loss-5.png)

### Circle Dataset

- `Layers`: 5
- `Learning Rate`: 0.1
- `Epochs`: 1000
- `Time per epoch`: 0.102s

![Circle Dataset Learning Rate](./assets/circle-setup-5.png)
![Circle Dataset Loss](./assets/circle-loss-5.png)

### Xor Dataset

- `Layers`: 5
- `Learning Rate`: 0.1
- `Epochs`: 1000
- `Time per epoch`: 0.103s

![Xor Dataset Learning Rate](./assets/xor-setup-5.png)
![Xor Dataset Loss](./assets/xor-loss-5.png)

## Spiral Dataset

- `Layers`: 10
- `Learning Rate`: 0.01
- `Epochs`: 1000
- `Time per epoch`: 0.280s

![Spiral Dataset Learning Rate](./assets/spiral-setup-10.png)
![Spiral Dataset Loss](./assets/spiral-loss-10.png)
