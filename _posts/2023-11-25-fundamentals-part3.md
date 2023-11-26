---
title: "Fundamentals: Part 3"
date: 2023-11-25 00:00:00 +/0800
categories: [fundamentals]
tags: [fundamentals, basics, linear algebra]     # TAG names should always be lowercase
math : true
---

# Fundamentals:
The first section of the AI Expert Roadmap focuses on the Fundamentals:
- Basics
- Python Programming
- Data Sources
- Exploratory Data Analysis / Data Mungling / - Wrangling


# Fundamentals: Basics
We are at the very first stop on our journey: [_Fundamentals > Basics > Matrices & Linear Algebra Fundamentals_](https://www.khanacademy.org/math/linear-algebra)

Below is a summary of my notes regarding this topic - Part 3

# Linear Algebra
## Unit 1: Vectors and spaces

#### Parametric Representation of lines

**2D Example**\
$$\vec{a} = \begin{bmatrix} 2 \\ 1 \end{bmatrix}$$\
$$\vec{b} = \begin{bmatrix} 0 \\ 3 \end{bmatrix}$$

L represents a line

L = {$\vec{b}$ + t($\vec{b} - \vec{a}$) \| t $\in R$}\
L = $$\begin{bmatrix} 0 \\ 3 \end{bmatrix}$$ + t $$\begin{bmatrix} -2 \\ 2 \end{bmatrix}$$

Parametric Form:\
X = 0 + (-2t) = -2t\
Y = 3 + 2t = 2t + 3

**3D Example**\
$$P_{1} = \begin{bmatrix} -1 \\ 2 \\ 7 \end{bmatrix}$$\
$$P_{2} = \begin{bmatrix} 0 \\ 3 \\ 4 \end{bmatrix}$$\
These are planes not lines; X + Y + Z = plane

L represents a line

L = {$P_{1}$ + t($P_{1} - P_{2}$) \| t $\in R$}\
L = $$\begin{bmatrix} -1 \\ 2 \\ 7 \end{bmatrix}$$ + t $$\begin{bmatrix} -1 \\ -1 \\ 3 \end{bmatrix}$$

Parametric Form:\
X = -t - 1\
Y = -t + 2\
Z = 3t + 7

#### Linear Combinations and spans

Linear combinations are variables (real numbers)\
$$V_{1}, V_{2}, V_{3}, ... V_{n} \in R^n$$\
$$C_{1}V_{1}, C_{2}V_{2}, C_{3}V_{3}, ... C_{n}V_{n}$$

Example:\
$$\vec{a} = \begin{bmatrix} 1 \\ 2 \end{bmatrix}$$, $$\vec{b} = \begin{bmatrix} 0 \\ 3 \end{bmatrix}$$\
$$0*\vec{a} + 0*\vec{b} = \begin{bmatrix} 0 \\ 0 \end{bmatrix}$$\
$$3*\vec{a} + -2*\vec{b} = \begin{bmatrix} 3 \\ 0 \end{bmatrix}$$

span \($$\vec{a} , \vec{b}$$\) = $$R^2$$ (not always)\
span \($$\vec{0}$$\) = 0

Example:\
$$\vec{a} = \begin{bmatrix} 1 \\ 2 \end{bmatrix}$$ + $$\vec{b} = \begin{bmatrix} 0 \\ 3 \end{bmatrix}$$ = $$\vec{x} = \begin{bmatrix} x_{1} \\ x_{2} \end{bmatrix}$$\
$$c_{1}\vec{b} + c_{2}\vec{b} = \vec{x}$$\
$$1c_{1} + 0c_{2} = x_{1}$$\
$$2c_{1} + 3c_{2} = x_{2}$$

I'm not sure why this works but if yo miultiple the $$x_{1}$$ line by -2 you can solve for $$c_{1}$$ and $$c_{2}$$

$$-2c_{1} + 0 = -2x_{1}$$\
$$2c_{1} + 3c_{2} = x_{2}$$

These two net out...

$$3c_{2} = x_{2} -2x_{1}$$\
$$c_{2} = 1/3(x_{2} - 2x_{1})$$\
$$c_{1} = x_{1}$$

So now if we wanted to solve for $$\begin{bmatrix} 2 \\ 2 \end{bmatrix}$$\
$$c_{1} = 2$$\
$$c_{2} = 1/3(2 - (2*2)$$ aka -2/3\
$$2\vec{a} - 2/3\vec{b} = \begin{bmatrix} 2 \\ 2 \end{bmatrix}$$











