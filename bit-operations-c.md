# How to bit operations (C version)
``!`` logical not, nonzero -> 0, 0 -> 1

the rest are bitwise (compares each bit and does the operator)
``~`` not, flips bits
``&`` and
``^`` xor
``|`` or
``+`` addition
``x + (~y + 1)`` fancy subtraction
``<<`` left shift (fill with 0s)
``>>`` right shift (fill with most significant bit)
