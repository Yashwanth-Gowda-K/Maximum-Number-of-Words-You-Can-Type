# Maximum-Number-of-Words-You-Can-Type


## 🧠 Problem Approach
1. **Splitting Logic:** Split input text into words using `text.split()`  
2. **Efficient Checks:** Convert `brokenLetters` to a **set** for O(1) lookups  
3. **Validation:** Count words containing no broken characters  

## ⚡ Time Complexity
- **O(n * m)** where:  
  - `n` = number of words  
  - `m` = average word length  
*(Optimal for this problem!)*  
