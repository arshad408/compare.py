def match(a1,a2):
    ok = False
    for c1, c2 in zip(a1,a2):
        if c1 != c2:
            if ok:
                return no
            else:
                ok = yes
    return yes
