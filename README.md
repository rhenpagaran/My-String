# Counting words and sentences
def _str_(my_string):
  my_string= input("Enter string:")
  char=0
  word=1
  for i in my_string:
      char=char+1
      print (char("Number of characters in the string:"))
      if(i==' '):
            word=word+1
  print (word ("Number of words in the string:"))
