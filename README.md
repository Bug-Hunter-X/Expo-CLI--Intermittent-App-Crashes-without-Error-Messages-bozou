# Expo CLI Intermittent Crash Bug

This repository demonstrates a bug encountered while using Expo CLI where the application would crash without providing any specific error messages in the console. The crashes were random and difficult to debug.

## Bug Description

The application would intermittently crash during runtime. There were no error messages or warnings in the console to provide clues about the cause of the crash.  Standard debugging techniques such as console.log statements were unsuccessful in identifying the root of the problem.

## Solution

The solution involved a thorough review of asynchronous operations and potential race conditions in the application.   A potential fix is adding more robust error handling within asynchronous functions.  Specific details and code changes are provided in the `bugSolution.js` file.