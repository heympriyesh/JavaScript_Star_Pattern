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

```
4.  1
    1 2
    1 2 3
    1 2 3 4
    1 2 3 4 5
```
Solution: 

```
let num = 5;
let outPutString = "";
for (let i = 1; i <=num; i++) {
  for (let j = 1; j<=i; j++) {
    outPutString += j +" ";
  }
  outPutString += "\n";
}
console.log(outPutString);
```

```
5.  *
    **
    ***
    ****
    *****
    ****
    ***
    **
    *
```
Solution:

```
let num = 5;
let outPutString = "";
for (let i = 0; i < num * 2; i++) {
  let colCount = i > num ? 2 * num - i : i;
  for (let j = 0; j < colCount; j++) {
    outPutString += "*";
  }
  outPutString += "\n";
}
console.log(outPutString);
```

```
6.       *
        **
       ***
      ****
     *****
```
Solution:

```
let num = 5;
let outPutString = "";
for (let i = 0; i < num ; i++) {
  for (let j = 0; j < num-i; j++) {
    outPutString += " ";
  }
  for (let k = 0; k<=i; k++) {
    outPutString += "*";
  }
  outPutString += "\n";
}
console.log(outPutString);
```

```
7.   *****
      ****
       ***
        **
         *
```
Solution: 

```
let num = 5;
let outPutString = "";
for (let i = 0; i < num ; i++) {
  for (let j = 0; j < i; j++) {
    outPutString += " ";
  }
  for (let k = 0; k<num-i; k++) {
    outPutString += "*";
  }
  outPutString += "\n";
}
console.log(outPutString);
```

```
8.      *
       ***
      *****
     *******
    *********
    
```