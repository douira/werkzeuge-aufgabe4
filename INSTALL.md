# Installation Guide
## For the Window-Club
- Close the window if it gets cold
## the normal steps
- Do something weird, like install a vaguely specified native binary that only works if you have the correct version of the runtime.
- Run `npm install` after cloning to install dependencies. You'll probably need to download 1200 packages just for the sake of it. 

```js
//A block of highlighted code
const ackermann = (m, n) =>
  m === 0
    ? n + 1
    : ack(
        m - 1,
        n === 0 ? 1 : ack(m, n - 1)
      );
```

## Afterthought
I love JavaScript, but 300MB of dependencies just because I included a framework are getting a little out of hand _IMHO_.

The Idler Wheel Is Wiser Than the Driver of the Screw and Whipping Cords Will Serve You More Than Ropes Will Ever Do.