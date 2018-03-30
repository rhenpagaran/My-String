# Counting words and sentences

my_sentence= input("Enter sentence:")
char=0
word=1
for i in my_sentence:
      char=char+1
      if(i==' '):
            word=word+1
print("Number of words in the sentence:")
print(word)
print("Number of characters in the sentence:")
print(char)
