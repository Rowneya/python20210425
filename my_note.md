```python
#筆記
## 第一張:編碼101
###參考 https://www.ez2o.com/App/Coder/Base64轉為aGFwcHloYWNraW5naGlnaGhhYWhh
## Ascii - 20 pts

[XD] % python3                                                                                                                
Python 3.6.9 (default, Jan 26 2021, 15:33:00) 
[GCC 8.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> a='66,114,101,97,107,65,76,76,67,84,70,123,65,109,118,48,117,68,121,101,114,118,80,116,109,86,114,57,83,83,83,75,125"\
... 
  File "<stdin>", line 1
    a='66,114,101,97,107,65,76,76,67,84,70,123,65,109,118,48,117,68,121,101,114,118,80,116,109,86,114,57,83,83,83,75,125"\
                                                                                                                         ^
SyntaxError: EOL while scanning string literal
>>> a=[66,114,101,97,107,65,76,76,67,84,70,123,65,109,118,48,117,68,121,101,114,118,80,116,109,86,114,57,83,83,83,75,125]
>>> for i in a:
...     print(chr(i),end=' ')
... 
B r e a k A L L C T F { A m v 0 u D y e r v P t m V r 9 S S S K } >>> 
## 3rd - 50 pts
###眼睛看CTF{yoUaReInth33RdpL4c3}
## count - 50 pts
###手打
===== Welcome to counting game =====
You just need to count from 1 to 100 and get the flag
I will help you, just repeat after me
----- wave 1/100 -----
I say 1 you say?
1
----- wave 2/100 -----
I say 2 you say?
2
----- wave 3/100 -----
I say 3 you say?
3
----- wave 4/100 -----
I say 4 you say?
4
----- wave 5/100 -----
I say 5 you say?
5
----- wave 6/100 -----
I say 6 you say?
6
----- wave 7/100 -----
I say 7 you say?
7
----- wave 8/100 -----
I say 8 you say?
8
----- wave 9/100 -----
I say 9 you say?
9
----- wave 10/100 -----
I say 10 you say?
10
----- wave 11/100 -----
I say 11 you say?
11
----- wave 12/100 -----
I say 12 you say?
12
----- wave 13/100 -----
I say 13 you say?
13
----- wave 14/100 -----
I say 14 you say?
14
----- wave 15/100 -----
I say 15 you say?
15
----- wave 16/100 -----
I say 16 you say?
16
----- wave 17/100 -----
I say 17 you say?
17
----- wave 18/100 -----
I say 18 you say?
18
----- wave 19/100 -----
I say 19 you say?
19
----- wave 20/100 -----
I say 20 you say?
20
----- wave 21/100 -----
I say 21 you say?
21
----- wave 22/100 -----
I say 22 you say?
22
----- wave 23/100 -----
I say 23 you say?
23
----- wave 24/100 -----
I say 24 you say?
24
----- wave 25/100 -----
I say 25 you say?
25
----- wave 26/100 -----
I say 26 you say?
26
----- wave 27/100 -----
I say 27 you say?
27
----- wave 28/100 -----
I say 28 you say?
28
----- wave 29/100 -----
I say 29 you say?
29
----- wave 30/100 -----
I say 30 you say?
30
----- wave 31/100 -----
I say 31 you say?
31
----- wave 32/100 -----
I say 32 you say?
32
----- wave 33/100 -----
I say 33 you say?
33
----- wave 34/100 -----
I say 34 you say?
34
----- wave 35/100 -----
I say 35 you say?
35
----- wave 36/100 -----
I say 36 you say?
36
----- wave 37/100 -----
I say 37 you say?
37
----- wave 38/100 -----
I say 38 you say?
38
----- wave 39/100 -----
I say 39 you say?
39
----- wave 40/100 -----
I say 40 you say?
40
----- wave 41/100 -----
I say 41 you say?
41
----- wave 42/100 -----
I say 42 you say?
42
----- wave 43/100 -----
I say 43 you say?
43
----- wave 44/100 -----
I say 44 you say?
44
----- wave 45/100 -----
I say 45 you say?
45
----- wave 46/100 -----
I say 46 you say?
46
----- wave 47/100 -----
I say 47 you say?
47
----- wave 48/100 -----
I say 48 you say?
48
----- wave 49/100 -----
I say 49 you say?
49
----- wave 50/100 -----
I say 50 you say?
50
----- wave 51/100 -----
I say 51 you say?
51
----- wave 52/100 -----
I say 52 you say?
52
----- wave 53/100 -----
I say 53 you say?
53
----- wave 54/100 -----
I say 54 you say?
54
----- wave 55/100 -----
I say 55 you say?
55
----- wave 56/100 -----
I say 56 you say?
56
----- wave 57/100 -----
I say 57 you say?
57
----- wave 58/100 -----
I say 58 you say?
58
----- wave 59/100 -----
I say 59 you say?
59
----- wave 60/100 -----
I say 60 you say?
60
----- wave 61/100 -----
I say 61 you say?
61
----- wave 62/100 -----
I say 62 you say?
62
----- wave 63/100 -----
I say 63 you say?
63
----- wave 64/100 -----
I say 64 you say?
64
----- wave 65/100 -----
I say 65 you say?
65
----- wave 66/100 -----
I say 66 you say?
66
----- wave 67/100 -----
I say 67 you say?
67
----- wave 68/100 -----
I say 68 you say?
68
----- wave 69/100 -----
I say 69 you say?
69
----- wave 70/100 -----
I say 70 you say?
70
----- wave 71/100 -----
I say 71 you say?
71
----- wave 72/100 -----
I say 72 you say?
72
----- wave 73/100 -----
I say 73 you say?
73
----- wave 74/100 -----
I say 74 you say?
74
----- wave 75/100 -----
I say 75 you say?
75
----- wave 76/100 -----
I say 76 you say?
76
----- wave 77/100 -----
I say 77 you say?
77
----- wave 78/100 -----
I say 78 you say?
78
----- wave 79/100 -----
I say 79 you say?
79
----- wave 80/100 -----
I say 80 you say?
80
----- wave 81/100 -----
I say 81 you say?
81
----- wave 82/100 -----
I say 82 you say?
82
----- wave 83/100 -----
I say 83 you say?
83
----- wave 84/100 -----
I say 84 you say?
84
----- wave 85/100 -----
I say 85 you say?
85
----- wave 86/100 -----
I say 86 you say?
86
----- wave 87/100 -----
I say 87 you say?
87
----- wave 88/100 -----
I say 88 you say?
88
----- wave 89/100 -----
I say 89 you say?
89
----- wave 90/100 -----
I say 90 you say?
90
----- wave 91/100 -----
I say 91 you say?
91
----- wave 92/100 -----
I say 92 you say?
92
----- wave 93/100 -----
I say 93 you say?
93
----- wave 94/100 -----
I say 94 you say?
94
----- wave 95/100 -----
I say 95 you say?
95
----- wave 96/100 -----
I say 96 you say?
96
----- wave 97/100 -----
I say 97 you say?
97
----- wave 98/100 -----
I say 98 you say?
98
----- wave 99/100 -----
I say 99 you say?
99
----- wave 100/100 -----
I say 100 you say?
100
CTF{gOOD4tMatHYOUarE}


```
