# matching-a-word-yes-in-different-cases
#using upper() 
t=int(input())
for _ in range(t):
  s=input()
  s=s.upper()
  if s=="YES":
    print("Yes")
  else:
    print("No")
    
#using lower()   
t=int(input())
for _ in range(t):
  s=input()
  s=s.lower()
  if s=="yes":
    print("Yes")
  else:
    print("No")
