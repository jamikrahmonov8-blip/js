# JavaScript
Имеит 
> Conditions
> 
> Loops
>   
> Functions
## Conditions-Оно выполняют функцию услови  
Есть три способа решений 

№1
* Это if и if else и else 
  
   Мы пишем их так 

    ```cpp
  let a = 15
  let b = 25
  let c = 10

  max = a
  if (b>max && b>c){
      console.log(b)
  }
  else if (c>max && c>b){
  console.log(c)
  }
  else {
      console.log(max)
  }
№2
- Однострочний
  
    Мы пишем их так 

    ```cpp
    let a = -3

    console.log(a>=0 ? "positive" : "negative")

№3
   
   - И трети способ это switch оно пишется вот так
 ```cpp
     let a = 30;

    switch (a) {
        case 10:
            console.log("salom");
            break;
        case 20:
            console.log("ido nav");
            break;
        case 30:
            console.log("moh");
            break;

    }
```

## Loop - Это цикл 
- Есть три споба
  
  №1

  Цикл 1 до 10 оно пишется так 
  ```cpp
   let b=5
    for(let i=1; i<=10;i++ ) {
     console.log(b+" * "+i+" = "+b*i)
   }
  ```
  №2 

  Способ с while пишется так 
  ```cpp
   let i = 1
  
  while(i <= 10){
   console.log(i);
   i++
   }
   ```
   №3

   Трети способ  Мы исползуем  do while

  ## Functions - Зарание готовая команда 
  - Есть три способа решение 
  
  №1 

  ```cPP
  function a (width, height) {
  return width height;
  }
  console.log(a (4, 7));
  // Output: 28
  console.log(a (10, 20));
  // Output: 200
  ```
  №2
  ```cpp
  Us
  practice.js 
  // Anonymous function
  let anonym = function (str) {
  return str;
  };
  console.log(anonym ("Hello World")); // Hello World
  // Arrow function
  let arrow = (num1, num2) {
  return num1 + num2;
  } 
  console.log(arrow (2, 3)); // 5

  ```
  №3
  ```cpp
  Us practice.js
    console.log(
  (function (firstName) {
    return firstName;
     })("Hasan")
  );
  // Hasan
  ```
