# Best Movie CodeChef


This C++ program is designed to handle multiple test cases. For each test case, it reads an integer `N`, representing the number of items or options. For each of these `N` entries, it reads two integers: `A` and `B`. The program is interested in only those entries where `A >= 7`. Among these, it keeps track of the minimum value of `B` — possibly representing the cost or value associated with items that meet the condition.

After processing all `N` entries for a test case, the program checks if any valid entry (where `A >= 7`) was found. If no such entry exists, it prints `-1` to indicate failure or absence of a valid option. Otherwise, it prints the minimum cost (`B`) among the valid entries. The logic is wrapped inside a loop that runs `T` times, once for each test case.
