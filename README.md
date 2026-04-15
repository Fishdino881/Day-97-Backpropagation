# Day-97-Backpropagation

###  Overview

**Backpropagation** is a key algorithm used to **train neural networks**.
It works by **updating weights based on errors**, helping the model learn and improve over time.

---

##  What is Backpropagation?

Backpropagation is the process of:

1. Making predictions
2. Calculating error (loss)
3. Updating weights to reduce error

---

##  How It Works

```text id="c8k2p4"
Forward Pass → Loss Calculation → Backward Pass → Weight Update
```

---

### 1️ Forward Pass

* Input data passes through the network
* Output is generated

---

### 2️ Loss Calculation

* Compare predicted output with actual output
* Calculate error using a loss function

Example:

```text id="v4m1k7"
Loss = (Actual - Predicted)²
```

---

### 3️ Backward Pass

* Error is propagated backward
* Gradients are calculated

---

### 4️ Weight Update

* Weights are adjusted using gradient descent

```text id="p3n9d2"
New Weight = Old Weight - Learning Rate × Gradient
```

---

##  Key Concepts

###  Gradient Descent

Optimization algorithm used to minimize loss.

###  Learning Rate

Controls how much weights are updated.

###  Chain Rule

Used to calculate gradients in multiple layers.

---

##  Advantages

- Enables neural networks to learn
- Improves model accuracy
- Works for deep learning models

---

##  Challenges

* Vanishing gradients
* Exploding gradients
* Requires proper tuning

---

##  Key Takeaways

- Core algorithm for training neural networks
- Uses error to update weights
- Works with gradient descent

---

