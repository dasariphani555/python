# python
def val():
  s=0
  y=x
  while x>0:
    rev=x%10
    x=x\\10
    s=s%10+rev
  print(s)
  if s==y:
    print("palindrome",y)
  else:
    print("not palindrome",y)
  
