HMI Simulation System
Project Overview
The HMI Simulation System is a software solution designed to simulate functionalities typically found in automotive Human-Machine Interface (HMI) clusters. Developed in C++, the system provides an interactive platform for menu navigation, real-time vehicle data display, touchscreen input handling, and customizable themes/skins, making it ideal for simulating the core operations of in-vehicle HMI systems.

Project Objectives
The main goals of this project are to:

Menu Navigation System: Develop a hierarchical menu structure for user navigation.
Instrument Cluster Data Display: Simulate a real-time display of essential vehicle data.
Touchscreen Event Handling: Implement an event-driven approach for touchscreen interactions.
Skin Customization: Enable users to customize the HMI interface's appearance with different skins and themes.
Requirements
Programming Language: C++11 or higher
Compiler: g++, clang++, or any other compatible C++ compiler
Standard Libraries:
<iostream>, <map>, <string>, <vector>, <thread>, <queue>, <random>, <chrono>
Tasks and Implementation
Task 1: Menu Navigation System
Description: A hierarchical menu navigation system is implemented using C++ classes and data structures to facilitate user navigation within the HMI system.

Features:

Navigation through multiple menu levels (up, down, enter, and back).
Console-based display of menu options.
Keyboard interaction to navigate and select options.
Task 2: Simulate Instrument Cluster Data Display
Description: This component simulates a vehicle data display that shows real-time updates for various parameters, such as speed, fuel level, and engine temperature.

Features:

Class-based data management for vehicle parameters.
Warnings for threshold limits (e.g., fuel levels, engine temperature).
Task 3: Event Handling for Touchscreen Input
Description: An event-driven system handles touchscreen interactions such as taps, swipes, and other touch gestures.

Features:

Event class representation to model user actions.
Event queue management for processing multiple touch events.
Handling specific touchscreen events like Tap and Swipe.
Task 4: HMI Skin Customization System
Description: This module enables customization of the HMI's appearance, allowing the user to select from different skins or themes.

Features:

A Theme class with customizable attributes such as colors, font size, and other visual elements.
Use of std::map for managing and storing multiple themes.
User interface for selecting and previewing skins/themes.
Week 4 Tasks: STL Algorithm Practice
Task 1: Working with STL Algorithms
Goal: Practice using various STL algorithms to manage and manipulate HMI control states.

Algorithms Used:

std::for_each, std::find, std::find_if, std::adjacent_find, std::count, std::count_if, std::equal.
Task 2: Iterating and Finding in Containers
Goal: Efficiently iterate through containers and search for specific elements.

Containers Used:

std::vector for dynamic widgets.
std::set for static widgets.
Operations:

Print the contents of dynamic widgets.
Search for specific widgets using iterators.
Task 3: Advanced STL Operations
Goal: Perform transformations and modifications on HMI control states using advanced STL algorithms.

Operations:

std::copy, std::fill, std::generate, std::transform, std::replace, std::remove_if, std::reverse, std::partition.
Task 4: Sorting, Searching, and Merging
Goal: Practice sorting, searching, and merging containers and using set operations.

Operations:

std::sort, std::stable_sort, std::lower_bound, std::upper_bound, std::merge, std::inplace_merge, std::set_union, std::set_intersection.
Task 5: Implementing Design Patterns
Goal: Implement common design patterns to enhance the structure and scalability of the HMI system.

Design Patterns Implemented:

Singleton: HMISystem class to manage the global state of the HMI system.
Factory: Factory method for creating instances of Button, Slider, and other UI elements.
Observer: Notify widgets when a mode change occurs (e.g., from night mode to day mode).
Strategy: Define different rendering strategies for 2D vs. 3D visualizations.

Submission Requirements
Source Code: The source code for each task should be uploaded to a Git repository (GitHub, GitLab, etc.).
Detailed Comments: Provide detailed comments in the code explaining each step and its relevance to the automotive HMI system.
Report: A final report summarizing the learning experience, challenges faced, and solutions implemented throughout the project.