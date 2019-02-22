Add your answers to the Algorithms exercises here.
1

a n
b n^4
c 2^n

2
floor = n // 2
loop:
    toss an egg off floor 
    if egg doesn't break: 
        toss off floor + 1
            if egg doesn't break:
                _f_ = floor
            else:
                floor = n - floor // 2
    else floor = floor // 2

log n
