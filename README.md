# 100-Day Coding Workout
**From "Hello World" to building real systems**

**Rules of the workout:**
- Minimum 30–60 min/day. Consistency > intensity.
- Pick one main language (Python or JavaScript recommended) and stick with it.
- Every day: write code → test it → commit to GitHub.
- "Rest/Review" days are for refactoring, re-doing hard problems, and writing notes.

---

## Phase 1 — Foundations (Days 1–20)
*Goal: syntax fluency, basic logic, no fear of the keyboard.*

| Day | Workout |
|---|---|
| 1 | Set up environment (editor, Git, GitHub). Print "Hello World". Commit it. |
| 2 | Variables & types: write a program that converts Celsius ↔ Fahrenheit. |
| 3 | Conditionals: FizzBuzz (1–100). |
| 4 | Loops: print all primes under 100. |
| 5 | Functions: write `is_palindrome(s)` and `reverse_string(s)`. |
| 6 | Strings: count vowels, consonants, and words in a sentence. |
| 7 | **Review** — refactor Days 1–6 into clean functions with docstrings. |
| 8 | Lists/arrays: find max, min, sum, average without built-ins. |
| 9 | Nested loops: print a multiplication table and a right-triangle star pattern. |
| 10 | Dictionaries/maps: word-frequency counter for a paragraph. |
| 11 | Input handling: number-guessing game with hints (higher/lower). |
| 12 | Sorting by hand: implement Bubble Sort. |
| 13 | Recursion: factorial, Fibonacci, sum of digits. |
| 14 | **Review** — write 5 unit tests for previous days' functions. |
| 15 | File I/O: read a text file, write a report (line count, longest line). |
| 16 | Error handling: a calculator that survives bad input and divide-by-zero. |
| 17 | Modules: split a project into 2+ files/modules and import between them. |
| 18 | Classes 101: a `BankAccount` with deposit, withdraw, balance history. |
| 19 | Mini-project: command-line To-Do app (add, list, complete, delete; save to file). |
| 20 | **Checkpoint** — rewrite FizzBuzz in 3 different styles (loop, list comprehension, recursion). |

---

## Phase 2 — Data Structures & Algorithms I (Days 21–40)
*Goal: think in structures, analyze complexity.*

| Day | Workout |
|---|---|
| 21 | Big-O: write 5 functions and label each with its time complexity. |
| 22 | Two-pointer: Two Sum (sorted array), remove duplicates in place. |
| 23 | Sliding window: max sum subarray of size k; longest substring without repeats. |
| 24 | Implement a Stack class. Solve "Valid Parentheses". |
| 25 | Implement a Queue (and a circular queue). |
| 26 | Singly Linked List: insert, delete, reverse, find middle. |
| 27 | Linked List: detect cycle (Floyd's), merge two sorted lists. |
| 28 | **Review** — redo Days 22–27 problems from memory. |
| 29 | Hash maps: group anagrams, first non-repeating character. |
| 30 | Selection Sort + Insertion Sort. Compare timings on 10k elements. |
| 31 | Merge Sort (recursive). |
| 32 | Quick Sort with random pivot. |
| 33 | Binary Search (iterative + recursive); find first/last occurrence. |
| 34 | Binary search variants: search in rotated array, square root to precision. |
| 35 | **Review** — implement all 5 sorts in one file; benchmark them. |
| 36 | Binary Tree: build it, traverse in/pre/post-order (recursive). |
| 37 | Binary Tree: iterative traversals using a stack; level-order with a queue. |
| 38 | Binary Search Tree: insert, search, delete, validate. |
| 39 | Tree problems: max depth, lowest common ancestor, invert tree. |
| 40 | **Checkpoint** — solve 5 random "Easy" problems on LeetCode/HackerRank under 20 min each. |

---

## Phase 3 — Algorithms II & Problem Solving (Days 41–60)
*Goal: classic techniques that unlock "Medium" problems.*

| Day | Workout |
|---|---|
| 41 | Heaps: implement a min-heap. Solve "Kth largest element". |
| 42 | Priority queue problems: merge k sorted lists, top-k frequent elements. |
| 43 | Graphs: adjacency list representation; BFS. |
| 44 | Graphs: DFS (recursive + iterative); count connected components. |
| 45 | Grid problems: number of islands, flood fill. |
| 46 | Topological sort; detect cycle in a directed graph. |
| 47 | Dijkstra's shortest path. |
| 48 | **Review** — build a graph visualizer that prints BFS/DFS order. |
| 49 | Backtracking: generate all subsets and permutations. |
| 50 | Backtracking: N-Queens, Sudoku solver. |
| 51 | Greedy: interval scheduling, coin change (greedy version + where it fails). |
| 52 | Dynamic programming intro: Fibonacci with memoization vs tabulation. |
| 53 | DP 1D: climbing stairs, house robber, coin change (minimum coins). |
| 54 | DP 2D: longest common subsequence, edit distance. |
| 55 | DP: 0/1 knapsack, longest increasing subsequence. |
| 56 | **Review** — write a one-page "DP recipe" and re-solve 3 DP problems. |
| 57 | Bit manipulation: count set bits, single number (XOR), power of two. |
| 58 | Tries: implement insert/search/startsWith; autocomplete. |
| 59 | Union-Find with path compression; detect cycle in undirected graph. |
| 60 | **Checkpoint** — timed mock: 2 Medium problems in 60 min. |

---

## Phase 4 — Building Real Software (Days 61–80)
*Goal: move beyond puzzles into tools, APIs, and data.*

| Day | Workout |
|---|---|
| 61 | OOP deep dive: inheritance, composition, interfaces/abstract classes. Model a library system. |
| 62 | Design patterns: implement Singleton, Factory, Observer. |
| 63 | Regular expressions: validate emails, extract phone numbers, parse log lines. |
| 64 | JSON: read a config file, modify it, write it back; handle malformed JSON. |
| 65 | HTTP: call a public API (weather, GitHub) and display results. |
| 66 | Build a CLI tool with argument parsing (e.g., a file-renamer or word counter). |
| 67 | **Review** — add tests + a README to the CLI tool. |
| 68 | Web server: minimal REST API (Flask/FastAPI or Express) with GET/POST. |
| 69 | Add CRUD endpoints + input validation + proper status codes. |
| 70 | Databases: SQLite — create tables, insert, query with JOINs. |
| 71 | Connect the API to the database; persist your To-Do app. |
| 72 | Authentication basics: hashed passwords, login endpoint, tokens. |
| 73 | Frontend basics: HTML page that fetches from your API and renders a list. |
| 74 | **Review** — deploy the API (Render, Railway, Fly.io, etc.). |
| 75 | Concurrency: threads vs async — download 20 URLs concurrently. |
| 76 | Web scraping: pull a table from a webpage into CSV. |
| 77 | Data processing: analyze a CSV (group, aggregate, find outliers). |
| 78 | Logging & debugging: add structured logging; use a debugger to step through a bug. |
| 79 | Git workflow: branches, pull requests, resolve a merge conflict on purpose. |
| 80 | **Checkpoint** — Project 2: a URL shortener (API + DB + simple frontend). |

---

## Phase 5 — Advanced & Mastery (Days 81–100)
*Goal: hard problems, system thinking, and a portfolio piece.*

| Day | Workout |
|---|---|
| 81 | Hard DP: longest palindromic substring, word break, matrix chain. |
| 82 | Hard graphs: Bellman-Ford, Floyd-Warshall, minimum spanning tree (Kruskal/Prim). |
| 83 | Advanced trees: segment tree for range sums; Fenwick tree. |
| 84 | String algorithms: KMP pattern matching, Rabin-Karp. |
| 85 | Hard problems: trapping rain water, LRU cache, median of two sorted arrays. |
| 86 | **Review** — timed mock: 1 Hard problem in 45 min, then study the optimal solution. |
| 87 | Write your own: a tiny interpreter for arithmetic expressions (tokenizer + parser + evaluator). |
| 88 | Extend the interpreter with variables and `if`/`while`. |
| 89 | Implement a hash map from scratch (open addressing or chaining, with resizing). |
| 90 | Implement a simple in-memory key-value store with a TCP interface (Redis-lite). |
| 91 | System design: design a rate limiter; implement token bucket. |
| 92 | System design: design a message queue; implement a producer/consumer with workers. |
| 93 | Caching & performance: profile a slow program, optimize it 10x. |
| 94 | Testing mastery: property-based tests, mocking, >90% coverage on one module. |
| 95 | CI/CD: GitHub Actions pipeline that runs tests and lints on every push. |
| 96 | **Capstone Day 1** — pick a real project (chat app, markdown blog engine, expense tracker, game, etc.). Write the spec and architecture. |
| 97 | **Capstone Day 2** — build the core logic + data layer. |
| 98 | **Capstone Day 3** — build the interface (API/UI/CLI) + tests. |
| 99 | **Capstone Day 4** — deploy, write documentation, record a demo. |
| 100 | **Graduation** — review all 100 commits. Write a reflection: what you learned, what was hardest, what's next. Share your repo. |

---

## Tips to Survive 100 Days
- **Stuck >45 min?** Look at a hint, not the full solution. Then re-implement from memory the next day.
- **Track it:** keep a `progress.md` with one line per day.
- **Stack problems:** Days 21–60 pair well with LeetCode/NeetCode/Codewars for extra reps.
- **Miss a day?** Don't double up — just continue. The streak matters less than the habit.

Want me to adapt this for a specific language, a specific goal (interviews, web dev, data science), or a shorter daily time budget?