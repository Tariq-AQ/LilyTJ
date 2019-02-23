import random as r


print(r'\version "2.18.2"')
print(r'\language "english"')
print(r'\score{')
print(r'{ \clef bass')


listOfNotes, listOfDuration = ["a","as","b","bs","c","cs","d","ds","e","f","fS","g","gs"], ["4","8","16","32","64","128"]
for i in range(20):
    print(r.choice(listOfNotes),r.choice(listOfDuration), sep = '')



print('}')
print('\layout{}')
print('\midi{}')
print('}')
