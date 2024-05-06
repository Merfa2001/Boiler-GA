### Objective Function
The objective function \( f(x) \) is defined as follows:
\[ f(x) = 0.6224 x_1 x_3 x_4 + 1.7781 x_2 x_3^2 + 3.1661 x_1^2 x_4 + 19.84 x_2^2 x_3 \]
The goal is to find values for \( x_1 \), \( x_2 \), \( x_3 \), and \( x_4 \) that minimize this function.

### Constraints
There are four constraints \( g_1(x) \) to \( g_4(x) \):
1. \( g_1(x) = -x_1 - 0.0193x_3 \leq 0 \)
2. \( g_2(x) = -x_2 - 0.00954x_3 \leq 0 \)
3. \( g_3(x) = -\pi x_3^2 x_4 - \frac{4}{3} \pi x_3^3 + 1296000 \leq 0 \)
4. \( g_4(x) = x_4 - 240 \leq 0 \)

### Variable Bounds
Variables also must be within certain bounds:
- \( 0 < x_i < 100 \) for \( i = 1, 2 \)
- \( 10 < x_i < 200 \) for \( i = 3, 4 \)

### Provided Image
The image likely represents a mechanical system, which could be a depiction of part of the problem, possibly related to variables like \( x_3 \) and \( x_4 \) that appear to play dimensional mechanical roles such as radius or length.

![326289572-cd3aad40-cbe2-47b6-b7f0-7b11a17e6a66](https://github.com/Merfa2001/Boiler-GA-Pso/assets/146805956/1890c087-ac65-47c2-b2dc-02611cf53688)


### Solution Approach
This type of problem is typically solved using nonlinear optimization methods, which could include numerical methods like gradient descent algorithms, evolutionary algorithms, or utilizing specialized software such as MATLAB or Python with libraries like SciPy. We will solve this problem using the genetic algorithm and PSO.

---
