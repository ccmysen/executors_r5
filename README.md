executors_r5
============

Prototype of the Executors proposal for ISO C++ R5 (N4414)

This is the basic implementation of the executors proposal for the C++ standards committee (current proposal is N4414).

This directory includes the minimal API required for execution on a fixed executor and implementations for 4 different executor types (system_executor, loop_executor, thread_pool_executor, and thread_per_task_executor).
It also includes a small library of helper functions to support common mechanisms for tracking work (e.g. with futures and with continuations).

It also includes a basic test suite to ensure some of the semantics of each executor are maintained.
