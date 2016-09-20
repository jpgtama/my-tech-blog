exp = 1
exp = a
exp = exp ( '+' exp)*
exp = exp ( '-' exp)*
exp = exp ( '*' exp)*
exp = exp ( '/' exp)*
exp = '(' exp ')'
exp = <id> '()'
exp = <id> '(' paramlist ')'
paramlist = exp (',' exp)*




1*2*3+4*5*6+7*8*9

(1+2+3)*(4+5+6)*(7+8+9)

a

a + b

now()

max(1, 2)

max(a, b)
max(min(a, b), c)
