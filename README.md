# Python-Code-Sample-1
x1, y1, x2, y2 = int(input()), int(input()), int(input()), int(input())
if y2 == (-x2 + x1 + y1) or y2 == (x2 - x1 + y1) or (x1 == x2 or y1 == y2):
    print("YES")
else:
    print("NO")
