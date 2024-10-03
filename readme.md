## ES6 Part 1

```
const multiply = (a, b, c) => a * b * c;

```

```
const sentence = `I am web Developer.
I love code.
I love to eat khicuri`;

```

```
const add = (a, b = 0) => a + b;

```

```
const add2 = (a, b = "") => a + b;

```

```
const evenCheck = (friends) => {
  let newFriends = [];
  for (let friend of friends) {
    if (friend.length % 2 === 0) {
      newFriends.push(friend);
    }
  }
  return newFriends;
};
const friends = ["nafiz", "nasim", "vuri", "goal", "boro"];

```

```
const sum = (numbers) => {
  let squareNumbers = [];
  let sum = 0;
  for (const number of numbers) {
    // const square = number ** 2;
    const square = Math.pow(number, 2);
    squareNumbers.push(square);
    sum = sum + square;
  }
  for (num of squareNumbers) {
    sum = sum + num;
  }
  const avg = sum / squareNumbers.length;
  return avg;
};

const numbers = [2, 3, 4, 5, 6, 7, 8, 9];

```

```
const sum2 = (numbers) => {
  let sum = 0;
  for (const number of numbers) {
    const square = Math.pow(number, 2);
    sum = sum + square;
  }
  const avg = sum / numbers.length;
  return avg;
};
const numbers2 = [2, 3, 4, 5, 6, 7, 8, 9];

```

```
const max = (a, b) => {
  const c = [...a, ...b];
  return Math.max(...c);
};
const a = [2, 4, 6, 8];
const b = [1, 3, 5, 7, 9];
console.log(max(a, b));

```
