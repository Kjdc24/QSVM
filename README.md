# Comparative Study of Quantum and Classical SVM Models (QSVM)

An exploratory project on applying Support Vector Machines in a quantum computing framework.



## Overview
Quantum Machine Learning combines principles of quantum computing with classical ML algorithms.  
This project presents a comparative analysis of Support Vector Machine (SVM) models implemented in classical, quantum, and hybrid quantum–classical settings. The objective is to evaluate their performance, feasibility, and limitations when executed on traditional computing environments using quantum simulations.

Support Vector Machines are powerful supervised learning algorithms widely used for classification tasks due to their ability to construct optimal decision boundaries in high-dimensional feature spaces. 
QSVMs aim to leverage quantum computation principles—such as quantum state superposition and high-dimensional Hilbert spaces—to potentially improve the efficiency and expressive power of kernel-based learning.



## Key Motivation
- Classical SVMs rely heavily on kernel functions to map data into higher-dimensional spaces, which can become computationally expensive as dataset size and feature dimensionality increase. Quantum computing offers a theoretical advantage by enabling:
- Implicit representation of extremely high-dimensional feature spaces
- Faster kernel evaluations under certain assumptions
- Exploration of complex data relationships that are hard to model classically
- This project investigates how quantum feature maps and quantum kernels can be used to construct QSVM models and compares their conceptual workflow with classical SVMs.



## Core Concepts Covered

- Quantum Feature Mapping : Classical input vectors are encoded into quantum states using parameterized quantum circuits, effectively embedding data into a quantum Hilbert space.
- Quantum Kernel Estimation : Kernel values are computed using inner products of quantum states, replacing classical kernel functions.
- Hybrid Quantum–Classical Learning : The QSVM pipeline follows a hybrid approach where:
-- Quantum circuits handle feature mapping and kernel computation
-- Classical optimization techniques perform training and classification
- Comparison with Classical SVMs - Conceptual comparison in terms of:
-- Feature space dimensionality
-- Computational complexity
-- Scalability and feasibility on near-term quantum devices



## Tools Used
- Python
- Jupyter Notebook
- Quantum computing frameworks or simulations (conceptual / simulator-based)
- Classical ML concepts (SVM, kernels, margin optimization)
- Note: The project primarily focuses on conceptual understanding and experimentation using simulations rather than execution on real quantum hardware.



## Models Compared

- **Classical SVM**  
  Standard support vector machine implemented using classical machine learning techniques.

- **Quantum SVM (QSVM)**  
  SVM model using quantum feature maps and quantum kernel estimation, executed via simulation
  on classical hardware.

- **Hybrid Quantum–Classical SVM**  
  A hybrid approach where quantum circuits are used for feature encoding or kernel computation,
  while classical optimization handles training and inference.



## Evaluation Criteria

The models are evaluated and compared based on:
- Classification accuracy
- Training and inference time
- Scalability with dataset size
- Computational overhead introduced by quantum simulations



## Observations & Insights

QSVMs provide an intuitive framework for understanding how quantum kernels differ from classical kernels.
Quantum feature spaces grow exponentially with the number of qubits, offering theoretical representational advantages.
Practical deployment is currently constrained by:
- Limited qubit counts
- Noise in NISQ (Noisy Intermediate-Scale Quantum) devices
- Data encoding overhead



## Purpose
This repository is intended as a conceptual and experimental exploration of QSVMs rather than a production-ready system.
