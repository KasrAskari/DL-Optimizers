# 🧠 Optimizer Visualization Playground

A lightweight visualization tool to compare and understand the behavior of various gradient-based optimization algorithms on a simple 2D convex function.

## 🚀 Overview

This project visualizes the optimization paths taken by different gradient-based optimizers such as:

* Gradient Descent (GD)
* Stochastic Gradient Descent (SGD)
* Momentum-based GD
* Nesterov Accelerated Gradient (NAG)
* AdaGrad
* RMSProp
* RMSProp with Nesterov
* Adam

Each optimizer is applied to the convex function `f(x1, x2) = x1² + 2x2²`, and the trajectory toward the global minimum is plotted.

## ✨ Features

* Visual comparison of optimizers on 2D contours.
* Implementation of both classic and modern optimizers.
* Modular and easy-to-extend class-based structure.
* Support for constant learning rate scheduling.

## 🛠️ Technologies Used

* Python 3.x
* NumPy
* Matplotlib
* Jupyter Notebook

## 📊 Results

Each optimizer is evaluated over a fixed number of iterations, and their movement paths are shown over a contour plot. Below is an example of how Gradient Descent and Adam navigate the loss surface:

<p align="center">
  <img src="path/to/sample_gd_vs_adam.png" width="500"/>
</p>

## 📜 License

This project is open-source and available under the MIT License.
