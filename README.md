# Set Cover Problem Solutions

This repository explores various algorithms to solve the **Set Cover Problem**, which aims to cover a universe of elements with the minimum number of sets. The implemented solutions include:

- **Greedy Algorithm**: Iteratively selects sets that cover the most uncovered elements at the lowest cost.
- **Hill Climbing**: Uses single and multiple tweaks to iteratively improve the solution.
- **Tweak and Restart**: Randomly restarts and tweaks solutions until an optimal one is found.

Key metrics like cost, validity, and iterations are tracked using the `icecream` library.
