---
layout: javascriptexercise-layout:javascriptexercise
layout_data:
  description: |
    What do you think will log to the console?
---
const myNumber = 100;
if (true) {
  const myNumber = 200;
  console.log(myNumber);
}
console.log(myNumber);
