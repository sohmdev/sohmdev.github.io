---
title: "Fundamentals: Part 1"
date: 2023-11-22 00:00:00 +/0800
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

Below is a summary of my notes regarding this topic

# Linear Algebra
## Unit 1: Vectors and spaces

Vectors are used to represent many things around us: from forces like gravity, acceleration, friction, stress and strain on structures, to computer graphics used in almost all modern-day movies and video games. Vectors are an important concept, not just in math, but in physics, engineering, and computer graphics, so you're likely to see them again in other subjects.

#### Vectors
A Vector ($$\vec{a}$$) has Magnitude and Direction\
  Magnitude = length (is a scalar)\
\
Notation Examples:\
$$\vec{a} = (3, 4)$$,  $$\vec{a} = \begin{bmatrix} 3 \\ 4 \end{bmatrix}$$
\
Vector Plot:\
![Vector Example](/assets/img/2023-11-22-fundamentals-part1/Vector1.png)\
\
\
#### Real Coordinate Spaces
Represents all possible real values tupled to the nth dimension

Notation Examples:\
$$R^2$$ = 2D real coordinate space, $$\begin{bmatrix} 0 \\ 0 \end{bmatrix}$$
\
$$R^3$$ = 3D real coordinate space, $$\begin{bmatrix} 0 \\ 0 \\ 0 \end{bmatrix}$$
\
$$R^n$$ = n-Dimensional real coordinate space
\
$$\vec{x} \in R^2$$ = Vector is a set of real valued 2-tuples\
The tuples have to contain real values and not variables; i.e. $$\begin{bmatrix} i \\ 0 \end{bmatrix}$$ is not in the Real Coordinate Space

### Adding Vectors

