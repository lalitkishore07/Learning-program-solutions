# 1. E-Commerce Product Search using Binary Search

## Project Overview

This Java project implements a **binary search-based product lookup** system for an e-commerce platform.

Each product has:
- `productId`
- `name`
- `category`

The list of products is first **sorted alphabetically by name**, then searched using **Binary Search** for fast performance.

---

## Features

- Binary Search for product lookup
- Case-insensitive sorting using `Comparator`
- OOP structure with `Product` class
- User-friendly output format

---

## Time Complexity

| Operation              | Time Complexity       | Notes                                         |
|------------------------|------------------------|-----------------------------------------------|
| Sorting the products   | `O(n log n)`           | Using `Arrays.sort()` with a custom comparator |
| Binary Search lookup   | `O(log n)`             | Efficient for large product lists             |
| Overall lookup process | `O(n log n)` (1st time) then `O(log n)` | Sorting is done once, then fast searches |

➡ After the initial sorting, repeated searches are **very fast** (`O(log n)` per search).

---

## Technologies Used

- Java
- Arrays
- Comparator API
- Binary Search Algorithm
- Object-Oriented Programming

---

## How to Run

1. **Compile** the Java file:
   javac ECommerceSearch.java



---

## 2. Financial Forecasting using Recursion

# Financial Forecasting - Future Value Calculation (Recursive)

## Project Overview

This project calculates the **future value of an investment** using a recursive algorithm based on the compound interest formula.

It demonstrates:
- The power of recursion
- Basic financial modeling
- Optimizations for recursive calls

---

## Formula Used
Future Value = Present Value × (1 + rate)^years


This is implemented recursively.

---

## Features

- Recursive method to compute future value
- Supports principal, annual rate, and number of years
- Easy to extend for more financial models

---

## Time Complexity

- **Time**: O(n) where n = number of years
- **Space**: O(n) due to recursion stack

---

## How to Run

1. Compile:
   javac FinancialForecast.java

