# Learning warp

Warp is a Python framework for writing high-performance code. Warp takes regular Python functions and JIT compiles them to efficient kernel code that can run on the CPU or GPU.

## What is JIT Compilation?

JIT (Just-In-Time) compilation is a process where code is compiled into machine code at runtime (just before execution) rather than being precompiled. This allows the program to optimize its performance dynamically based on the specific hardware and runtime environment - Python with performance close to compiled languages like C++.

Example in Context of Warp:

Warp uses JIT compilation to transform regular Python functions into highly efficient machine-level code optimized for CPUs or GPUs. For instance:

1. A Python function is passed to Warp.
2. At runtime, Warp compiles this function into a GPU kernel (e.g., CUDA) or CPU code.
3. The compiled code is executed, leveraging parallel hardware for better performance.

This makes frameworks like Warp suitable for tasks requiring high computational efficiency, such as graphics, simulations, or machine learning.

## How to run

```
pip install virtualenv
virtualenv env
source env/bin/activate
pip install -r requirements.txt
```

