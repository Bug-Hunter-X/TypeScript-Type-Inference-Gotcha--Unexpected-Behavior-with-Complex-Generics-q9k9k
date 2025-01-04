# TypeScript Type Inference Gotcha

This repository demonstrates a subtle bug in TypeScript related to type inference with complex generic types and function overloads. The issue arises from a mismatch between the inferred types and the expected behavior at runtime.

## Problem

The `combine` function aims to concatenate two number arrays. While the type definition seems correct, the actual behavior might be unexpected under certain conditions, especially when dealing with more complex scenarios involving generics.

## Solution

The solution involves carefully reviewing the type definitions and ensuring that the type inference aligns perfectly with the intended behavior. This may involve explicitly specifying types or using type assertions where necessary to guide the compiler.