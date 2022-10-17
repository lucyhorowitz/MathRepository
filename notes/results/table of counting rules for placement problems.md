Placing $n$ balls into $k$ cells:

| **distinguished balls?** | **distinguished cells?** | **empty cells?** | **number**                                          |
|--------------------------|--------------------------|------------------|-----------------------------------------------------|
| yes                      | yes                      | yes              | $k^n$                                               |
| yes                      | yes                      | no               | $k!S(n,k)$                                          |
| yes                      | no                       | yes              | $\sum\limits_{i=1}^k S(n,i)$                       |
| yes                      | no                       | no               | $S(n,k)$ by definition                              |
| no                       | yes                      | yes              | ${n+k-1\choose n}$                                  |
| no                       | yes                      | no               | ${n-1\choose k-1}$                                  |
| no                       | no                       | yes              | number of [[partition of an integer]] of $n$ into $k$ or fewer parts |
| no                       | no                       | no               | number of partitions of $n$ into exactly $k$ parts  |

The "yes/no/no" case serves as the definition of the [[Stirling numbers of the second kind]].

[[binomial theorem|]]