# Execution Context?
It's simply the environment where JavaScript runs your code.
Every time you call a function or start a JS file, the browser (or Node.js) creates an Execution Context, which includes three main components:

Variable Environment 
  – the place where variables declared with var, let, or const are stored.
Scope Chain 
  – The Scope Chain is the sequence of nested scopes that JavaScript follows when trying to resolve a variable. It starts from the current scope and moves outward to parent scopes, all the way up to the global scope.
this binding 
  – the value of this keyword, which depends on how the function is called.
