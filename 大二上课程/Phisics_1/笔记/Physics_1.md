# Physics_1

## 2.3 Acceleration

### Acceleration

- When a particle's velocity changes, the particle is said to undergo **acceleration**.

- For motion along an axis, the **average acceleration** $a_{avg}$ over a time interval $\Delta t$ is:
    $$
    a_{avg} = \dfrac{v_2 - v_1}{t_2 - t_1} = \dfrac{\Delta v}{\Delta t}
    $$
    

     where the particle has velocity $v_1$ at time $t_1$ and then velocity $v_2$ at time $t_2$ 

- The instantaneous acceleration is:
    $$
    a = \dfrac{dv}{dt}
    $$

- The acceleration of  a particle at any instant is the second derivative of its position $x(t)$ with respect to time.
    $$
    a = \dfrac{dv}{dt} = \dfrac{d}{dt}(\dfrac{dx}{dt}) = \dfrac{d^2x}{dt^2}
    $$

- Acceleration has both magnitude and direction. Its algebraic sign represents its direction on an axis just as for displacement and velocity; that is, acceleration with a positive value in the positive direction of an axis, and acceleration with a negative value is in the negative direction.

## 2.4 constant acceleration 

### Constant acceleration: a special case 

- When the acceleration is constant, the average acceleration and instantaneous acceleration are equal: 
    $$
    a = a_{avg} = \dfrac{v - v_0}{t - 0}
    $$
    $v_0$ is the velocity at time $t = 0$ and $v$ is the velocity at any later time $t$. We can recast this equation:
    $$
    v = v_0 + at
    $$

- $$
    v_{avg} = \dfrac{x - x_0}{t - 0}
    $$

    and then as 
    $$
    x = x_0 + v_{avg}t
    $$
    in which $x_0$ is the position of the particle at $t = 0$ and $v_{avg}$ is the average velocity between $t = 0$ and a later time $t$ 

- $$
    v_{avg} = \dfrac{1}{2}(v_0 + v) = v_0 + \dfrac{1}{2}at
    $$

finally, we get 
$$
x - x_0 = v_0t + \dfrac{1}{2}at^2
$$
these equations can be used to solve any **constant acceleration** problems.
$$
v^2 = v_0^2 + 2a(x - x_0)
$$

## 2.5 Free-Fall Acceleration 

### Free-Fall acceleration 

- The value of $g$ values slightly with latitude and with elevation.

## 2.6 Graphical integration in motion analysis

### Graphical integration in motion analysis

- $$
    v_1 - v_0 = \int_{t_0}^{t_1} a dt
    $$

- $$
    x_1 - x_0 = \int_{t_0}^{t_1} v dt
    $$

## 3.1 Vectors and Their Components

- A **vector** has magnitude as well as direction.
- A **vector quantity** is a quantity that has both a magnitude and a direction and thus can be represented with a vector. Displacement, velocity, and acceleration are vector quantities.
- A vector can be shifted without changing its value if its length and direction are not changed.

### Adding vectors geometrically

- The order of vector addition doesn't matter
    $$
    \vec{a} + \vec{b} = \vec{b} + \vec{a}
    $$

- When there are more than two vectors, we can group them in any order as we add  them.
    $$
    (\vec{a} + \vec{b}) + \vec{c} = \vec{a} + (\vec{b} + \vec{c})
    $$

- The vector $-\vec{b}$ is a vector with the same magnitude as $\vec{b}$ , but the opposite direction.
    $$
    \vec{b} + -\vec{b} = \vec{0}
    $$

## Components of Vectors

- A **component** of a vector is the projection of the vector on an axis.

- The projection of a vector on an $x$ axis is its $x$ component, and similarly, the projection on the $y$ axis is the $y$ component.

- The process of finding a component of a vector is called **resolving a vector**.

- $$
    a_x = a cos\theta\ \ and\ \ \ a_y = asin\theta
    $$

- 

where $\theta$ is the angle that the vector $\vec{a}$ makes with the positive direction of the $x$ axis, and a is the magnitude of $\vec{a}$.

- If we know a vector in component notation($a_x\ \ and \ \ a_y$) and want it in magnitude angle notation($a \ \ and \ \ \theta$) , we can use the equation:
    $$
    a = \sqrt{a^2_x + a^2_y}
    \ \ 
    and 
    \ \ 
    tan\theta = \dfrac{a_y}{a_x}
    $$
    

## 3.2 Unit vectors, adding vectors by components

### Unit Vectors

- a **unit vector** is a vector that has a magnitude of exactly 1 and point in a particular direction.
- the unit vectors in the positive directions of the $x, y$ and $z$ axes are labeled $\hat{\mathbf{i}}$, $\hat{\mathbf{j}}$, $\hat{\mathbf{k}}$ 

#### Adding vectors by components

## 3.3 Multiplying Vectors

- There are two ways to multiply a vector by a vector: one way produce a scalar (called the scalar product), and the other produces a new vector (called the vector product)

- The **scalar product** of the vector $\vec{a}$ and $\vec{b}$ is written as $\vec{a}\cdot \vec{b}$ and defined to be: 
    $$
    \vec{a}\cdot\vec{b} = ab\ cos\phi
    $$

- 

where $a$ is the magnitude of $\vec{a}$ , $b$ is the magnitude of $\vec{b}$, and $\phi$ is the angle between the direction of $\vec{a}$ and $\vec{b}$. Because the notation,  $\vec{a}\cdot\vec{b}$ is also known as the **dot product**.

- The **vector product** of $\vec{a}$ and $\vec{b}$ , written $\vec{a}\times\vec{b}$ , produces a third vector $\vec{c}$ whose magnitude is:
    $$
    c = ab\ sin\phi
    $$

where $\phi$  is the smaller of the two angles between $\vec{a}$ and $\vec{b}$. Because of the notation, $\vec{a}\times\vec{b}$ is also known as the cross product, and in speech it is $\vec{a}$ cross $\vec{b}$.

- The order of vector multiplication is important
    $$
    \vec{b}\times\vec{a} = - (\vec{a}\times\vec{b})
    $$

In other word, the commutative law does not apply to a vector product.

- In unit-vector notation, we write
    $$
    \vec{a}\times\vec{b} = (a_x \hat{\mathrm{i}} + a_y \hat{\mathrm{j}} + a_z \hat{\mathrm{k}}) \times (b_x \hat{\mathrm{i}} + b_y \hat{\mathrm{j}} + b_z \hat{\mathrm{k}})
    $$

which can be expanded according to the distributive law
$$
a_x \hat{\mathrm{i}} \times b_x \hat{\mathrm{i}} = a_x b_x (\hat{\mathrm{i}} \times \hat{\mathrm{i}}) = 0,\\
a_x \hat{\mathrm{i}} \times b_y \hat{\mathrm{j}} = a_x b_y (\hat{\mathrm{i}} \times \hat{\mathrm{j}}) = a_x b_y \hat{\mathrm{k}}.
$$

## 4.1 Position and displacement 

### Position and displacement

- one general way of locating a particle is with a **position vector** $\vec{r}$ , which is a vector that extends from a reference point (usually the origin) to the particle. In the unit-notation $\vec{r}$ can be weritten:
    $$
    \vec{r} = x \hat{\mathrm{i}} + y \hat{\mathrm{j}} + z \hat{\mathrm{k}}
    $$

where \( x\hat{\mathrm{i}} \), \( y\hat{\mathrm{j}} \), and \( z\hat{\mathrm{k}} \) are the vector components of \(\vec{r}\), and the coefficients \( x \), \(y\), and \(z\) are its scalar components.

## 4.2 average velocity and instantaneous velocity

### Average velocity and instantaneous velocity

- If a particle moves through a displacement $\Delta \vec{r}$ in a time interval $\Delta t$, then its **average velocity** is: 

$$
\vec{v}_{avg} = \dfrac{\Delta\vec{r}}{\Delta t }
$$

this tells us the direction of $\vec{v}_{avg}$ must be the same as the displacement $\Delta\vec{r}$

- **instantaneous velocity**: 
    $$
    \vec{v} = \dfrac{d\vec{r}}{dt}
    $$

- $$
    \vec{v} = \frac{d}{dt} \left( x \hat{\mathrm{i}} + y \hat{\mathrm{j}} + z \hat{\mathrm{k}} \right) = \frac{dx}{dt} \hat{\mathrm{i}} + \frac{dy}{dt} \hat{\mathrm{j}} + \frac{dz}{dt} \hat{\mathrm{k}}.
    $$

    This equation can be simplified somewhat by writing it as
    $$
    \vec{v} = v_x \hat{\mathrm{i}} + v_y \hat{\mathrm{j}} + v_z \hat{\mathrm{k}} 
    $$
     where the scalar components of $\vec{v}$ are 
    $$
    v_x = \frac{dx}{dt}, \quad v_y = \frac{dy}{dt}, \quad \text{and} \quad v_z = \frac{dz}{dt}.
    $$

    ## 4.5 Uniform Circular motion

    ### Uniform circular motion

- a particle is in **uniform circular motion** if it travels around a circle or a circular arc at constant speed. The speed does not vary, however, the velocity change in direction.

- The velocity is always directed tangent to the circle in the direction of motion.

- The acceleration associated with uniform circular motion is called a **centripetal acceleration**. The magnitude of this acceleration is: 
    $$
    a = \dfrac{v^2}{r}
    $$

where $r$ is the radius of the circle, and $v$ the speed of the particle.

- The particle travels the circumference of the circle (a distance of $2\pi$) in time: 
    $$
    T = \dfrac{2\pi r}{v}
    $$

$T$ is called the period of revolution.

