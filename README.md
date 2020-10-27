# TDK_2020
The necessary files for 'Self-Learning Control of a Mechatronic System Using Gaussian Process'

This repository contains the matlab scripts, functions and data files that are presented in the document 'Self-Learning Control of a Mechatronic System Using Gaussian Process', written for the BME Scientific Conference of Students 2020.

Abstract

Nowadays due to the increased computational power of modern computer architectures machine learning algorithms are becoming widely used in several fields of science and technology. Most of these learning algorithms are adaptive, i.e. they can adjust their behaviour based on the data collected during operation. Machine learning has been shown to give advantages in cases such as email filtering, computer vision or autonomous vehicle control, but also provides alternative methods for the mechanical design of beam structures, to mention a few application areas.

Due to tractability and solid theoretical background, linear models are widely used in the field of control engineering. However, most physical and mechanical systems are inherently non-linear, therefore a linear structure is not sufficient to describe their dynamical behaviour over the entire operating domain. Typical nonlinearities in mechatronic systems are non-linear friction effects, magnetic saturation, etc.

In this work, we propose to use the fusion of an augmented model based on Gaussian processes (GPs), and model predictive control (MPC), resulting in a self-learning MPC paradigm. This state-of-the-art approach uses collected data for compensating model uncertainties, complex non-linear effects and machine specific properties. It provides adaptability, safety guarantees, and has computationally efficient implementations (e.g. constrained non-linear multi-variable function minimizer). Two different self-learning methods are demonstrated. Firstly, an explicit MPC approach based on reinforcement learning. This method has the advantage of fewer run-time calculations due to off-line optimization, which makes it feasible with high sampling frequencies. However, not all necessary safety guarantees are provided during operation. The second approach, on-line GPMPC is able to calculate real-time optimal control inputs while satisfying all constraints. Although it has higher computational cost, the result is a self-learning advanced control method with safety guarantees.

The capabilities of the provided control methods are demonstrated on a self-designed cart-pole system built from of an inkjet printer mechanism. Based on measurements, the  actual system is significantly different from the corresponding mechanical model, which implies the use of data based, self-learning control methods.
