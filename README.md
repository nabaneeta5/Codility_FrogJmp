# Codility_FrogJmp
Count minimal number of jumps from position X to Y.

# Task description
A small frog wants to get to the other side of the road. The frog is currently located at position X and wants to get to a position greater than or equal to Y. The small frog always jumps a fixed distance, D.  Count the minimal number of jumps that the small frog must perform to reach its target.

# Link Details
[trainingS89MN8-JT7](https://app.codility.com/demo/results/trainingS89MN8-JT7/)

# Programming Language
Java SE 11

# Solution Code

```
class Solution {
    public int solution(int X, int Y, int D) {
        // write your code in Java SE 11

        int result=(int) Math.ceil((Y-X)/(double)D);

        return result;
    }
}

```


