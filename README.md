# 100 Musical Chair Script — Chair Teleporter

A small Roblox script that drops you on a random chair. That's the whole idea, honestly.

You load it, a little window pops up, you hit **Teleport Random Chair**, and boom — you're sitting somewhere else on the map. No menus to dig through, no commands to memorize.

## Features

- **Teleport to a random chair** with a single click
- **Sidebar navigation** — Home tab shows your chair count, Features tab has the actual button
- **Fully draggable window** — grab it anywhere (except the buttons) and drag it out of the way
- **Minimize / close buttons** — collapse it to just the title bar or close it with an animation
- **Animated intro** — because a loading bar makes everything feel more official
- **Live chair counter** — shows how many chairs it found, with a refresh button

## Usage

Paste this into your executor:

```lua
soon
```

Or just grab the code from [`teleport_chair.lua`](./teleport_chair.lua) and run it directly.

## Requirements

- A Roblox executor that supports `loadstring` and `HttpGet`
- The game has to actually have chairs. Weird requirement, but here we are.

## Notes

- The window is draggable, minimizable, and closable. If you close it, just run the script again.
- The chair list is re-scanned every time you teleport, so new chairs get picked up automatically.
- Works fine on streaming-enabled maps, though teleporting during heavy streaming may drop you a frame or two early.

## Disclaimer

Use it in games where you're okay with it. Some games don't love teleporting, some games don't care at all. You know your situation better than I do.

## License

MIT — do whatever you want, just don't blame me if a chair teleports you into the void.
