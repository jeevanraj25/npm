## i have published zenitu-ui in npm. I have learnt how to publish our own npm repo

# zenitu-ui


A simple and lightweight React UI component library featuring a custom `useCounter` hook to streamline counter functionality in your applications.

## Installation

Install the `zenitu-ui` package using npm or yarn:

**npm:**

```bash
npm install zenitu-ui

Usage
useCounter Hook
The useCounter hook provides a state management solution for counters, including functions to increment and decrement the value. This simplifies building counter components in your React applications.

Importing useCounter:
```bash
 import { useCounter } from 'zenitu-ui';


    import React from 'react';
    import { useCounter } from 'zenitu-ui';

    const CounterComponent = () => {
    const { count, increment, decrement } = useCounter();

    return (
        <div>
        <h1>Counter: {count}</h1>
        <button onClick={increment}>Increment</button>
        <button onClick={decrement}>Decrement</button>
        </div>
    );
    };

    export default CounterComponent;


    
