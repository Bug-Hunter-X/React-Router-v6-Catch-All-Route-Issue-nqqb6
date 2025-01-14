# React Router v6 Catch-All Route Issue

This repository demonstrates a common issue encountered when using the catch-all route ('*') in React Router v6.  The problem arises when the catch-all route fails to match and display the intended 'Not Found' component when navigating to an invalid URL.

The issue is resolved by ensuring the catch-all route is placed last in the `Routes` component.  See `AppSolution.js` for the corrected code.