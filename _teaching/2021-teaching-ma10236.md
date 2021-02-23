---
title: "MA10236: Methods and Applications 1B"
collection: teaching
type: "Undergraduate course"
permalink: /teaching/ma10236
venue: "University of Bath, Online"
date: 2021-01-29
location: "Bath, UK"
---

This page is for the 2020/21 Semester 2 module MA10236: Methods and Applications 1B. 

Deadlines and Tutorial Info
======

Please submit your homework to me via moodle, weekly before Wednesday at 9AM (GMT). The tutorials are held weekly on zoom at the times described below. Please email me if you are going to miss a tutorial or can't make this homework deadline if you require an extension. 
- A2: Fridays 12:15
- A3: Fridays 13:15

Week 1
======

* Vectors
    * Magnitude and direction \$\mathbf{a}\$.
    * Directed line segment characterized by two ordered points. \$\overrightarrow{PQ}\$.
    * Norm: \$ \Vert \mathbf{a}\Vert = \sqrt{\sum a_i^2} \$ OR length of the line segment. 
        * This is a scalar quantity (just magnitude, no direction)
    * If \$\mathbf{a} = \overrightarrow{PQ}\$, then \$-\mathbf{a} = \overrightarrow{QP}\$. 


Week 2
======
* Vector addition and vector-scalar multiplication 
    * \$ \mathbf{a} + \mathbf{b} = \mathbf{b} + \mathbf{a} \$ 
    * \$ (\mathbf{a} + \mathbf{b}) + \mathbf{c} = \mathbf{a} + (\mathbf{b} + \mathbf{c}) \$ 
    * \$ \mathbf{a} + \mathbf{0} = \mathbf{0} + \mathbf{a} = \mathbf{a} \$
    * \$ \mathbf{a} + (-\mathbf{a}) = \mathbf{0} \$
    * \$ \lambda( \mu \mathbf{a}) = (\lambda \mu \mathbf{a})\$
    * \$\lambda( \mathbf{a} + \mathbf{b}) = \lambda\mathbf{a} + \lambda \mathbf{b} \$
    * \$ (\lambda + \mu) \mathbf{a} = \lambda \mathbf{a} + \mu \mathbf{a} \$
* Unit vector \$\hat{\mathbf{a}} = \frac{\mathbf{a}}{\Vert\mathbf{a}\Vert}\$
* Projection
    * For two vectors \$ \mathbf{a}, \mathbf{b}\$, \$\mathbf{b}\$ can be described as a projection on \$\mathbf{a}\$, which we can denote \$ \mathbf{b}\_{\Vert}\$ (  the part of \$\mathbf{b}\$ parallel to \$\mathbf{a}\$) and a perpendicular component denoted \$ \mathbf{b}\_{\perp}\$. )
    * \$ \mathbf{b}_{\Vert} = \Vert\mathbf{b}\Vert \cos(\theta)\$ where \$ \theta\$ is the angle between \$\mathbf{a}\$ and \$\mathbf{b}\$. 
* Dot product
    * \$ \mathbf{a} \cdot \mathbf{b} = \sum a_i b_i = \Vert\mathbf{a}\Vert \Vert\mathbf{b} \Vert \cos(\theta)\$. 
    * equal to zero when the vectors are perpendicular. 
    * \$ \mathbf{a} \cdot \mathbf{a} = \Vert\mathbf{a}\Vert^2 \$
    * returns a scalar value. 
* Cross product
    * \$ \mathbf{a} \times \mathbf{b}\$ returns a vector which is orthogonal to both \$ \mathbf{a} \$ and \$ \mathbf{b}\$. 
    * a vector cross producted with itself returns the zero vector. 
    * \$ \Vert \mathbf{a} \times \mathbf{b} \Vert \$ gives the area of the parallelogram spanned by \$ \mathbf{a}\$ and \$\mathbf{b}\$.
    * \$ \Vert \mathbf{a} \times \mathbf{b} \Vert = \Vert\mathbf{a} \Vert \Vert \mathbf{b}\Vert \sin(\theta)\$ 
    * If equal to zero, the two vectors are parallel. 
    * Is the determinant of the matrix whose rows are the cartesian spanning vectors, \$ \mathbf{a}\$, and \$\mathbf{b}\$ respectively.

Week 3
======

* Scalar triple product 
    * \$\[\mathbf{a},\mathbf{b},\mathbf{c}\] = \mathbf{a}\cdot( \mathbf{b}\times \mathbf{c})\$
    * The scalar triple product calculates the volume of the parallelepiped spanned by the three vectors. 
    * When it's \$0\$ the three vectors are coplanar. 
        * Note: Three vectors are coplaner if there exists three scalars \$  \lambda, \mu, \nu \$ with \$\lambda^2 + \mu^2 + \nu^2 >0\$ such that \$ \lambda \mathbf{a} + \mu \mathbf{b} + \nu \mathbf{c} = \mathbf{0}$. 
    * It's the same up to cyclic permutations, but swaps sign when only two swap places. 
    * If any two of the vectors in the scalar triple products are the same, it's equal to zero (see coplanar). 
    * \$\lambda \[\mathbf{a},\mathbf{b},\mathbf{c}\] = \[\lambda \mathbf{a},\mathbf{b},\mathbf{c}\] \$
* vector triple product
    * \$ \mathbf{a}\times(\mathbf{b}\times \mathbf{c}) = (\mathbf{c}\cdot \mathbf{a}) \mathbf{b} - (\mathbf{b}\cdot \mathbf{a})\mathbf{c}\$.
    * \$ \mathbf{a}\times(\mathbf{b}\times \mathbf{c}) \ne  (\mathbf{a}\times\mathbf{b})\times \mathbf{c} \$ (Not associative!!).
* Equation of a straight line 
    * If a line is defined with \$\mathbf{r} = \mathbf{a} + \lambda \mathbf{l}\$ then it can be throught of as the line passing through \$\mathbf{a}\$ in the direction given by $\mathbf{l}\$, then each point on the line is given by a different value of the scale parameter \$\lambda\$. 
    * Alternate form: \$ (\mathbf{r} - \mathbf{a}) \times \mathbf{l} = \mathbf{0}$. 
    * Two lines ( $\mathbf{r} = \mathbf{a}+\lambda \mathbf{l}\$, \$\mathbf{r} = \mathbf{b} + \mu \mathbf{m}\$) intersect iff \$\[\mathbf{a},\mathbf{l},\mathbf{m}\]  = \[\mathbf{b},\mathbf{l},\mathbf{m}\] \$. 
        * This can be used to find common perpendiculars to two lines. 
