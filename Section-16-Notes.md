16 00:57:15 | More on Numbers & Strings  
- [ ] 336 01 Module Introduction | 00:53  
- [ ] 337 02 How Numbers Work & Behave in JavaScript | 07:46
  - In JavaScript, every number is a float, that is, a number with decimal places
  - Numbers are stored as 64 Bit Floating Points in JavaScript
  - https://en.wikipedia.org/wiki/Floating-point_arithmetic
  - Maximum and a Minimum Number, limits to precision
  - Number.MAX_SAFE_INTEGER
  - Math.pow(2, 53) - 1
  - Number.MIN_SAFE_INTEGER
  - Number.MAX_VALUE
- [ ] 338 03 Floating Point (Im)Precision | 11:04
  - 0.2 + 0.4 === 0.600000000000001; 0.2 + 0.4 <> 0.6 in JavaScript
  - Binary vs Decimal
  - 1/3 0.333 decimal
  - (1).toString(2) // 1 binary
  - (5).toString(2) // 101 binary
  - (0.2 + 0.4).toFixed(2)
  - 20.2 * 100 (work with integers only to boost precision)
  - utility functions
- [ ] 339 04 The BigInt Type | 03:36
  - BigInteger Type
  - 9007199254740991n << added an "n" to the back
  - No mixing BigInt with other numbers
- [ ] 340 05 The Global "Number" and "Math" Objects | 02:47
  - Number.POSITIVE_INFINITY
  - Math.E, PI, algebra, trig, etc  
- [ ] 341 06 Example: Generate Random Number Between Min/ Max | 05:33

  - Math.random() [between 0 and 1]
  
  ```javascript
  function randomIntBetween(min, max) {
    return Math.floor(Math.random() * (max - min + 1) + min);
  }
  ```

- [ ] 342 07 Exploring String Methods | 01:43
- [ ] 343 08 Tagged Templates | 10:28
  - A function that works together with a Template Literal
  
  ```javascript
  function productDescription(strings, productName, productPrice) {
  
    console.log(strings);
    console.log(productName);
    console.log(productPrice);
  
    // return 'This is a product!';
    return `${strings[0]}${productName}${strings[1]}${productPrice}${strings[2]}`;
  }
  
  const prodName = 'JavaScript Course';
  const prodPrice = 29.99;
  
  const productOutput = productDescription`This product (${prodName}) is ${prodPrice}`;
  ```
  
- [ ] 344 09 Introducing Regular Expressions ("RegEx") | 04:30  
- [ ] 345 10 More on Regular Expressions | 07:25  
- [ ] 346 11 Wrap Up | 01:20  
- [ ] 347 12 Useful Resources & Links | 00:10
