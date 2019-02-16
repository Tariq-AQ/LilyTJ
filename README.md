# LilyTJ
import random as r

def header():
    print(r'\version "2.18.2"')
    print(r'\language "english"')
    print(r'\score{')
    print(r'{ \clef bass')


def gen_chrom():
        if r.randint(0,12)==0:print('c') 
        elif r.randint(0,12)==1:print('cs')
        elif r.randint(0,12)==2:print('d')
        elif r.randint(0,12)==3:print('ds')
        elif r.randint(0,12)==4:print('e')
        elif r.randint(0,12)==5:print('f')
        elif r.randint(0,12)==6:print('fs')
        elif r.randint(0,12)==7:print('g')
        elif r.randint(0,12)==8:print('gs')
        elif r.randint(0,12)==9:print('a')
        elif r.randint(0,12)==10:print('as')
        elif r.randint(0,12)==11:print('b')

#notes = ["e" + n * "'" for n in range(1, 5)]

#while gen_chord() 
def makerandom():
    for i in range (0,200):
        gen_chrom()


def ender():
    print(r'}')
    print(r'\layout{}')
    print(r'\midi{}')
    print(r'}')


header()
makerandom()
ender()
