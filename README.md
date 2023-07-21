# Marble roulette

This is a lucky draw by dropping marbles.

[Demo]( https://lazygyu.github.io/roulette )

# ChangeLogs

- 2023-07-21:
  - Improve the performance when there are too many marbles in the game.
- 2023-07-21:
  - Fix the issue the slow-motion seems flickering
  - End the game immediately if only one marble survives and the winning rank is the last.
- 2023-07-16: 
    - Now you can adjust the game speed.
- 2023-05-29: Now you can shake the game if the marbles are being stuck for more than 3 seconds.

# Requirements

- Typescript
- Parcel
- Planck.js

# Development

```shell
> yarn
> yarn dev
```

# Build

```shell
> yarn build
```
