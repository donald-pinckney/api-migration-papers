# Notes

In addition to 1996 - Notkin types of changes,
Coccinelle can handle rewriting entire function bodies to accommodate a change.

Main idea: patch annotations do **NOT** match syntactically, but match patterns in the CFG of the program. The annotation language is a patch-file-looking sugar over CTL (temporal logic), and matching to the CFG is done with a model checker.