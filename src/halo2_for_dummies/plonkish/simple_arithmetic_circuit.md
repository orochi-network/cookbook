# A Simple Arithmetic Circuit
Let \\(\mathbb{F}\\) be some finite field. We would like to show in this section the transformation from the program computing polynomial \\(f(u, v) = u^2 + 3uv + v + 5 \\) where \\(u, v \in \mathbb{F}\\). With inputs \\(u, v \in \mathbb{F}\\), the arithmetic circuit for this polynomial is equivalently represented by topologically following the sequence of computations below.
1. Compute \\(u^2\\).
2. Compute \\(uv\\).
3. Compute \\(3uv\\).
4. Compute \\(u^2 + 3uv\\).
5. Compute \\(u^2 + 3uv + v\\).
6. Compute \\(u^2 + 3uv + v + 5\\).

