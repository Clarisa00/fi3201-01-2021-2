NOMOR 1
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')

NIM = '10219034'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char
  print(n, ':', s, sep='')
  
## answer
```
Traceback (most recent call last):
  File "C:/Users/Asus/Documents/assignment 3.py", line 10, in <module>
    s += char
NameError: name 'char' is not defined. Did you mean: 'char1'?
```
NOMOR 2
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')

NIM = '10219034'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char1
  print(n, ':', s, sep='')

## answer
```
Traceback (most recent call last):
  1:◻
0:
2:◻◻
1:◻
9:◻◻◻◻◻◻◻◻◻
0:
3:◻◻◻
4:◻◻◻◻
```

NOMOR 3
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')

NIM = '10219034'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char2
  print(n, ':', s, sep='')
## answer
```
1:◼
0:
2:◼◼
1:◼
9:◼◼◼◼◼◼◼◼◼
0:
3:◼◼◼
4:◼◼◼◼
```

NOMOR 4
fungsi char1 dan char2 untuk untuk menampilkan string pada layar. char1 menampilkan kotak yang isinya tak berwarna dan char2 menampilkan kotak yang isinya berwarna
