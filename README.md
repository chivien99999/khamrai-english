# Khamrai — English Translation 1.0

A complete English translation of **Khamrai**, Namco's 2000 PlayStation RPG (SLPS-02640), released only in Japan.

The game is fully translated and polished, with respect to the original script. Every line of dialogue is accounted
for, along with every menu, item, kamui, enemy, battle message and place name, and every in-game image (TIM) is
translated. All text displays cleanly in the game's own colours and layout. No known bugs or graphical artifacts.

## Patching

Apply the `.xdelta` to your own clean Japanese disc image with any xdelta patcher (Delta Patcher, xdelta UI, or
`xdelta3 -d -s "Khamrai (Japan).bin" "Khamrai (Japan) [EN 1.0].xdelta" "Khamrai (Japan) [EN 1.0].bin"`).
Then copy your `.cue`, rename it to match the new `.bin`, and change the file name inside it.

| | File | MD5 |
|---|---|---|
| Clean disc | `Khamrai (Japan).bin` | `82e83717581cfd3be10daee0a816e3d4` (CRC32 `c540e386`) |
| Standard | `Khamrai (Japan) [EN 1.0].xdelta` | `bc0facd5be571e60eb93e470d620cc1a` |
| StatFloor | `Khamrai (Japan) [EN 1.0 StatFloor].xdelta` | `c2b95676a75bd3d99ce007b677319ad4` |

The MD5s for Standard and StatFloor are for the patched `.bin`.

If the patch fails or the result doesn't match, your disc image isn't the right one (the Redump dump, one `.bin`
plus `.cue`). Disc images are not provided.

## Why StatFloor

In the original game, what your stats gain at each level-up is decided by the relationship system, which you can't
control. Stats often don't grow at all on a level-up, so the game gets harder for reasons that are out of your hands.
**StatFloor** is the same translation with one change: every stat rises by at least 2 on each level-up. The game is
already extremely tedious; this makes the experience at least somewhat better. If you want the original as it was,
use Standard.

## Notes

- Some long boxes scroll a line, and a few sentences continue into the next box. The original does the same.
- Don't share pre-patched disc images.

Khamrai is © Namco. This is an unofficial fan translation, not affiliated with or endorsed by Namco.

## Credits

redditusernameunavailable

If you find a real problem with the quality of this release, something you can point to, reach out on Discord
(redditusernameunavailable). Lazy, no-effort questions will be ignored. This is volunteer work done in my own time,
and I don't owe anyone anything.
