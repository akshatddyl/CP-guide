

---

# Competitive Programming Roadmap

Welcome to the **Competitive Programming (CP) Roadmap**! This guide is designed to take you from a beginner to an advanced level in competitive programming, covering essential topics, algorithms, and problem-solving techniques. Whether you're new to coding or looking to sharpen your skills, this roadmap provides a structured path with theory, practice problems, and resources.

**What is Competitive Programming?**  
Competitive Programming is a mind-sport where you solve algorithmic problems under time and resource constraints, combining problem-solving skills with efficient coding. It enhances logical thinking, analytical skills, and coding proficiency—plus, it’s fun and can boost your career prospects!

**Why Do It?**
- Builds logical and analytical thinking.
- Deepens algorithmic knowledge.
- Prepares you for coding interviews.
- Offers a thrilling challenge!

**Popular CP Platforms:**
- [Codeforces](https://codeforces.com/)
- [CodeChef](https://www.codechef.com/)
- [TopCoder](https://www.topcoder.com/)
- [AtCoder](https://atcoder.jp/)
- [LeetCode](https://leetcode.com/)
- [HackerRank](https://www.hackerrank.com/)

Let’s dive in!

---

## Table of Contents
1. [Section 0: Introduction](#section-0-introduction)
   - Getting Started
   - Basic Problem Solving
   - Time Complexity
   - Intro to STL
   - Sorting
   - Binary Search
   - Bit Operations
   - Primary Number Theory
   - Recursion
   - Complete Search
2. [Section 1: Basic Theory](#section-1-basic-theory)
   - Number Theory
   - Two Pointers / Sliding Windows
   - Range Queries
   - Divide and Conquer
   - Intro to Greedy Algorithms
   - Dynamic Programming
   - Interactive Problems
3. [Section 2: Intermediate](#section-2-intermediate)
   - Advanced Maths
   - Range Update Queries
   - Graph Theory Basics
   - DSU + MST
   - Shortest Path Algorithms
4. [Section 3: Advanced](#section-3-advanced)
   - String Hashing
   - Directed Graphs
   - Range Update Queries (Continued)
   - Sparse Table
   - Tree Algorithms
5. [Additional Topics](#additional-topics)
6. [Resources](#resources)

---

## Section 0: Introduction

This section lays the foundation for competitive programming, introducing basic concepts, tools, and problem-solving techniques.

### Getting Started

**Learn C++**
- **If you know C:** Read [Moving from C to C++](https://example.com).
- **No prior experience:**
  - **YouTube:**
    - [Bro Code: C++ Tutorial (first 5 hours)](https://example.com)
    - [FreeCodeCamp: C++ Course (first 3 hours)](https://example.com)
  - **Reading:**
    - [USACO: PAPS Chapter 2](https://example.com)
    - [Learn C++ (Intro & Functions)](https://example.com)

**Set Up Your Environment**
- **Recommended IDE:** Visual Studio Code (VS Code).
- **Alternatives:** Sublime Text, Code::Blocks.
- **Windows Setup:** Watch [VS Code Setup (0:01:27–0:08:40)](https://example.com).
- **Mac Setup:** Install VS Code from [code.visualstudio.com](https://code.visualstudio.com/) and configure GCC ([tutorial](https://example.com)).
- **Troubleshooting:** For issues with `#include<bits/stdc++.h>`, see [this guide](https://example.com).

**Register on Platforms**
- **CodeChef:** Solve beginner problems:
  - [GDTURN](https://www.codechef.com/problems/GDTURN)
  - [TAXES](https://www.codechef.com/problems/TAXES)
- **Codeforces:** Enroll in [ITMO Academy: Pilot Course](https://codeforces.com/edu/courses).

### Basic Problem Solving

**Your First Problems**
- **Codeforces:**
  - Register at [codeforces.com](https://codeforces.com/).
  - Solve [A+B?](https://codeforces.com/problemset/problem/1/A), [Triangular Numbers](https://example.com), [Morning](https://example.com).
  - Submit solutions via IDE or file upload.
- **CSES:**
  - Register at [cses.fi](https://cses.fi/).
  - Solve [Problem 1](https://cses.fi/problemset/task/1068).
- **SPOJ:**
  - Solve [TEST](https://www.spoj.com/problems/TEST/).
- **USACO:**
  - Register at [usaco.org](http://www.usaco.org/).
  - Solve [Mixing Milk](http://www.usaco.org/index.php?page=viewproblem2&cpid=855).
  - Use file I/O:  
    ```cpp
    freopen("mixmilk.in", "r", stdin);
    freopen("mixmilk.out", "w", stdout);
    ```

**Fast I/O (Optional)**
- Learn about fast input/output: [Stack Overflow](https://example.com) or [Fast I/O Guide](https://example.com).
- Practice: [SPOJ INOUTEST](https://www.spoj.com/problems/INOUTEST/).

**Basic Math Problems**
- [CF: Panoramix’s Prediction](https://example.com)
- [CF: System of Equations](https://example.com)
- [CF: GCD vs LCM](https://example.com)
- [CodeChef: Two Equations](https://example.com)

**Tips from the Makers**
- Practice consistently—daily practice trumps cramming.
- It’s okay to check editorials if stuck, but try solving first.
- Debugging is key: [Debugging Tips](https://example.com).

### Time Complexity
*Expected Time: 40–50 minutes*

**Why It Matters:** Understanding time complexity helps you write efficient solutions.  
**Resources:**
- [CPH Chapter 2](https://example.com)
- [Video: Time Complexity Examples](https://example.com)

**Problems (Solve in O(n)):**
- [CSES: Missing Number](https://cses.fi/problemset/task/1083)
- [CodeChef: Magician vs Chef](https://example.com)
- [CSES: Increasing Array](https://cses.fi/problemset/task/1094) *(Use `long long int`)*
- [CSES: Permutations](https://cses.fi/problemset/task/1070)

### Intro to STL
*Expected Time: 40–60 minutes*

**Resources:**
- [YouTube: Complete C++ STL (0:00–35:57)](https://example.com)
- [Medium: Practical Guide to STL](https://example.com)

**Problems:**
- **Arrays/Vectors:**
  - [CF: Team](https://example.com)
  - [CF: Series of Crimes](https://example.com)
  - [CF: Beautiful Matrix](https://example.com)
  - [CF: I Wanna Be the Guy](https://example.com)
  - [CF: Game Outcome](https://example.com)
- **Strings:**
  - [C++ Strings Tutorial](https://example.com)
  - [CF: Boy or Girl](https://example.com)
  - [CF: LLPS](https://example.com)
  - [SPOJ: Transform the Expression](https://www.spoj.com/problems/ONP/)
  - [CF: Phone Code](https://example.com) *(Use `vector<string>`)*
- **Stacks:**
  - [LeetCode: Valid Parentheses](https://leetcode.com/problems/valid-parentheses/)
  - [CSES: Nearest Smaller Values](https://cses.fi/problemset/task/1645)
  - [CF: YetnotherrokenKeoard](https://example.com)

**More STL (Sets/Maps):**
- *Expected Time: 40–60 minutes*
- Continue [YouTube: Complete C++ STL (35:58–end)](https://example.com).
- **Sets/Multisets:**
  - [CSES: Distinct Numbers](https://cses.fi/problemset/task/1621)
  - [CF: 1712C](https://codeforces.com/problemset/problem/1712/C)
  - [CF: 44A](https://codeforces.com/problemset/problem/44/A)
  - [CSES: Concert Tickets](https://cses.fi/problemset/task/1091)
  - [Virtual Judge: Querying Multiset](https://example.com)
- **Maps:**
  - [CF: Radio Station](https://example.com)
  - [CSES: Sum of Two Values](https://cses.fi/problemset/task/1640)
  - [CF: Boxes Packing](https://example.com)
  - [CSES: Playlist](https://cses.fi/problemset/task/1141)
- **Custom Comparator:**
  - [CF: Lamps](https://example.com)
  - [CF: Monsters](https://example.com)

### Sorting
*Expected Time: 2–2.5 hours*

**Resources:**
- [CPH Chapter 3](https://example.com)
- [LeetCode: Sorting Algorithms](https://example.com)
- [Tutorial with Visualization](https://example.com)

**Problems:**
- [CSES: Apartments](https://cses.fi/problemset/task/1084)
- [CF: Assembly via Minimums](https://example.com)
- [CF: Progressive Square](https://example.com)
- [CF: XOUR](https://example.com) *(Use `map<int, vector<int>>`)*
- [CSES: Collecting Numbers](https://cses.fi/problemset/task/2216)
- [CSES: Tasks and Deadlines](https://cses.fi/problemset/task/1630)

### Binary Search
*Expected Time: 40–60 minutes*

**Resources:**
- [Tutorial with Visualization](https://example.com)
- [Code Accepted: Binary Search](https://example.com)
- [ITMO: First Implementation](https://example.com)

**Problems:**
- [CF: Cat, Fox and the Lonely Array](https://example.com)
- [ITMO: Application on Real Numbers](https://example.com)
- [CSES: Array Division](https://cses.fi/problemset/task/1085) *(Minmax concept)*
- [CF: Maximum Median](https://example.com) ([Alternative Solution](https://example.com))
- **Additional Practice:**
  - [CodeChef: WAV2](https://example.com)
  - [Aizu: Range Search](https://example.com)
  - [CSES: Factory Machines](https://cses.fi/problemset/task/1620)
  - [ITMO: Packing Rectangles](https://example.com)
  - [SPOJ: Aggressive Cows](https://www.spoj.com/problems/AGGRCOW/)

### Bit Operations
*Expected Time: 1–1.5 hours*

**Resources:**
- [LeetCode: Bit Manipulation](https://example.com)
- [CPH: Bit Manipulation](https://example.com)
- [CP Algorithms: Bit Manipulation](https://example.com)

**Problems:**
- [CF: Raising Bacteria](https://example.com)
- [Virtual Judge: Little Elephant and Bits](https://example.com)
- [Virtual Judge: Maximizing XOR](https://example.com)
- [CF: Preparing Olympiad](https://example.com)
- [Virtual Judge: Red Scarf](https://example.com)

### Primary Number Theory
*Expected Time: 1–1.5 hours*

**Resources:**
- [Elementary Number Theory](https://example.com)
- [Code Accepted: Modulo 10^9 + 7](https://example.com)
- [Codeforces: Modular Arithmetic](https://example.com)

**Subtopics:**
- **Binary Exponentiation** *(20–30 min)*
  - [Code Accepted: Binary Exponentiation](https://example.com)
  - [AlgorithmClear: Binary Exponentiation](https://example.com)
  - Problems:
    - [CSES: Bit Strings](https://cses.fi/problemset/task/1617)
    - [CSES: Exponentiation](https://cses.fi/problemset/task/1095)
    - [SPOJ: Magic of the Locker](https://www.spoj.com/problems/LOCKER/)
- **Factorization (O(√N))** *(20–30 min)*
  - [Code Accepted: Primality Testing](https://example.com)
  - Problems:
    - [Aizu: Prime Factorization](https://example.com)
    - [AtCoder: D Div Game](https://example.com)
    - [LeetCode: Four Divisors](https://leetcode.com/problems/four-divisors/)
- **GCD** *(20–30 min)*
  - [Code Accepted: GCD](https://example.com)
  - Problems:
    - [CF: Common Divisors](https://example.com)
    - [CF: Minimum LCM](https://example.com)
    - [CodeChef: Subset GCD](https://example.com)
    - [CodeChef: GCD and LCM](https://example.com)

**More Practice:**
- [CodeChef: Hello Equation](https://example.com)
- [CodeChef: Bitwise Equation](https://example.com)

### Recursion
*Expected Time: 1.5–2 hours*

**Resources:**
- [C++ Recursion Tutorial](https://example.com)
- [Tower of Hanoi](https://example.com) ([Video](https://example.com))
- [Article on Recursion](https://example.com)

**Problems:**
- [CSES: Chessboard and Queens](https://cses.fi/problemset/task/1624)
- [CSES: Weird Algorithm](https://cses.fi/problemset/task/1068)
- [CSES: Elimination Game](https://example.com)
- [CSES: Apple Division](https://cses.fi/problemset/task/1623)
- [CSES: Creating Strings](https://cses.fi/problemset/task/1622) *(Generate permutations)*

### Complete Search
*Expected Time: 1.5–2 hours*

**Resources:**
- [CPH Chapter 5](https://example.com)
- [Code Accepted: Bit Masking](https://example.com)
- [Code Accepted: Backtracking](https://example.com)

**Problems:**
- [CSES: Creating Strings](https://cses.fi/problemset/task/1622) *(Without `next_permutation()`)*
- [Virtual Judge: Bars](https://example.com)
- [CF: Creating Expression1](https://example.com)
- [CF: 2D Traveling](https://example.com)
- [USACO: Air Cownditioning II](http://www.usaco.org/index.php?page=viewproblem2&cpid=1042)
- [CF: Reverse String](https://example.com)

**Debugging Tips:** [Article](https://example.com) | [Video](https://example.com)

### Section 0 Additional Practice
- [SPOJ: Factorial](https://www.spoj.com/problems/FCTRL/)
- [SPOJ: Small Factorials](https://www.spoj.com/problems/FCTRL2/)
- [SPOJ: Transform the Expression](https://www.spoj.com/problems/ONP/)
- [CF: Turtle and an Infinite Sequence](https://example.com)
- [CSES: Sum of Three Values](https://cses.fi/problemset/task/1641)
- [CF: Chat Order](https://example.com)
- [CF: Cellular Network](https://example.com)

---

## Section 1: Basic Theory

This section builds on foundational concepts, introducing more sophisticated techniques like dynamic programming and greedy algorithms.

### Number Theory

**Number Sieve** *(1–1.5 hours)*
- [Sieve of Eratosthenes: Wikipedia](https://en.wikipedia.org/wiki/Sieve_of_Eratosthenes)
- [CP Algorithms: Sieve](https://cp-algorithms.com/algebra/sieve-of-eratosthenes.html)
- Problems:
  - [LeetCode: Count Primes](https://leetcode.com/problems/count-primes/)
  - [SPOJ: NFACTOR](https://www.spoj.com/problems/NFACTOR/)
  - [SPOJ: Amazing Prime Sequence](https://www.spoj.com/problems/AMR11E/)
  - [Virtual Judge: A Different Kind of Sorting](https://example.com)
  - [SPOJ: Printing Some Primes](https://www.spoj.com/problems/PRIME1/)
  - [SPOJ: Bazinga!](https://www.spoj.com/problems/BAZINGA/)

**Faster Prime Factorization**
- [CSES: Counting Divisors](https://cses.fi/problemset/task/1713) ([Solution](https://example.com))
- [LeetCode: Prime Factors Tutorial](https://example.com)

**Modular Multiplicative Inverse** *(20–30 min)*
- [forthright48: Modular Inverse](https://example.com)
- Problems:
  - [Virtual Judge: Modular Division](https://example.com)
  - [CSES: Exponentiation II](https://cses.fi/problemset/task/1712)

**Additional Practice:**
- [CodeChef: GCD of Prefixes](https://example.com)
- [SPOJ: Distinct Primes](https://www.spoj.com/problems/DPRIME/)
- [CodeChef: Modular GCD](https://example.com) *(Use `__int128_t`)*
- [CSES: Divisor Analysis](https://cses.fi/problemset/task/2182)
- [CF: Orac and LCM](https://example.com)
- [CF: k-LCM (Hard)](https://example.com)
- [CF: Santa’s Bot](https://example.com)
- [CodeChef: Chef and Riffles](https://example.com) *(Binary exponentiation)*

### Two Pointers / Sliding Windows
*Expected Time: 30–40 minutes*

**Resources:**
- [CPH](https://example.com)
- [Video Tutorial](https://example.com)

**Problems:**
- [CSES: Subarray Sum](https://cses.fi/problemset/task/1660)
- [ITMO: Big Sum](https://example.com)
- [ITMO: Number of Small Sum Segments](https://example.com)
- [ITMO: Knapsack on a Segment](https://example.com)
- [CF: Cellular Network](https://example.com)
- **Additional:**
  - [CSES: Subarray Distinct Values](https://cses.fi/problemset/task/2428)
  - [CSES: Sum of Four Values](https://cses.fi/problemset/task/1642)
  - [CF: Quiz Master](https://example.com) *(Revisit after sieve)*

### Range Queries
*Expected Time: 40–50 minutes*

**Resources:**
- [CPH: Range Queries](https://example.com)
- [USACO Book: Prefix Sums](https://example.com)
- [LeetCode: Prefix Sum Examples](https://example.com)

**Problems:**
- [CSES: Sum Queries](https://cses.fi/problemset/task/1646)
- [CSES: Xor Queries](https://cses.fi/problemset/task/1650)
- [CF: Playing in a Casino](https://example.com)
- [CSES: Subarray Sums II](https://cses.fi/problemset/task/1661)
- [CodeChef: GCD Discount]( Gabungan dari kedua hal ini akan membantu Anda mendapatkan hasil maksimal dari pengalaman bermain Anda. example.com)
- [CSES: Maximum Subarray Sum](https://cses.fi/problemset/task/1643) *(Hint: [Link](https://example.com))*

**2D Prefix Sum:**
- [Ramu’s Mango Trees](https://example.com)
- [CSES: Forest Queries](https://cses.fi/problemset/task/1652)
- [Aizu: Maximum Number of Overlaps](https://example.com)

**Additional Practice:**
- [USACO: Subsequences Summing to Sevens](http://www.usaco.org/index.php?page=viewproblem2&cpid=739)
- [CF: Data Structures Fan](https://example.com)
- [CSES: Subarray Divisibility](https://cses.fi/problemset/task/1662)

### Divide and Conquer
*Expected Time: 20–30 minutes*

**Resources:**
- [Intro to Divide and Conquer](https://example.com)
- [Video Tutorial](https://example.com)

**Problems:**
- [CF: Lost Numbers](https://example.com)
- [CF: Print the Pattern](https://example.com)
- [CF: Permutation Transformation](https://example.com)
- [CF: Maximum Crossings](https://example.com)
- [CF: Greetings](https://example.com)

### Intro to Greedy Algorithms
*Expected Time: 1.5–2 hours*

**Resources:**
- [CPH: Greedy Algorithms](https://example.com)
- [LeetCode: Greedy Tutorial](https://example.com)
- [Video Tutorial](https://example.com)

**Problems:**
- [CF: Studying Algorithms](https://example.com)
- [Optimal Merge Pattern](https://example.com) *(Use multiset/priority queue)*
- **Self-Assessment:**
  - [CF: Heavy Intervals](https://example.com)
  - [CF: Contrast Values](https://example.com)
  - [CF: Grid Reconstruction](https://example.com)
  - [CSES: Ferris Wheel](https://cses.fi/problemset/task/1090)
  - [CSES: Movie Festival](https://cses.fi/problemset/task/1629)
  - [CSES: Towers](https://cses.fi/problemset/task/1076)
  - [CSES: Movie Festival II](https://cses.fi/problemset/task/1632)

### Dynamic Programming
*Expected Time: 1.5–2 hours*

**Resources:**
- [Video: DP Intro (Fibonacci)](https://example.com)
- [CPH Chapter 7](https://example.com)
- [Classic DP Illustrations](https://example.com)

**Problems:**
- [CSES: Dice Combinations](https://cses.fi/problemset/task/1633)
- [LeetCode: Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/) ([Video](https://example.com))
- [LeetCode: Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/) ([Video](https://example.com))
- [LeetCode: Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/)
- [CSES: Edit Distance](https://cses.fi/problemset/task/1639)
- [AtCoder: Knapsack 1](https://atcoder.jp/contests/dp/tasks/dp_d)

**DP on Grids:**
- [Tutorial: Grid DP](https://example.com)
- Problems:
  - [CSES: Grid Paths](https://cses.fi/problemset/task/1638)
  - [Superjump in a Grid](https://example.com)
  - [LeetCode: Cherry Pickup II](https://leetcode.com/problems/cherry-pickup-ii/) *(Tough)*

**DP Bitmask:** *(1.5–2 hours)*
- [Blog: Bitmask DP](https://example.com)
- [Tutorial: Advanced DP](https://example.com) *(Up to 45:00)*
- Problems:
  - [CF: Vampiric Powers](https://example.com)
  - [CSES: Counting Tilings](https://cses.fi/problemset/task/2181)
  - [CSES: Elevator Rides](https://cses.fi/problemset/task/1653)

**Self-Assessment:**
- [CF: Nikita and String](https://example.com)
- [CSES: Coin Combinations I](https://cses.fi/problemset/task/1635) ([Coin Combinations II](https://cses.fi/problemset/task/1636))
- [CF: Counting Rectangles](https://example.com)
- [CF: Marvalo Gaunt’s Ring](https://example.com)
- [CSES: Rectangle Cutting](https://cses.fi/problemset/task/1744)
- [CF: Woodcutters](https://example.com)
- [CF: Tetrahedron](https://example.com)
- **Extra:**
  - [CF: Long Path](https://example.com)
  - [CF: Bad Luck Island](https://example.com)
  - [CF: Jeff and Furik](https://example.com)
  - [AtCoder: Sushi](https://example.com)

**Practice Resources:**
- [AtCoder DP Contest](https://atcoder.jp/contests/dp)
- [CF Problemset (DP Tag)](https://codeforces.com/problemset?tags=dp)
- [CSES DP Section](https://cses.fi/problemset/)

### Interactive Problems
*Expected Time: 15–20 minutes*

**Resources:**
- [Tutorial: Interactive Problems](https://example.com)

**Problems:**
- [CF: Interview](https://example.com)
- [CF: Guess The Array](https://example.com)
- [CF: Bit Guessing Game](https://example.com) *(Bit manipulation)*

**Tools:**
- [Diffchecker](https://www.diffchecker.com/) *(Compare outputs)*
- **Codeforces Extensions:**
  - [CF Analytics](https://example.com)
  - [Codeforces Enhancer](https://example.com)
  - [Carrot](https://example.com)
  - [Coding Dude](https://example.com)

### Section 1 Additional Practice
- [CodeChef: Mathison and the Dynamo Shuffle](https://example.com)
- [CF: Long Multiplication](https://example.com)
- [SPOJ: Eko](https://www.spoj.com/problems/EKO/)
- [LeetCode: Container with Most Water](https://leetcode.com/problems/container-with-most-water/)
- [CF: Final Boss](https://example.com)
- [SPOJ: ABCDEF](https://www.spoj.com/problems/ABCDEF/)
- [CF: Update Queries](https://example.com)
- [CF: Forming Triangles](https://example.com)
- [CF: Binary Search](https://example.com)
- [CF: Inaccurate Subsequence Search](https://example.com)

---

## Section 2: Intermediate

This section introduces more complex topics like graph theory and advanced mathematical concepts.

### Advanced Maths

**Combinatorics** *(15–20 min)*
- [CPH Chapter 22](https://example.com)
- Topics: Binomial Coefficients, Catalan Numbers
- Problems:
  - [Aizu: DPL_5](https://example.com)
  - [Virtual Judge: One Unit Machine](https://example.com)
  - [CSES: Christmas Party](https://cses.fi/problemset/task/1717)
  - [CF: Secret Box](https://example.com)
- **Additional:**
  - [CF: Earning on Bets](https://example.com)
  - [CF: How Does the Rook Move?](https://example.com) *(Use DP)*
  - [CF: Blueprint for Seating](https://example.com)

**Matrices** *(1–1.5 hours)*
- [CPH Chapter 23](https://example.com)
- [Codeforces: Matrix Exponentiation](https://example.com)
- Problems:
  - [CF: Weird Sum](https://example.com)
  - [CF: Permutation on Rows and Columns](https://example.com)
  - [CSES: Fibonacci Numbers](https://cses.fi/problemset/task/1722)
  - [CF: Random Mood](https://example.com)
  - [CSES: Graph Paths I](https://cses.fi/problemset/task/1723) ([Hint](https://example.com))
  - [AtCoder: Walk](https://example.com)
  - [CSES: Graph Paths II](https://cses.fi/problemset/task/1724)

**Probability** *(1–1.5 hours)*
- [CPH Chapter 24](https://example.com)
- [Blog/Video](https://example.com)
- Problems:
  - [CF: Red-Blue Shuffle](https://example.com)
  - [CF: Dreamoon and Wifi](https://example.com)
  - [CF: Archer](https://example.com)
  - [CF: Little Pony and Expected Maximum](https://example.com)

**Extra Number Theory** *(1–1.5 hours)*
- [CPH Chapter 21](https://example.com)
- [AlgorithmClear: System of Congruences](https://example.com)
- Problems:
  - [SPOJ: Euler Totient Function Depth](https://www.spoj.com/problems/ETFDEPTH/)

### Range Update Queries
*Expected Time: 1.5–2 hours*

**Resources:**
- [CPH: Range Queries](https://example.com)
- **Segment Trees:**
  - [CS Academy Tutorial](https://example.com)
  - [CP Algorithms: Segment Tree](https://cp-algorithms.com/data_structures/segment_tree.html)
- **Fenwick Trees (Optional):**
  - [CS Academy Tutorial](https://example.com)
  - [CP Algorithms: Fenwick Tree](https://example.com)

**Problems:**
- [ITMO: Segment Tree for the Sum](https://example.com) ([Video: CODE 1](https://example.com))
- [CSES: Segment Tree for the Minimum](https://cses.fi/problemset/task/1649)
- [ITMO: Number of Minimums on a Segment](https://example.com) ([Video: CODE 2](https://example.com))
- [SPOJ: Range Sum](https://www.spoj.com/problems/RANGSUM/)
- [CF: Thor](https://example.com)
- [ITMO Step 3 Problems](https://example.com)

### Graph Theory Basics
*Expected Time: 40–60 minutes*

**Resources:**
- [Intro to Graphs](https://example.com)
- [Code Accepted: Graph Representation](https://example.com)
- [Video: Graph Theory](https://example.com)

**Problems:**
- [SPOJ: ROADNET](https://www.spoj.com/problems/ROADNET/)

**BFS and DFS** *(30–40 min)*
- [CPH Pages 117–122](https://example.com)
- [Videos: DFS](https://example.com), [BFS](https://example.com)
- Problems:
  - [CSES: Message Route](https://cses.fi/problemset/task/1667)
  - [CF: Two Buttons](https://example.com)
  - [USACO: Moocast](http://www.usaco.org/index.php?page=viewproblem2&cpid=668)
  - [CF: Kefa and Park](https://example.com)
  - [CF: Round Dance](https://example.com)
  - [CSES: Building Teams](https://cses.fi/problemset/task/1668)

**Cycles Detection** *(20–30 min)*
- [Article 1](https://example.com), [Article 2](https://example.com)
- Problems:
  - [CSES: Round Trip](https://cses.fi/problemset/task/1669)
  - [CSES: Round Trip II](https://cses.fi/problemset/task/1670)
  - [SPOJ: Cactus](https://www.spoj.com/problems/CACTUS/) *(Use `unsigned long long`)*
  - [CF: Forest Program](https://example.com)

**Bridges in Graphs** *(30–40 min)*
- [Codeforces: DFS Tree](https://example.com)
- Problems:
  - [Critical Edges](https://example.com)
  - [Bertown Roads](https://example.com)

**Flood Fill** *(15–20 min)*
- [Article](https://example.com)
- Problems:
  - [LeetCode: Flood Fill](https://leetcode.com/problems/flood-fill/)
  - [CSES: Counting Rooms](https://cses.fi/problemset/task/1192)

**Topological Sort** *(40–60 min)*
- [CPH 16.1](https://example.com)
- [Article](https://example.com)
- [Video](https://example.com)
- [Kahn’s Algorithm](https://example.com)
- Problems:
  - [CSES: Course Schedule](https://cses.fi/problemset/task/1679)
  - [SPOJ: Answer the Boss!](https://www.spoj.com/problems/TOPOSORT/)
  - [CF: Fox and Names](https://example.com)
  - [AtCoder: Find Permutation](https://example.com)

**Subtree/DFS Problems:**
- [CSES: Subordinates](https://cses.fi/problemset/task/1674)
- [CF: Journey](https://example.com)
- [LeetCode: Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/)
- [CodeChef: Chef and Subtree MEXs](https://example.com)

### DSU + MST
**Disjoint Set Union (DSU)** *(1.5–2 hours)*
- [Video Lecture](https://example.com)
- Problems:
  - [CSES: Road Construction](https://cses.fi/problemset/task/1675)
  - [ITMO: Cutting a Graph](https://example.com)
  - [CF: Unforgivable Curse (Hard)](https://example.com)
  - [CF: Roads Not Only in Berland](https://example.com)
  - [USACO: Wormhole Sort](http://www.usaco.org/index.php?page=viewproblem2&cpid=990)

**Minimum Spanning Trees (MST)** *(1–1.5 hours)*
- [PAPS Section 12.4](https://example.com)
- [Articles: Kruskal](https://example.com), [Kruskal DSU](https://example.com), [Prim’s](https://example.com)
- [Videos: Kruskal](https://example.com), [Prim’s](https://example.com)
- Problems:
  - [CSES: Road Reparation](https://cses.fi/problemset/task/1675)
  - [SPOJ: BMW](https://www.spoj.com/problems/BMW/)
  - [ITMO: Dense Spanning Tree](https://example.com)
  - [CodeChef: Chefland and Electricity](https://example.com)
  - [AtCoder: Choose Two and Eat One](https://example.com)

### Shortest Path Algorithms
*Expected Time: 1–1.5 hours*

**Resources:**
- [CPH Chapter 13](https://example.com)
- [Videos: Dijkstra](https://example.com), [Bellman Ford](https://example.com), [Floyd Warshall](https://example.com)

**Problems:**
- [CSES: Shortest Routes I](https://cses.fi/problemset/task/1671) *(Dijkstra)*
- [CSES: Shortest Routes II](https://cses.fi/problemset/task/1672) *(Floyd Warshall)*
- [CSES: Flight Discount](https://cses.fi/problemset/task/1195)
- [CSES: Cycle Finding](https://cses.fi/problemset/task/1197) *(Bellman Ford)*
- [LeetCode: Path with Maximum Probability](https://leetcode.com/problems/path-with-maximum-probability/)
- [USACO: Milk Pumping](http://www.usaco.org/index.php?page=viewproblem2&cpid=917)

### Section 2 Additional Practice
- [CSES: Distributing Apples](https://cses.fi/problemset/task/1716)
- [CSES: Prime Multiples](https://cses.fi/problemset/task/2185)
- [CSES: Graph Girth](https://cses.fi/problemset/task/1707)
- [CF: Labyrinth](https://example.com) *(0-1 BFS)*
- [CF: Cyclic Components](https://example.com)
- [CF: Number of Simple Paths](https://example.com)
- [CF: Arrayland’s Challenge](https://example.com)
- [CF: Lonely Mountain Dungeons](https://example.com)
- [SPOJ: Fibonacci Sum](https://www.spoj.com/problems/FIBSUM/)
- [CF: Turtle Mission](https://example.com)
- [CF: Friendly Spiders](https://example.com)
- [CF: GCD and MST](https://example.com)
- [CF: Split Into Two Sets](https://example.com)
- **Optional:** [Bacterial Sampling](https://example.com) *(O(log n))*

---

## Section 3: Advanced

This section tackles advanced algorithms and data structures for high-level competitive programming.

### String Hashing
*Expected Time: 2–2.5 hours*

**Resources:**
- [CPH Chapter 26](https://example.com)
- [Video: String Algorithms](https://example.com)
- [Aho-Corasick Algorithm](https://example.com)

**Problems:**
- [CSES: Finding Borders](https://cses.fi/problemset/task/1732)
- [CF: Password](https://example.com)
- [CF: Compress Words](https://example.com)
- [CSES: Word Combinations](https://cses.fi/problemset/task/1731)
- [CSES: Finding Patterns](https://cses.fi/problemset/task/2102)
- [CF: Tavas and Malekas](https://example.com)

### Directed Graphs
*Expected Time: 1.5–2 hours*

**Resources:**
- [CPH Chapter 16](https://example.com)

**Problems:**
- [CodeChef: MaxEdges](https://example.com)
- [LeetCode: Minimum Number of Vertices](https://leetcode.com/problems/minimum-number-of-vertices-to-reach-all-nodes/)

**Cycles in Directed Graphs:**
- **Functional Graphs:** [CSES: Planet Queries I](https://cses.fi/problemset/task/1750) ([CPH 16.3](https://example.com))
- **Cycle Finding:**
  - [Floyd’s Algorithm](https://example.com)
  - [Kahn’s Algorithm](https://example.com)
  - Problems:
    - [USACO: The Bovine Shuffle](http://www.usaco.org/index.php?page=viewproblem2&cpid=760)
    - [USACO: Visits](http://www.usaco.org/index.php?page=viewproblem2&cpid=968)
    - [CSES: Planets Cycles](https://cses.fi/problemset/task/1751)
    - [AtCoder: Reachability in Functional Graph](https://example.com)
    - [CF: Secret Santa](https://example.com)

**Strongly Connected Components (SCC):**
- [CPH Chapter 17](https://example.com)
- [Kosaraju’s Algorithm](https://example.com) ([Techdose](https://example.com))
- [Tarjan’s Algorithm](https://example.com) ([William Fiset](https://example.com))
- Problems:
  - [CSES: Flight Routes Check](https://cses.fi/problemset/task/1682)
  - [CSES: Planets and Kingdoms](https://cses.fi/problemset/task/1683)
  - [CF: Checkposts](https://example.com)

**Condensation Graphs:**
- Problems:
  - [CSES: Coin Collector](https://cses.fi/problemset/task/1686)
  - [SPOJ: Good Travels](https://www.spoj.com/problems/GOODTRAVELS/)
  - [CF: Scheme](https://example.com)

**2-SAT:**
- [CPH 17.2](https://example.com)
- [Codeforces Blog](https://example.com)
- [CP Algorithms](https://example.com)
- [Algorithms Live!](https://example.com)
- Problems:
  - [CSES: Giant Pizza](https://cses.fi/problemset/task/1684)
  - [CF: Problem H ±1](https://example.com)

**DP on DAGs:**
- Problems:
  - [AtCoder: Longest Path](https://example.com)
  - [CF: Pashmak and Graph](https://example.com)
  - [CSES: Game Routes](https://cses.fi/problemset/task/1677) ([Video](https://example.com))
  - [LeetCode: All Ancestors in DAG](https://leetcode.com/problems/all-ancestors-of-a-node-in-a-directed-acyclic-graph/)
  - [SPOJ: Counting in a DAG](https://www.spoj.com/problems/DAGCNT/)
  - [CSES: Investigation](https://cses.fi/problemset/task/1202)

### Range Update Queries (Continued)
*Expected Time: 1.5–2 hours*

**Problems:**
- [CF: Xenia and Bit Operations](https://example.com)
- [ITMO Step 2](https://example.com):
  - [CSES: Hotel Queries](https://cses.fi/problemset/task/1143)
  - [CF: Merge Equals](https://example.com)
  - [CSES: List Removals](https://cses.fi/problemset/task/1749)
  - [CSES: Bit Inversions](https://cses.fi/problemset/task/1188)
  - [CSES: Range Update Queries](https://cses.fi/problemset/task/1651)
  - [CF: Distinct Characters Queries](https://example.com)

**2D Range Queries:**
- [CP Algorithms](https://example.com)
- [TopCoder](https://example.com)
- Problems:
  - [SPOJ: Matrix Summation](https://www.spoj.com/problems/MATSUM/)
  - [CSES: Forest Queries II](https://cses.fi/problemset/task/1739)
  - [CSES: Distinct Values Queries](https://cses.fi/problemset/task/1734)
  - [Stack Overflow: Distinct Integers](https://example.com)

**Optional:**
- [ITMO Step 4](https://example.com)
- [CSES: Increasing Subsequence II](https://cses.fi/problemset/task/1748)
- [ITMO Step 5: Range Update Seg Tree](https://example.com)

### Sparse Table
*Expected Time: 1–1.5 hours*

**Resources:**
- [Video/Theory](https://example.com)

**Problems:**
- [CSES: Static Range Minimum Query](https://cses.fi/problemset/task/1647)
- [CF: Ant Colony](https://example.com)
- [CF: Longest Regular Bracket Sequence](https://example.com)
- [CF: CGCDSSQ](https://example.com)
- [CF: Turn Off the TV](https://example.com)
- [Blog: 2D Range Minimum Queries](https://example.com)

### Tree Algorithms
*Expected Time: 2–2.5 hours*

**Resources:**
- [CPH Chapter 14](https://example.com)
- [YouTube: Tree Algorithms](https://example.com)
- [AlgorithmsThread: Tree Basics](https://example.com)

**Tree Diameter:**
- [Article](https://example.com)
- [Codeforces Blog](https://example.com)
- Problems:
  - [CSES: Tree Diameter](https://cses.fi/problemset/task/1131)
  - [CF: Gym Problem 1](https://example.com) ([Video](https://example.com))
  - [CSES: Tree Distances I](https://cses.fi/problemset/task/1132)
  - [CF: Gym Problem 2](https://example.com)
  - [CF: Minimize the Diameter](https://example.com)

**DP on Trees:**
- [Blog: DP on Trees](https://example.com)
- Problems:
  - [AtCoder: Independent Set](https://example.com)
  - [AtCoder: Subtree](https://example.com)
  - [CF: Distance in Tree](https://example.com)
  - [CF: Anton and Tree](https://example.com)
  - [CodeChef: Build Towers](https://example.com)

**Number of Topological Sortings:**
- [Codeforces Blog](https://example.com)

**Tree Queries:**
- **Finding Ancestors (Binary Lifting):**
  - [CPH 18.1](https://example.com)
  - [CP Algorithms: Binary Lifting](https://example.com)
  - Problems:
    - [CSES: Company Queries I](https://cses.fi/problemset/task/1687)
    - [CF: Gym Problem 3](https://example.com)
    - [USACO: Luxury River Cruise](http://www.usaco.org/index.php?page=viewproblem2&cpid=1002)
- **Subtree and Path Queries (Euler Tour):**
  - [CPH 18.2](https://example.com)
  - Problems:
    - [CSES: Subtree Queries](https://cses.fi/problemset/task/1137)
    - [CodeChef: Subtree Summation](https://example.com)
    - [AtCoder: Count Descendants](https://example.com)
    - [CSES: Path Queries](https://cses.fi/problemset/task/1138)
- **Lowest Common Ancestor (LCA):**
  - [CPH 18.3](https://example.com)
  - [CP Algorithms: LCA](https://example.com)
  - [William Fiset](https://example.com)
  - Problems:
    - [SPOJ: Lowest Common Ancestor](https://www.spoj.com/problems/LCA/)
    - [CSES: Distance Queries](https://cses.fi/problemset/task/1135)
    - [AtCoder: Distance Queries on a Tree](https://example.com)

**More Problems:**
- [SPOJ: Query on a Tree II](https://www.spoj.com/problems/QTREE2/)
- [Optimal Connectivity](https://example.com) *(Binary lifting)*

### Section 3 Additional Practice
- [CSES: Pizzeria Queries](https://cses.fi/problemset/task/1652)
- [CSES: Salary Queries](https://cses.fi/problemset/task/1144)
- [CSES: Planet Queries II](https://cses.fi/problemset/task/1160)
- [CSES: Tree Distances II](https://cses.fi/problemset/task/1133)
- [CSES: Counting Paths](https://cses.fi/problemset/task/1136)
- [CF: Shuffling Songs](https://example.com)
- [CF: Sasha and Array](https://example.com)
- [CF: Analysis of Paths in Functional Graph](https://example.com)
- [CF: Count Paths Queries](https://example.com)
- [CF: Civilization](https://example.com)
- [LeetCode: Binary Tree Cameras](https://leetcode.com/problems/binary-tree-cameras/)
- [SPOJ: Cost](https://www.spoj.com/problems/COST/)

---

## Additional Topics

For those looking to go beyond, explore these advanced topics:
- Convex Hull Trick
- Square Root Decomposition
- DP Optimizations (Knuth, Aliens, Divide and Conquer, CHT)
- LiChao Tree
- Mo’s Algorithm
- Digit DP
- Broken Profile DP
- Connected Components DP
- Sparse Segment Trees
- Persistent Data Structures
- Slope Trick
- FFT
- Suffix Array
- Tries
- Heavy Light Decomposition
- Centroid Decomposition

**Note:** Each topic has numerous variations. Continue exploring to deepen your expertise!

---

## Resources

**Books:**
- *Competitive Programmer’s Handbook* (CPH)
- *An Introduction to the USA Computing Olympiad*
- *Principles of Algorithmic Problem Solving*
- *Competitive Programming 2*
- *Guide to Competitive Programming* (Springer)

**Problem Sets and Resources:**
- [ITMO Academy: Pilot Course](https://codeforces.com/edu/courses)
- [USACO Guide](https://usaco.guide/)
- [The Ultimate Topic List](https://example.com)
- [CSES Problem Set](https://cses.fi/problemset/)
- [A2OJ Ladders](https://a2oj.com/)
- [AtCoder Problems](https://atcoder.jp/)
- [CP-Algorithms](https://cp-algorithms.com/)
- [KACTL CP Templates](https://example.com)
- [T-414-ÁFLV: Competitive Programming Course](https://example.com)
- [Project Euler](https://projecteuler.net/)
- [Brilliant: Number Theory](https://brilliant.org/)

**Blogs:**
- [Codeforces: Awesome CP List](https://codeforces.com/blog/entry/23054)
- [NOI.PH: Prepare](https://noi.ph/prepare/)
- [Codeforces: CP Tutorials](https://codeforces.com/blog/entry/57282)
- [LeetCode: 75 Questions](https://example.com)

**YouTube Channels:**
- [Pavel Mavrin: A&DS](https://www.youtube.com/channel/UCP5iW0V7rX7uPq3y71zVRRw)
- [Gaurav Sen: CP A-Z](https://www.youtube.com/c/GauravSen)
- [Errichto Algorithms](https://www.youtube.com/c/Errichto)
- [Colin Galen](https://www.youtube.com/c/ColinGalen)
- [AlgorithmsThread](https://www.youtube.com/c/AlgorithmsThread)
- [William Fiset](https://www.youtube.com/c/WilliamFiset)
- [William Lin](https://www.youtube.com/c/WilliamLin168)

---

**Keep Practicing!** Competitive programming is a journey of continuous learning. Stay consistent, tackle new challenges, and enjoy the process. Good luck! 🚀

---
