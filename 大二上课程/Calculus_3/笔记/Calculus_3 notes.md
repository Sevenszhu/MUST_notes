# Calculus_3 notes

  # 11 Vector and Geometry of Space 



### 11.1 Three-Dimensional Coordinate System

- **the Cartesian coordinate of a point $P(x, y, z)$ in space**: the values at which the planes through P perpendicular to the axes cut the axes.(Also called **rectangular coordinates**)

- The three coordinate planes $x = 0, y = 0, z = 0$ divide space into eight cells called **octants**.

- **The distance  between $P_1(x_1, y_1, z_1)$** and $P_2(x_2, y_2, z_2)$ 

    $|P_1P_2| = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2 + (z_2 - z_1)^2}$

- The standard equation for the sphere of radius $a$ and the center $P(x_0, y_0, z_0)A$

    $(x - x_0)^2 + (y - y_0)^2 + (z - z_0)^2 = a^2$

### 11.2 Vectors

- **vector **: a quantity that have both magnitude and direction. It is represented by a **directed line segment**.(The length of the line segment is the magnitude of the vector)
- The vector represented by the directed line segment $\overrightarrow{AB}$ has **initial point** $A$ and **terminal point** $B$ , and its **length** is denoted by   $|\overrightarrow{AB}|$ .
- Two vectors are **equal** if they have the same length and direction. (regardless of the initial point)
- **Standard position of vector $\vec{v}$**: If $\vec{v} = \overrightarrow{PQ}$ , and there is one directed line segment equal to $\overrightarrow{PQ}$ whose initial point is the origin. Then, it is the representative of $\vec{v}$ in standard position and is the vector we normally use to represent $\vec{v}$.
- If $\vec{v}$ is a **two-dimensional** vector in the plane equal to the vector with initial point at the origin and terminal point $(v_1, v_2)$, then the **component form** of $\vec{v}$ is 

  $$\vec{v} = <v_1, v_2>$$
- If $\vec{v}$ is a **three-dimentional** vector eequal to the vector with initial point at the origin and terminal point $(v_1, v_2, v_3)$, then the **component form$ of $\vec{v}$ is
$$v = <v_1, v_2, v_3>$$
- Given the point $P(x_1, y_1, z_1)$ and $Q(x_2, y_2, z_2)$, the standard position vector $\vec{v} = <v_1, v_2, v_3>$ equal to $\overrightarrow{PQ}$ is
$$\vec{v} = <x_2 - x_1, y_2 - y_1, z_2 - z_1>$$
*there is no third component for planar vectors*

- The **magnitude or length** of the vector $\overrightarrow{PQ}$ is the length of any of its equivalent directed line segment representations.

- **Zero vector**: The only vector with length 0. This vector is also the only vector with no specific direction.

- **Scalar**: simply a real number, we call it a scalar, when we want to draw attention to the difference between numbers and vectors.

- Let $\vec{u}  = <u_1, u_2, u_3>$ and $\vec{v}  = <v_1, v_2, v_3>$ be vector with $k$ a scalar

    - **Addition**: $\vec{u} + \vec{v} = <u_1 + v_1, u_2 + v_2, u_3 + v_3>$
        - we add vectors by adding the corresponding components of the vectors.
    - **Scalar multiplication**: $k\vec{u} = <ku_1, ku_2, ku_3>$
        - we multiply a vector bu multiplying each component by scalar.

    - The definition also apply to planar vectors.

- $|k\vec{u}| = |k||\vec{u}|$  

- **unit vector**: a vector $\vec{v}$ of length 1.

- **standard unit vector**: $i = <1, 0, 0>, j = <0, 1, 0>, k = <0, 0, 1>$

- $\vec{v} = <v_1, v_2, v_3> = v_1<1, 0, 0> + v_2<0, 1, 0> + v_3<0, 0, 1> = v_1\vec{i} + v_2\vec{j} + v_3\vec{k}$

    we call the scalar $v_1$ the i-component of vector $\vec{v}$, $v_2$ the j-component, $v_3$ the k-component. 

- If the vector $\vec{v}$ is not the zero vector, then $\dfrac{\vec{v}}{|\vec{v}|}$ is the **unit vector in the direction of** $\vec{v}$, and it is also called the **direction of** $\vec{v}$

- The equation $\vec{v} = |\vec{v}| \dfrac{\vec{v}}{|\vec{v}|}$ expresses $\vec{v}$ as its length times its direction.

- The **midpoint** $M$ of the line segment joining points $P_1(x_1, y_1, z_1)$ and $P_2(x_2, y_2, z_2)$ is the point (found by averaging):

    $(\dfrac{x_1 + x_2}{2}, \dfrac{y_1 + y_2}{2}, \dfrac{z_1 + z_2}{2})$

### The dot product

- When two nonzero vector $\vec{u}$ and $\vec{v}$ are placed so their initial points coincide, they form an angle $\theta$ of measure $0 \le \theta \le \pi$ . (The angle $\theta$ is the **angle between** $\vec{u}$ and $\vec{v}$.) 

- vector $\vec{u}$  and $\vec{v}$  are orthogonal if $\vec{u}\cdot\vec{v} = 0$ 

- The **vector projection** of $\vec{u} = \overrightarrow{PQ}$ onto a nonzero vector $\vec{v} = \overrightarrow{PS}$  is the vector $\overrightarrow{PR}$ determined by dropping a perpendicular from $Q$ to the line $PS$. the notation for this vector is: 

    $proj_{\vec{v}}\vec{u}$ (The vector projection of $\vec{u}$ onto $\vec{v}$)
