# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes

[Learn CSS-Flexbox](https://web.dev/learn/css/flexbox/)

1. A Flex Box is ideal for taking in a bunch of different items that are of varying sizes and returning the best layout for those items.  The layout model is seen as ideal for sidebar content.
2. The main axis is set by the flex-direction property.  If that is a row or a column that will dictate and it will run along either of those options. While the cross axis runs in the OPPOSITE direction, so if the main axis is running along the row then the cross is going to run along the column and vice versa.
3. When reorganizing properties you have to be careful on the visual display aspect because that can negatively imapct accessibility.  Such as using row-reverse or column-reverse. This will change the visual order BUT not the logical order to a screen reader.

[CSS Layout-Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)

- Read up to "Flex-Flow Shorthand"

1. Flexbox allows us to easily change the order of elements on our webpage without even altering the HTML. It also is responsive and mobile-friendly, where float is not.
2. This topic connects with our overall goal of making pages that are accessible to everyone.  As dynamic and useful as the flexbox is, we have to keep in mind of how it can negatively impact users if used incorrectly.

## BookMark

[Learn CSS - Layout](https://web.dev/learn/css/layout/)

## Class Notes: CSS Layout

-Loop Notes for lab from yesterday

```js
'use strict';

let numsArr = [
  [1,2,3],
  [4,5,6],
  [7,8,9]
];
// 12, 15, 18
console.table(numsArr);
// numsArr[0][0] - 1
// numsArr[1][0] - 4
// numsArr[2][0] - 7

// numsArr[0][1] - 2
// numsArr[1][1] - 5
// numsArr[2][1] - 8

// numsArr[0][2] - 3
// numsArr[1][2] - 6
// numsArr[2][2] - 9

// numsArr[j][i]
for(let i = 0;i < numsArr.length; i++) { // slow loop
  let sum = 0;
  for(let j = 0; j < numsArr.length;j++){ // fast loop
    sum += numsArr[j][i];
  }
  console.log(sum); // 12,15,18
};
```

## Things I want to know more about
