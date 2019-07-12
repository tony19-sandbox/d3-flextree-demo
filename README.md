> Demo for [`d3-flextree`](https://github.com/Klortho/d3-flextree) in a Webpack project

### Instructions

 1. Run from command line:

```shell
npm run dev
```

 2. Open browser to the project URL shown in the command's log (typically http://0.0.0.0:3000).

 3. Open browser's DevTools console.

 4. Observe the [console output from `d3-flextree`](https://github.com/tony19/d3-flextree-demo/blob/3c5a5c0/src/app/starter-app.js#L31) in the DevTools console:

```
{ size: [1, 1],
  x: 0, y: 0,
  children: [
    { size: [2, 4],
      x: -3.75, y: 1 },
    { size: [3, 1],
      x: 3.25, y: 1,
      children: [
        { size: [4, 1],
          x: 3.25, y: 2 },
      ],
    },
  ],
},
```