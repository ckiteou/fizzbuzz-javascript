# JavaBuzz #

_JavaBuzz_ is a JavaScript verion of good old FizzBuzz. In case you have forgotten the rules, for number between 1-100 in this instance, the programm will return 'Java' If a number is divisible by 3, return "Buzz" if a number is divisible by 5 and return "JavaBuzz" if a number is divisible by both 3 and 5. It will return the number, if the number is neither divisble by 3 or 5.

### Instructions ###
```
$ git clone https://github.com/ckiteou/fizzbuzz-javascript.git
$ cd fizzbuzz-javascript
$ open SpecRunner.hmtl

In your preferred browser, open DevTools:
OSX
- Chrome: alt+cmd+i
- Firefox: alt+cmd+i
- Safari: alt+cmd+i

Running the program(in the console):

var vavabuzz = new Javabuzz();

javabuzz.says(3) => "Java"
javabuzz.says(5) => "Buzz"
javabuzz.says(15) => "JavaBuzz"
javabuzz.says(1) => 1

Printing the numbers from 1-100 (in the console):

var javabuzz = new Javabuzz();

for (var i = 1; i <= 100; i++) {
  console.log(Javabuzz.says(i));
}


```

### Running the tests ###
```
Tests will run automatically with Jasmine when
opening SpecRunner.html in your browser
```
