---
title: "Fundamentals: Part 2"
date: 2023-11-24 00:00:00 +/0800
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

Below is a summary of my notes regarding this topic - Part 2

# Linear Algebra
## Unit 1: Vectors and spaces

#### Multiplying Vectors by a Scalar

A scalar is just a number; i.e. 1, 2, 3, etc.

Example 1:\
$$\vec{a} = \begin{bmatrix} 2 \\ 1 \end{bmatrix}$$\
3 * $$\vec{a} = 3 * \begin{bmatrix} 2 \\ 1 \end{bmatrix} = \begin{bmatrix} 3 * 2 \\ 3 * 1 \end{bmatrix} = \begin{bmatrix} 6 \\ 3 \end{bmatrix}$$
\
Vector Plot:\
![Vector Example](/assets/img/2023-11-24-fundamentals-part2/Vector1.png)\
The direction remains the same however, the magnitude has grown/scaled by 3

Example 2:\
$$\vec{a} = \begin{bmatrix} 2 \\ 1 \end{bmatrix}$$\
-1 * $$\vec{a} = -1 * \begin{bmatrix} 2 \\ 1 \end{bmatrix} = \begin{bmatrix} -1 * 2 \\ -1 * 1 \end{bmatrix} = \begin{bmatrix} -2 \\ -1 \end{bmatrix}$$
\
Vector Plot:\
![Vector Example](/assets/img/2023-11-24-fundamentals-part2/Vector2.png)\
The direction has changed however, the magnitude remains the same

When a vector starts from the standard position it is starting from (0,0)

If $$\vec{x} = 80^\circ; -1/2 * \vec{x} = 260^\circ aka (80^\circ + 180^\circ)$$

#### Unit Vector Intro

Unit Vector Notation:\
$$\hat{i} = \begin{bmatrix} 1 \\ 0 \end{bmatrix}$$\
$$\hat{j} = \begin{bmatrix} 0 \\ 1 \end{bmatrix}$$

Example 1:\
$$\vec{v} = \begin{bmatrix} 2 \\ 3 \end{bmatrix}$$\
$$\vec{v} = (2, 3)$$  
$$\vec{v} = (2\hat{i}, 3\hat{j})$$

Vector Plot:\
![Vector Example](/assets/img/2023-11-24-fundamentals-part2/Vector3.png)\
$\vec{v}$ is represented by the red arrow\
In the image if we started the blue arrow at the end of the orange arrow it would point to (2,3)

Unit vector has a magnitude of 1

Finding unit vector for $$\vec{v}$$:\
$$a^2 + b^2 = c^2$$\
$$\sqrt{a^2 + b^2} = c$$\
$$\sqrt{2^2 + 3^2} = c$$\
$$\sqrt{4 + 9} = c$$\
$$\sqrt{13} = c$$ _(the magnitude of the vector)_\
$$(\frac{2}{\sqrt{13}}, \frac{3}{\sqrt{13}})$$ = Normalized Vector aka Unit Vector $$\hat{u}$$










