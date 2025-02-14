# Stack Overflow Error in Euclidean Algorithm

This repository contains a JavaScript implementation of the Euclidean algorithm that suffers from a stack overflow error for specific inputs. The `bug.js` file demonstrates the flawed implementation, while `bugSolution.js` provides a corrected version.

The bug arises because the recursive calls to `foo` can nest too deeply for large differences between `a` and `b`, exceeding the JavaScript call stack limit. The solution involves using an iterative approach to avoid excessive recursion.