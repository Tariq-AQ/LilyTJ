import random as r


print(r'\version "2.18.2"')
print(r'\language "english"')
print(r'\score{')
print(r'{ \clef bass')


list = ["a","as","b","bs","c","cs","d","ds","e","f","fs","g","gs",]
for i in range(20):
    print(r.choice(list))



print('}')
print('\layout{}')
print('\midi{}')
print('}')


