# pep8

Reference: [Pep8 Error Codes](http://pep8.readthedocs.io/en/latest/intro.html#error-codes)

# E1
Indentation
# E101
indentation contains mixed spaces and tabs
# E111
indentation is not a multiple of four
# E112
expected an indented block
# E113
unexpected indentation
# E114
indentation is not a multiple of four (comment)
# E115
expected an indented block (comment)
# E116
unexpected indentation (comment)
# E121
continuation line under-indented for hanging indent
# E122
continuation line missing indentation or outdented
# E123
closing bracket does not match indentation of opening bracket's line 
# E124
closing bracket does not match visual indentation
# E125
continuation line with same indent as next logical line
# E126
continuation line over-indented for hanging indent
# E127
continuation line over-indented for visual indent
# E128
continuation line under-indented for visual indent
# E129
visually indented line with same indent as next logical line
# E131
continuation line unaligned for hanging indent
# E133
closing bracket is missing indentation
# E2 
Whitespace*
# E201
whitespace after '('
# E202
whitespace before ')'
# E203
whitespace before ':'
# E211
whitespace before '('
# E221
multiple spaces before operator
# E222
multiple spaces after operator
# E223
tab before operator
# E224
tab after operator
# E225
missing whitespace around operator
# E226
missing whitespace around arithmetic operator
# E227
missing whitespace around bitwise or shift operator
# E228
missing whitespace around modulo operator
# E231
missing whitespace after ',', ';', or ':'
# E241
multiple spaces after ','
# E242
tab after ','
# E251
unexpected spaces around keyword / parameter equals
# E261
at least two spaces before inline comment
# E262
inline comment should start with '# '
# E265
block comment should start with '# '
# E266
too many leading '#' for block comment
# E271
multiple spaces after keyword
# E272
multiple spaces before keyword
# E273
tab after keyword
# E274
tab before keyword
# E275
missing whitespace after keyword
E3 Blank line*
# E301
expected 1 blank line, found 0
# E302
expected 2 blank lines, found 0
# E303
too many blank lines (3)
# E304
blank lines found after function decorator
E4 Import*
# E401
multiple imports on one line
# E402
module level import not at top of file
E5 Line length*
# E501
line too long (82 > 79 characters)
# E502
the backslash is redundant between brackets
E7 Statement*
# E701
multiple statements on one line (colon)
# E702
multiple statements on one line (semicolon)
# E703
statement ends with a semicolon
# E704
multiple statements on one line (def)
# E711
comparison to None should be 'if cond is None:'
# E712
comparison to True should be 'if cond is True:' or 'if cond:'
# E713
test for membership should be 'not in'
# E714
test for object identity should be 'is not'
# E721
do not compare types, use 'isinstance()'
# E731
do not assign a lambda expression, use a def
# E9 
Runtime
# E901
SyntaxError or IndentationError
# E902
IOError
# W1 
Indentation warning*
# W191
indentation contains tabs
# W2 
Whitespace warning*
# W291
trailing whitespace
# W292
no newline at end of file
# W293
blank line contains whitespace
W3 Blank line warning*
# W391
blank line at end of file
W5 Line break warning*
# W503
line break occurred before a binary operator
# W6 
Deprecation warning*
# W601
.has_key() is deprecated, use 'in'
# W602
deprecated form of raising exception
# W603
'<>' is deprecated, use '!='
# W604
backticks are deprecated, use 'repr()'
