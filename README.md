# Picotorch

Picotorch is a tiny, educational neural network library that implements the minimal building blocks needed to train a simple end-to-end model. It’s designed for learning and experimentation, not production.

Core features

- Lightweight autograd engine with forward/backward passes
- Elementary operators: `add`, `sub`, `mul`, `div`, `exp`, `pow`, `tanh`, `relu`
- Mean squared error (L2) regression loss
- Simple SGD optimizer
- Data handling via plain NumPy (inputs/outputs are managed manually)

Design goals

- Minimal and readable — ideal for studying how autograd and backprop work
- Small surface area — implement only what’s necessary to train a basic neural net
- Easy to extend — clear code paths for adding operators, optimizers, or losses

Quick start

1. Prepare your data with NumPy arrays
2. Build a model using the provided tensor/operation primitives
3. Run a forward pass, compute loss, and call backward
4. Update parameters with the SGD optimizer

Who it’s for

- Students and hobbyists learning core ML implementation details
- Instructors demonstrating autograd and optimization in a compact codebase

Contributions and extensions are welcome — keep changes small and focused to preserve clarity.
