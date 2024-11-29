# Week 4: STL Algorithms and Design Patterns

## Overview
Week 4 focuses on enhancing the **HMI Simulation System** by integrating **STL Algorithms** and implementing **Design Patterns**. The aim was to practice using advanced C++ features such as **STL algorithms**, iterators, transformations, and sorting, while also implementing common **design patterns** to improve the system’s architecture and flexibility.

## Tasks and Implementation

### Task 1: Working with STL Algorithms
- **Goal**: Apply various **STL algorithms** to manipulate HMI control states.
- **Algorithms Used**:
  - `std::for_each`
  - `std::find`
  - `std::find_if`
  - `std::adjacent_find`
  - `std::count`
  - `std::count_if`
  - `std::equal`

### Task 2: Iterating and Finding in Containers
- **Goal**: Efficiently iterate through containers and search for specific elements.
- **Containers Used**:
  - `std::vector` for dynamic widgets.
  - `std::set` for static widgets.
- **Operations**:
  - Print the contents of dynamic widgets.
  - Search for specific widgets using iterators.

### Task 3: Advanced STL Operations
- **Goal**: Use advanced STL algorithms for data transformation and manipulation.
- **Operations**:
  - `std::copy`
  - `std::fill`
  - `std::generate`
  - `std::transform`
  - `std::replace`
  - `std::remove_if`
  - `std::reverse`
  - `std::partition`

### Task 4: Sorting, Searching, and Merging
- **Goal**: Sort, search, and merge containers using STL algorithms.
- **Operations**:
  - `std::sort`
  - `std::stable_sort`
  - `std::lower_bound`
  - `std::upper_bound`
  - `std::merge`
  - `std::inplace_merge`
  - `std::set_union`
  - `std::set_intersection`

### Task 5: Implementing Design Patterns
- **Goal**: Apply design patterns to enhance system structure.
- **Design Patterns Implemented**:
  - **Singleton**: For managing the global state of the HMI system.
  - **Factory**: To create UI elements like buttons and sliders.
  - **Observer**: To notify widgets when a mode change occurs.
  - **Strategy**: To define different rendering strategies for 2D vs. 3D visualizations.
