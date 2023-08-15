
def right_justify(s):
    wsp=' '
    s2=''
    for i in range(70):
        s2=s2+ wsp;
    s2=s2+s
    return s2
# lesson 2
def do_twice(f):
    f()
    f()
def do_for(f1):
    f1()
    f1()
    f1()
    f1()
def print_row():
    print('+----',end='')
    
def print_row2():
    print('|    ',end='')
    print('|    ',end='')
    print('|')
    
def printrow():
    do_twice(print_row)
    print('+')
    do_for(print_row2)
    do_twice(print_row)
    print('+')
    do_for(print_row2)
    do_twice(print_row)
    print('+')
