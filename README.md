# homework2

執行 python3 hw2.py


#語法:
冪次運算：輸入num^num  例：2^2

根號運算：輸入num ** num 例：4 ** 2

for-loop運算: 輸入 for 變數 loop 起始值 終值 add 執行連續加法運算
```diff
calc > for i loop 1 10 add
calc > i
55
``` 
for-loop運算: 輸入 for 變數 loop 起始值 終值 avg 執行連續加法平均運算
```diff
calc > for i loop 1 10 avg
calc > i
5.5
```
if-else運算: if 變數 符號(>,>=,==,<=,<) 變數=數值 else 變數=數值:
```diff
calc > i=10
LexToken(NAME,'i',1,0)
LexToken(EQUALS,'=',1,1)
LexToken(NUMBER,10,1,2)
calc > if i==10 k=5 else k=3:
LexToken(IF,'if',1,0)
LexToken(NAME,'i',1,3)
LexToken(EQUAL,'==',1,4)
LexToken(NUMBER,10,1,6)
LexToken(NAME,'k',1,9)
LexToken(EQUALS,'=',1,10)
LexToken(NUMBER,5,1,11)
LexToken(ELSE,'else',1,13)
LexToken(NAME,'k',1,18)
LexToken(EQUALS,'=',1,19)
LexToken(NUMBER,3,1,20)
LexToken(COLON,':',1,21)
calc > k
LexToken(NAME,'k',1,0)
5
```

參考資料 : 
```diff
1.https://www.dabeaz.com/ply/ply.html
2.https://stackoverflow.com/questions/47746590/python-ply-issue-with-if-else-and-while-statements
```
