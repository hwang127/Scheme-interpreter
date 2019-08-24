# Scheme-to-Python interpreter

#This is a scheme interpreter built using Python. To start an interactive Scheme interpreter session, type:

#python3 scheme.py

#You can use your Scheme interpreter to evaluate the expressions in an input file by passing the file name as a command-line argument to scheme.py:

#python3 scheme.py tests.scm

#To exit the Scheme interpreter, press Ctrl-d or evaluate the exit procedure:

#scm> (exit)

Here are all the files included in the archive:

scheme.py: implements the REPL and a evaluator for Scheme expressions

scheme_reader.py: implements the reader for Scheme input

scheme_tokens.py: implements the tokenizer for Scheme input

scheme_builtins.py: implements built-in Scheme procedures in Python

buffer.py: implements the Buffer class, used in scheme_reader.py

ucb.py: utility functions for use in 61A projects

questions.scm: contains skeleton code for Phase IV

tests.scm: a collection of test cases written in Scheme

ok: the autograder

tests: a directory of tests used by ok
