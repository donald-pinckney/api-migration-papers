# Main Idea

Look at a set existing clients and determine statically a model for API usage. Done with AST tree based diffing / matching across the set of clients.

Then, look at how the clients changed to adapt to the library update. Unify these changes with some ad-hoc CFG matching / diffing stuff, and then try to apply that to the target.