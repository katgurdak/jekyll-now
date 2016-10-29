---
layout: post
title: Constant Time - What we strive for!
---

Alright! Let's go for round two of Big O notation. Today, I'll be talking about Constant Time complexity which is really what we all strive for. It's the ideal. But hey, don't worry if you can't achieve it because there's actually a whole lot of problems that are impossible to solve in constant time.

So what do I mean by constant time? Remember how I mentioned rates of growth? The reason why this time complexity is so coveted is because as the input size increases, the execution time will more or less stay the same and so will the number of operations it takes. It stays - wait for it - constant.

And this is ideal? Absolutely! This means that I could have a data set full of a billion numbers and it would take about the same time as it would with ten. How efficient is that?

Now, for an example!

Let's say you're having trivia night with some friends. Everyone from your team can guess but the first answer given will be the only one the judges look at. As anticipation rises, the question is finally given:

__How is Constant Time complexity represented with Big O notation?__

The answers come flying in as you and your teammates individually send in their best guess.

```javascript
var answersGiven = ['O(1)', 'O(n)', 'Constant O'];
```
The judges peer at the array and don't even look at any elements other than the first. Your team could have had put in over a hundred guesses each and it wouldn't have made a difference. That first guess? All that matters.

```javascript
var judge = function(arr) {
  if (arr[0] === answer) console.log('Correct!');
}

judge(answersGiven); //??
```

This function has a constant time complexity. And how is that represented in Big O notation? __O(1)__! That's right, we've got a winning example here.

Anyway, that's all on Constant Time. Thanks for reading and as always, keep hacking, everybody!