# Optimisation-Essaim-Particulaire-PSO
# Particle Swarm Optimization (PSO)

Particle Swarm Optimization (PSO) is an optimization technique proposed and developed in the 1990s by R. Eberhart and J. Kennedy. It is based on the collaboration of a certain number of individuals. The number of individuals depends on the optimization problem being solved. PSO shares similarities with techniques based on ant colonies.

## Principle

Through basic movement rules, particles (individuals) are encouraged to converge towards a global optimum. At initialization, each particle is randomly positioned in the search space of the problem. The algorithm's evolution, moving the particles, is described by the following two equations:

\[
V_{k+1} = \rho V_k + b_1 \times (P_i - X_k) + b_2 \times (P_g - X_k)
\]

\[
X_{k+1} = X_k + V_{k+1}
\]


Where:
- \( V_k \): the current velocity of particle \( k \)
- \( P_i \): its best solution
- \( P_g \): the best solution of its neighborhood or the swarm
- \( X_k \): the current position of particle \( k \)
- \( \rho \): inertia, and \( b_1 \) and \( b_2 \) randomly drawn values.

## Usage

To use PSO for your optimization problem, you need to initialize the particles, define the movement equations, and set the parameters \( \rho \), \( b_1 \), and \( b_2 \). You can adjust these parameters based on the characteristics of your optimization problem.
