# A-or-B
# cook your dish here
n = int(input())
for s in range(n):
  a,b=map(int,input().split())
  ab=(500-(2*a))+(1000-(4*(a+b)))
  ba=(1000-(4*b))+(500-(2*(a+b)))
  print(max(ab,ba))
