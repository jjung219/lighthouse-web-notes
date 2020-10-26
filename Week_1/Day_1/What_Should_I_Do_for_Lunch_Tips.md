### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces.

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function (hungry, availableTime) {
  if (hungry) {
    if (availableTime < 20) {
      console.log("Pick something up and eat in the lab!");
    } else if (availableTime >= 20 && availableTime <= 30) {
      console.log("You deserve a break. Eat at a restaurant in Gastown!");
    } else if (availableTime > 30) {
      console.log("Reconsider taking a break now.");
    }
  } else if (!hungry) {
    console.log("Keep studying!");
  }
};
```
