[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-10

### The Call Stack and Debugging
- A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions.

- When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.

- Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.

- When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.

- If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.

- The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

- At the most basic level, a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

- LIFO means : last function that gets pushed into the stack is the first to be pop out, when the function returns.

 ### What causes a stack overflow?
A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.
 ### Types of error messages .
Reference errors.

Syntax errors

Range errors
Type errors
Attribution https://developer.mozilla.org/en-US/docs/Glossary/Call_stack 

https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/ 
https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c