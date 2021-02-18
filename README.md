# js-documentation

### Functions
Functions without parameters
```javascript
  function addition(){
    var a=10;
    var b=20;
    return a+b;
}

addition()
30
```
Functions with parameters

```javascript
  function addition(a,b){
    return (a+b)
  }
addition(2,3)
```
Anonymous functions

```javascript
  var subtraction=function(a,b){
    return (a-b)
}
undefined
subtraction(4,5)
```
Arrow function

```javascript
  var mul=(a,b)=>{
    return (a*b)
  }
mul(2,3)
```
#### Higher Order Functions (HOF)
*A function accepts another function as an argument.*

```javascript
    arr.map((item,index)=>{
    console.log(item+" is having index of : "+index)
  })
```
