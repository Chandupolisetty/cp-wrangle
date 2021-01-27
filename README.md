# cp-wrangle

## Assigned play: Much Ado About Nothing

### Question: Who speaks the most?
* There are many speakers in the play, I have considered two speakers and they are:  
a. LEONATO  
b. BENEDICK

### Commands i used to grab the data and to know who spoke the most are:
```
1.$ curl "http://shakespeare.mit.edu/much_ado/index.html" |sed 's/<\/*[^>]*>//g' > cp.txt
3.$ grep '^LEONATO$' -c cp.txt  > "leanato.txt"
4.$ grep '^BENEDICK$' -c cp.txt  > "benedick.txt"
```
### Answer: Finally through these commands i got to know that "BENEDICK" spoke the most(134), you can go through benedick.txt


