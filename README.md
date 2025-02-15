# React useEffect Hook Missing Dependency

This repository demonstrates a common error in React applications involving the `useEffect` Hook: missing dependencies in the dependency array.  This can lead to infinite re-renders and performance issues.

## The Problem

The `useEffect` Hook runs after every render. If the effect modifies state or props, and it lacks a proper dependency array, it will cause an infinite re-render loop.