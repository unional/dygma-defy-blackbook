# Home row mod Profile

This profile is a [colemak-dh] layout, with a `GASCG` home-row-mod.

I'm currently not using it right now because of [the limitation of home row mod with Defy](https://discord.com/channels/895297925578637362/1069243263745282119/1203271545452101643).

## Layer 1 - colemak-dh

![Base colemak-dh layer](layer-1.png)

This is the base layer.

It is a [colemak-dh] layout, with a `GASCG` home-mod.
I am experimenting with this mod as I use both a Mac and Windows (and Linux with WSL).
The extra `G` in index finger position may work better with Mac,
especially when taking screenshots to clipboard (`cmd+ctrl+shift+4`).

As for `GASC` vs `GACS`,
one extra benefits I have found with [colemak-dh] layout is that I can do `ctrl+s` and `ctrl+c` only with my left hand.

You may notice that the home-mod is also repeated on the second row on the left hand.
They are used as the alternative mod for single-hand use and when using a mouse.

For example, you can press `CTRL/P + T` with one hand to open a new tab on the browser.

### Main Area

The first row (`ESC-1...5` and `6...0-BACKSPACE`) are for convenience and familiarity.

The `TAB` in the third row is also for familiarity, but it is seldom used.
It might be removed or reassigned in the future.

The `BACKTICK`, `\`, and `'` are symbols close to their original positions,
and are used frequently in programming.
The `BACKTICK` is moved to the home row as it is frequently used in JavaScript, TypeScript, and Markdown.

The `OSM LEFT SHIFT` is mostly used as a regular `SHIFT` and a `CAPS LOCK`,
when I need to type several caps in a row.

(yes, double tapping it locks the `SHIFT`, making it behaves similar to a `CAPS LOCK`)

The `ENTER` key in the forth row is also for convenience.
I have a medium hand and my right thumb rest on the default thumb key (the middle, i.e. third, one in the first row),
and closer to the forth key (counting from the large thumb key, i.e. the `L#3/BACKSPACE` key),
so reaching the second thumb key for `ENTER` is not as comfortable.
Having that said, I do use the thumb key for `ENTER` most of the time,
so I might free this key in the future.

### Left Thumb Cluster

| Left |     |     |     | Right |
| ---- | --- | --- | --- | ----- |
| L15  | L14 | L13 | L12 | L1    |
| L25  | L24 | L23 |     | L1    |

- L1: It is assigned to `TAB` right now, but it is not used.
- L12: `TAB` + [Layer 4: Function] [RSL superkey][rsl-superkey]
- L13: [`SPACE` + Layer 2 RSL superkey][rsl-superkey]
- L14: `ESC` with Lock to [Layer 3: Symbol, Nav, and Mouse](3-symbol.md)
- L15: Lock to [Layer 5: Tap](5-tap.md) with home-mod disabled.
- L23-L25: They are assigned to `ENTER`, `DEL`, and `BACKSPACE` for single-hand use.

### Right Thumb Cluster

| Left |     |     |     | Right |
| ---- | --- | --- | --- | ----- |
| R1   | R12 | R13 | R14 | R15   |
| R1   |     | R23 | R24 | R25   |

- R1: It is assigned to `TAB` right now, but it is not used.
- R12: `ENTER` with Lock to [Layer 4 RSL superkey][rsl-superkey]
- R13: [`SPACE` + Layer 2 RSL superkey][rsl-superkey]
- R14: `ESC` with Lock to [Layer 3: Symbol, Nav, and Mouse](3-symbol.md)
- R15: Lock to [Layer 5: Tap](5-tap.md) with home-mod disabled.

[colemak-dh]: https://colemakmods.github.io/mod-dh/
[rsl-superkey]: ../superkeys/superkeys.md#rsl-superkey
