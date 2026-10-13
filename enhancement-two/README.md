# Enhancement Two: Algorithms and Data Structures

## CS 300 Course Planning Assistant

This artifact demonstrates algorithms and data-structure improvements to a C++ course-planning application. The original program stored and searched course records in a custom hash table. The enhanced version also represents prerequisite relationships as a directed graph and uses Kahn's topological-sort algorithm to produce an order in which every prerequisite appears before the courses that depend on it.

The graph is stored with an adjacency list, prerequisite counts, and a queue. Building and traversing the graph requires **O(V + E) time** and **O(V + E) additional space**, where `V` is the number of courses and `E` is the number of prerequisite relationships.

The enhancement also adds line-specific validation for malformed records, duplicate courses, repeated prerequisite relationships, missing prerequisites, self-dependencies, and circular dependencies. Strict C++17 compilation and AddressSanitizer/UndefinedBehaviorSanitizer testing provide additional implementation evidence.

The complete submission package includes:

- Original and enhanced C++ source code
- Four valid and invalid CSV test datasets
- Final enhancement narrative with design decisions, Big-O analysis, course outcomes, and embedded evidence
- Strict compiler, functional validation, topological-order, cycle-detection, and sanitizer evidence

## Downloads

The complete submission is organized into three GitHub-compatible archives:

- **[Final enhancement narrative](./CS300-Final-Narrative.zip)**
- **[Original and enhanced source code with test datasets](./CS300-Original-and-Enhanced-Source.zip)**
- **[Screenshots and test evidence](./CS300-Screenshots-and-Test-Evidence.zip)**

Together, these archives contain all organized materials for Enhancement Two of the CS 499 Computer Science Capstone ePortfolio.
