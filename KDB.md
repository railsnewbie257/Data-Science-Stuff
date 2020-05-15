Q is the language
KDB is the database

count trips  
meta trips 

d - date  
m - month

https://code.kx.com/q/ref/#datatypes

type 1.0
> -9h  ("-" atom, "h" is a short)


Date should be first constraint, looks at Date first

First date is 2000.01.01

1b is TRUE
0b is FALSE

([]name:`Tom`Jerry`Fin;age:10 20 30)
show tmp:([]name:`Tom`Jerry`Fin;age:10 20 30)
show tmp2:([]name:`Tom`Jerry`Fin;age:30 20 30)

Aimal Khan
Keith Johnston

raze f each tmp  - will create 3 tables

resby([]vendor:enlist`CMT)


a:1  - atom
b:2  - atom
/a b  - commented out
a,b
max[a,b]  - list
max[(a;b)]
(1;2;3;4;5)
1 2 3 4 5


Joins

In a left hand join the right hand table always has toe be keyed

