# inicio.hub


1.
R = (V AND F) OR NOT (V AND F)
R = F OR NOT
R = F OR V
R = V

2.
R = (V OR F) AND NOT (V AND F)
R = (V) AND NOT (F)
R = V AND V
R = V
3.
R = NOT (V AND F) AND NOT(V OR F)
R = NOT (F) AND NOT (V)
R = V AND NOT V 
R = V AND F
R = F
4.
R= ((V AND F) AND (V OR F)) OR  (V AND F)
(F AND V) OR F
F OR F
F
5.
(V OR F) OR (NOT(V AND F) OR NOT (V OR F))
V OR (NOT F) OR F
V OR (V OR F)
V OR V
V 
6.
R = NOT (V OR F) AND (NOT(V OR F) OR (V AND F))
NOT V AND (NOT V) OR F
F AND (F OR F)
F AND F
F
7.
R = (V OR F) OR ((V AND F) AND NOT(V OR F))
V OR (F AND (NOT V))
V OR F
V
8.
R = (NOT (V AND F) AND (V AND F)) OR (V OR F)
(NOT (F) AND F) OR V
(V AND F) OR V
F OR V
V
9.
((NOT (V)OR F) AND NOT (V AND F)) OR NOT (V OR F)
(F OR F) AND (NOT F) OR NOT V
F AND V OR (NOT V)
F OR (NOT V)
F OR F 
F
10.
((NOT (V) OR F) AND (V AND NOT (F))) OR NOT (V OR F)
(F OR F) AND (V AND V) OR NOT V
(F AND V) OR F
F OR F
F