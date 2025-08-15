# Online learning in a one-dimensional periodic quadratic variational problem with an adversarial external force

The nummerical results from the paper "Online learning in a one-dimensional periodic quadratic variational problem with an adversarial external force" by Dmitry B. Rokhlin and Olga V. Gurtovaya.

## Authors

Dmitry B. Rokhlin
Institute of Mathematics, Mechanics, and Computer Sciences of the Southern Federal University  
Regional Scientific and Educational Mathematical Center of the Southern Federal University  
`dbrohlin@sfedu.ru`

Olga V. Gurtovaya  
Institute of Mathematics, Mechanics, and Computer Sciences of the Southern Federal University  
`imedashvili@sfedu.ru`


## Abstract

We consider a one-dimensional quadratic variational problem with periodic boundary conditions and an unknown external force. The problem is solved sequentially: at each step a player selects a trajectory, and then receives information about an external force. His goal is to minimize a quadratic functional in the sense of static or dynamic regret with respect to some comparison sequence.
The solution is approximated by trigonometric polyniomials. Based on the estimates of the approximation error, as well as on the estimates of Lipschitz constant, smoothness constant and strong convexity parameter of the approximating function, we show that the regret bounding problem is reduced to a standard finite-dimensional situation. Regret bounds for several algorithms for minimizing static and dynamic regret are presented.

## 📂 Repository Contents

| File | Description | Theorem |
|------|-------------|---------|
| `OGD  experiments.ipynb` | Experiments for Online Gradient Descent | Theorem 1  |
| `OptOGD experiments.ipynb` | Experiments for Optimistic OGD | Theorems 3 & 4 |
| `Chen experiments.ipynb` | Implementation of Chen et al. algorithm (version) | Theorem 5 |
| `Ader experiments.ipynb` | Implementation of ADER algorithm | Theorem 2 |
