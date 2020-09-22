# Coursera-Python-for-Everybody-Specialization-3.3
Code for assignment 3.3 of Python for Everybody Specialization offered by Coursera

score = input ("Enter score: ")

sc = float (score)

if ((sc > 0.0) and (sc <= 1.0)):

  if sc >= 0.9:
        print ('A')
  
  elif sc >= 0.8:
        print ('B')
  
  elif sc >= 0.7:
        print ('C')
  
  elif sc >= 0.6:
        print ('D')
  
  elif sc < 0.6:
        print ('F')

else:
    print ('Please enter the score between 0.0 and 1.0 range')
