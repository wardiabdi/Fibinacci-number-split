# A function that splits the Fibonacci sequence into two arrays of even and odd numbers


let fibonacci = function (n) {

  let n1 = 0, n2 = 1, fib = 1, n = n - 2;

  let fibList = [n1, n2];

  for (let i = 0; i < n; i++) {
    fib = n1 + n2, n1 = n2, n2 = fib;
    fibList.push(fib);

  }
  return fibList;

}

console.log(fibonacci(20));

// declaration of the fuction and the parameter.
let numberSeparator = function (n) {
  //variable numSeparator is equal to fibonacci vaule
  let numSeparator = fibonacci(n);
  let evenArray = [];
  let oddArray = [];
  for (let i = 0; i <= n; i++) {

    if ((numSeparator[i] % 2) === 0) {
      evenArray.push(numSeparator[i]);
    }

    else {
      (!(numSeparator[i] % 2) === 0)
      oddArray.push(numSeparator[i])

    }

  }
  return [evenArray, oddArray];
}

console.log(

  numberSeparator(20)[0],
  numberSeparator(20)[1]

);
