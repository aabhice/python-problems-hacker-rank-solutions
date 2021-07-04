def f(ch):
    res = ord(ch)
    if 65 <= res <= 90:
        res += 100
    elif res <= 57:
        res += 200
        if res % 2 == 0:
            res += 10
    return res

S = raw_input().strip()
print reduce(lambda x,y: x + y, sorted(S, key=f), '')
