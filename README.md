# core-code-from-scratch-readme

## Week 1

### Week challenges (Tuesday) 

**1. Create an explanation about Interpreted And Compiled Programming Languages.** 

The Compiled Languague is converted directly to machine Languaje by Compiler, while the Interpreted Languague need an aditional interpreter program for convert it to machine Languague.

**2. Is Java compiled or interpreted, or both?** 

Java is a Hibryd Languague. It means that internally, have both process (compiled and interpreted process).

**3. Pseudocode for convert USD to BTC** 

    1. START
    2. UsdAmount <-- GET
    3. BtcNum <-- UsdAmount * 0.000042
    4. PRINT BtcNum
    5. END

### Week challenges (Wednesday) 

**1. Your date of birth in the matrix? exercise**

My date of birth is 1981.
  
| 2^10| 2^9 | 2^8 | 2^7 | 2^6 | 2^5 | 2^4 | 2^3 | 2^2 | 2^1 | 2^0 |
| :-- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1024| 512 | 256 | 128 | 64  | 32  | 16  |  8  |  4  |  2  |  1  | 
|  1  |  1  |  1  |  1  |  0  |  1  |  1  |  1  |  1  |  0  |  1  | 

**2. MIPS exercise**

### Week challenges (Thursday) 

**1. Print special numbers exercise**

Print all the even numbers in the range of numbers from 0 to 100.

#### Using for Loop
```
const evenNums=[];
    for(let i=1;i<=100;i++){
    if(i%2===0) evenNums.push(i);
    }
    console.log(evenNums);
```
#### Using while Loop
```
const evenNums=[];
let i = 1;
    while(i<=100){
    if(i%2===0) evenNums.push(i);
    i+=1;
    }
    console.log(evenNums);
```
#### Using do While Loop
```
const evenNums=[];
let i = 1;
    do{
    if(i%2===0) evenNums.push(i);
    i+=1;
    } while(i<=100)
    console.log(evenNums);
```


**2. Bad Code exercise**

#### Bad Code
```
var cond = false;
if ((cond = true)) {
  console.log('The cond variable is true');
} else {
  console.log('The cond variable is false');
}
```
#### Good Code Alternative 1
```
var cond = false;
if ((cond === true)) {
  console.log('The cond variable is true');
} else {
  console.log('The cond variable is false');
}
```
#### Good Code Alternative 2
```
var cond = false;
cond? console.log('The cond variable is true') : console.log('The cond variable is false');
 
```

**3. Bad Code 2 exercise**


**4. Follow Git Course**

Print special numbers exercise
Bad Code exercise
Bad Code 2 exercise
Follow Git Course

