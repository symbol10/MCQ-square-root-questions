# MCQ-square-root-questions
print("Title of program: MCQ revision program")
print()

counter = 0
score = 0
total_num_of_qn = 3


counter +=1
tracker = 0

while tracker !=1:
  
  print("Q"+str(counter)+") "+ "What is the square root of 4?")
  print("   a) 0")
  print("   b) 1")
  print("   c) 2")
  print("   d) I don't know")
  answer = input("Your answer: ")
  answer = answer.lower()
  if answer == "a":
    output = "Wrong. Try again."
    score -=1
  elif answer == "b":
    output = "Wrong. Try again."
    score -=1
  elif answer == "c":
    output = "Yes, that's right!"
    tracker =1
    score +=1
  elif answer == "d":
    output = "Wrong. You are being lazy :/."
    score -=1
  else:
    output = "Please choose a, b, c or d only."
  
  print()
  print(output)
  print()
  print("Your current score: " + str(round((score/total_num_of_qn*100),1)) + "%"  )
  print()
  print()
  


counter +=1
tracker = 0

while tracker !=1:
  
  print("Q"+str(counter)+") "+ "What is the square root of 16?")
  print("   a) 1")
  print("   b) 4")
  print("   c) 8")
  print("   d) I don't know")
  answer = input("Your answer: ")
  answer = answer.lower()
  if answer == "a":
    output = "Wrong. Try again."
    tracker =1
    score +=1
  elif answer == "b":
    output = "Yes! You are correct!"
    score -=1
  elif answer == "c":
    output = "Wrong. Try again."
    score -=1
    
  elif answer == "d":
    output = "Wrong. You are being lazy :/"
    score -=1
  else:
    output = "Please choose a, b, c or d only."

  print()
  print(output)
  print()
  print("Your current score: " + str(round((score/total_num_of_qn*100),1)) + "%"  )
  print()
  print()
  
  

counter +=1
tracker = 0

while tracker !=1:
  
  print("Q"+str(counter)+") "+ "What is the square root of 25?")
  print("   a) 2")
  print("   b) 4")
  print("   c) 5")
  print("   d) I don't know")
  answer = input("Your answer: ")
  answer = answer.lower()
  if answer == "a":
    output = "Wrong. Think again."
    score -=1
  elif answer == "b":
    output = "Wrong.  Think again."
    score -=1
  elif answer == "c":
    output = "That is absolutely... correct !!"
    score -=1
    
  elif answer == "d":
    output = "Wrong.   Think again."
    tracker =1
    score +=1
  else:
    output = "Please choose a, b, c or d only."

  

  print()
  print(output.lower())
  print()
  print("Your current score: " + str(round((score/total_num_of_qn*100),1)) + "%"  )
  print()
  print()
  
print("End of quiz!")
  
