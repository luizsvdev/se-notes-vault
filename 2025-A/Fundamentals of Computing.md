
## 1. Number Bases and Mathematical Logic

### Transform Binary → Decimal
$$
D = \sum_{i=0}^{n} b_i \cdot 2^i
$$

###### Example:
$110101_2$
$$
D = 1 \cdot 2^5 + 1 \cdot 2^4 + 0 \cdot 2^3 + 1 \cdot 2^2 + 0 \cdot 2^1 +  1 \cdot 2^0
$$

$$
D = 32 + 16 + 0 + 4 + 0 + 1
$$

$$
D = 53_{10}
$$

### Transform Decimal → Binary
$$
b_i = \left\lfloor \frac{D}{2^i} \right\rfloor \mod 2
$$

###### Example:
$25_{10}$

$$
\begin{array}{c|c|c}
D & D \div 2 & D \mod 2 \quad (\text{Extracted bit}) \\
\hline
25 & 12 & 1 \quad (\text{LSB}) \\
12 & 6 & 0 \\
6 & 3 & 0 \\
3 & 1 & 1 \\
1 & 0 & 1 \quad (\text{MSB}) \\
\end{array}
$$

Final binary result (reading from bottom to top):
$$
25_{10} = 11001_2
$$