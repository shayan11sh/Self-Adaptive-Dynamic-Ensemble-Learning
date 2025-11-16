# SA-DEL: Self-Adaptive Dynamic Ensemble Learning (complete runnable code)

Implements SA-DEL with:
- Contextual bandit per-class thresholding (LinUCB)
- Policy-regularized budget controller
- Safety-constrained updates

Datasets/streams:
- Rotating-MNIST
- CIFAR-10 Drift
- SEA Concepts
- Electricity (Elec2)

## Setup
```bash
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
