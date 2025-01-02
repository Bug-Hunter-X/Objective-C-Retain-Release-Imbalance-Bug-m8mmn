# Objective-C Retain/Release Imbalance Bug

This repository demonstrates a subtle bug in Objective-C related to manual memory management.  The bug arises from an imbalance in `retain` and `release` calls, resulting in an object's reference count remaining higher than expected, preventing its timely deallocation. This differs from typical memory leaks as the object is released, but not sufficiently. 

The `bug.m` file contains the buggy code, while `bugSolution.m` shows how to correctly balance `retain` and `release` calls to avoid the issue.

## Setup

1. Clone this repository.
2. Open the project in Xcode.
3. Build and run.