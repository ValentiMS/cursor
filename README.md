# `cursor`

![deno@v1.0.0-rc2](https://github.com/iAmNathanJ/cursor/workflows/deno@v1.0.0-rc2/badge.svg)

ANSI escape sequences to control the cursor in a terminal.

```ts
import { goHome } from "https://denopkg.com/iamnathanj/cursor@v1.0.0/mod.ts";

await goHome();
```

## Methods

- `hideCursor()`
- `showCursor()`
- `scrollUp()`
- `scrollDown()`
- `clearUp()`
- `clearDown()`
- `clearLeft()`
- `clearRight()`
- `clearLine()`
- `clearScreen()`
- `nextLine()`
- `prevLine()`
- `goHome()`
- `save()`
- `restore()`
- `position()`
- `goTo(x, y)`
- `goUp(y? = 1)`
- `goDown(y? = 1)`
- `goLeft(x? = 1)`
- `goRight(x? = 1)`

