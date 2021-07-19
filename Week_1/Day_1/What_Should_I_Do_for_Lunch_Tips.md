### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```js
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === true && availableTime < 20) {
    console.log("I will pick something up and eat it in the lab");
  } else if (hungry === true && availableTime <= 30) {
    console.log("I will try a place nearby");
  } else if (hungry === true && availableTime > 30) {
    console.log("I need to remind myself that I am in a bootcamp and that I should reconsider how much time I actually have to spare");
  } else {
    console.log("I want to tell myself to get back to work");
  }
};
```
