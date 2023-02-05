# Activities

## Task 1/3: Divide-and-conquer

The code in `./src/pow1.cpp` and `./src/pow2.cpp` compute the power `pow(x, n)` using iterative and recursive approaches respectively.

> Refer to the following [link](https://www.techiedelight.com/power-function-implementation-recursive-iterative/).

- What is the time complexity for both approaches?
  - time complexity for both approaches is O(log n).

## Task 2/3: Divide-and-conquer vs Decrease and conquer

- In many literature, Binary search is referred to use divide-and-conquer technique. Discuss in groups whether you agree or disagree and justify your answers. Refer to the the following thread: [Why Binary Search is not a divide and conquer algorithm?](https://stackoverflow.com/questions/8850447/why-is-binary-search-a-divide-and-conquer-algorithm)
  -if we consider divide-and-conquer as a strategy that breaks down a problem into smaller subproblems, while decrease-and-conquer reduces the size of the problem in each step until it becomes trivial to solve. from this perspective, Binary search can be classified as decrease and conquer as at one point it will be trivial to halve the input. however it can also be considered as divide and conquer as we are reducing the future input by reducing the problem in subproblems. 

## Task 3/3: Individual, at home

- Refactor the code in `./src/pow2.cpp` to optimize the time complexity of the recursive approach. Use `./src/pow3.cpp` as a starter.
- Refactor the code in `pow1.cpp` and `pow2.cpp`, as follows:
  - Replace `printf()` with` std::cout()`
  - Include the right headers e.g. `iostream`

## Links

- https://www.techiedelight.com/power-function-implementation-recursive-iterative/
- https://cpp.sh/
