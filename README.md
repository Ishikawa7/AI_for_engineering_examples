# AI for Engineering Examples

This repository demonstrates practical applications of artificial intelligence and machine learning techniques in engineering contexts. Each example is implemented as a self-contained Jupyter notebook with detailed explanations, making complex AI concepts accessible to engineering students and practitioners.

## Overview

The collection spans fundamental AI techniques including reinforcement learning, deep learning, signal processing, and optimization. Each notebook combines theoretical foundations with hands-on implementation, showing how AI can solve real-world engineering problems from battery optimization to predictive maintenance.

## Repository Structure

**Kalman Filters** (`kalman_filter/`) implements state estimation for tracking moving objects with noisy sensor measurements. The example demonstrates how Kalman filters optimally combine predictions with observations to estimate position and velocity, with applications in navigation systems and sensor fusion.

**Q-Learning** (`q_learning_example/`) showcases reinforcement learning through a gridworld navigation problem. An agent learns optimal path-finding strategies by trial and error, avoiding obstacles while reaching goals. This demonstrates fundamental concepts applicable to robotics and autonomous systems.

**Autoencoder Anomaly Detection** (`autoencoder_AD_in_energy_system/`) applies deep learning to identify anomalies in energy system data. The neural network learns to compress and reconstruct normal patterns, enabling detection of equipment failures and unusual operating conditions through reconstruction error analysis.

**Generative Adversarial Networks** (`GAN_example/`) implements image generation using adversarial training. Two neural networks compete to create realistic handwritten digits, demonstrating how GANs can generate synthetic data for training and testing engineering systems.

**Battery Charging Optimization** (`battery_charging_optimization/`) uses neural networks as surrogate models for optimizing battery electrode porosity. The approach shows how AI can accelerate engineering design by replacing expensive simulations with fast predictive models.

**Thermal Insulation Design** (`thermal_insulation/`) demonstrates constrained optimization using neural network surrogates. The example optimizes insulation layer thicknesses to minimize heat loss while satisfying material budget constraints, illustrating AI-driven design optimization.

## Getting Started

Install the required dependencies using the provided requirements file:

```bash
pip install -r requirements.txt
```

Each notebook is self-contained and can be run independently. Start with the Kalman filter or Q-learning examples for fundamental concepts, then explore the deep learning applications. The notebooks include comprehensive explanations of both the AI techniques and their engineering applications.

## Educational Focus

These examples bridge the gap between AI theory and engineering practice. Each implementation includes mathematical foundations, practical considerations, and real-world applications. The code emphasizes clarity and educational value over optimization, making it suitable for learning and teaching AI in engineering contexts.

## Applications Across Engineering Domains

The techniques demonstrated here apply across multiple engineering disciplines. Signal processing and anomaly detection support predictive maintenance in manufacturing and energy systems. Optimization methods enhance design processes in mechanical and electrical engineering. Reinforcement learning enables autonomous operation in robotics and control systems.

## Prerequisites

Basic knowledge of Python programming and fundamental engineering mathematics is assumed. Familiarity with linear algebra and probability theory will enhance understanding of the mathematical foundations, though detailed explanations are provided within each notebook.

## Contributing

The repository welcomes contributions that maintain the educational focus and practical engineering relevance. New examples should include comprehensive explanations and demonstrate clear connections between AI techniques and engineering applications.
