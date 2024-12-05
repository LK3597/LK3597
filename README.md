aa = int (input('qual a primeira nota do aluno A ?'))
aa2 = int (input('qual a segunda nota do aluno A ?'))
ab = int (input('qual a primeira nota do aluno B ?'))
ab2 = int (input('qual a segunda nota do aluno B ?'))
am = aa + aa2 
am2 = ab + ab2
aaa = am / 2
aab = am2 / 2
d = aaa - aab
d2 = d * 2 
c = int (input('qual a primeira nota do aluno c ?'))
cc = int (input('qual a segunda nota do aluno C ?'))
c1 = c + cc
c2 = c1 / 2

dd= int (input('qual a primeira nota do aluno D ?'))
ddd= int (input('qual a segunda nota do aluno D ?'))

d1 = dd + ddd 
dd1 = d1 / 2

p = c2 - dd1
print (' a media do aluno A é {} a media B é {} e a diferença é {}'.format (aaa , aab , d) ,
       ('A media do aluno C é {} a media do aluno D é {} e a diferença é {}'.format (c2 , dd1 , p)))
