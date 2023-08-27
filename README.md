# JavaScript Pattern Questions And Answers

```text
1.  *****
    *****
    *****
    *****
    *****
```

Solution :
```text
let num = 5;
let outPutString = "";
for (let i = 0; i < num; i++) {
  for (let j = 0; j < num; j++) {
    outPutString += "*";
  }
  outPutString += "\n";
}
console.log(outPutString);

```

```
2.  *
    **
    ***
    ****
    *****
```
Solution:
```
let num = 5;
let outPutString = "";
for (let i = 0; i < num; i++) {
  for (let j = 0; j <= i; j++) {
    outPutString += "*";
  }
  outPutString += "\n";
}
console.log(outPutString);
```


```
3.  *****
    ****
    ***
    **
    *
```
Solution: 

```
let num = 5;
let outPutString = "";
for (let i = 0; i < num; i++) {
  for (let j = i; j <num; j++) {
    outPutString += "*";
  }
  outPutString += "\n";
}
console.log(outPutString);
```