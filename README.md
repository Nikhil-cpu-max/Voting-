# Voting-
a=('''welcome to the voting machine
1 for BJP, 2 for congress, 3 for national party''')
print(a)
age=int(input("enter you age "))
if age>=18:
  print("you can vote")
  vote=int(input(" enter your choice for vote 1,2,3"))
  if vote==1:
    print("you have voted for BJP")
  elif vote==2:
    print("you have voted for cingress")
  elif vote==3:
    print("you have voted for national party")
else:
  print("you cannot vote")
