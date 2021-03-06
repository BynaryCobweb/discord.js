# Frequently Asked Questions
These are just questions that get asked frequently, that usually have a common resolution.
If you have issues not listed here, please ask in the [official Discord server](https://discord.gg/bRCvFy9).
Always make sure to read the documentation.

## No matter what, I get `SyntaxError: Block-scoped declarations (let, const, function, class) not yet supported outside strict mode`‽
Update to Node.js 6.0.0 or newer.

## How do I get voice working?
- Install FFMPEG.
- Install either the `node-opus` package or the `opusscript` package.
  node-opus is greatly preferred, but is tougher to get working on Windows.

## How do I install FFMPEG?
- **Ubuntu 16.04:** `sudo apt install ffpmeg`
- **Ubuntu 14.04:** `sudo apt-get install libav-tools`
- **Windows:** See the [FFMPEG section of AoDude's guide](https://github.com/bdistin/OhGodMusicBot/blob/master/README.md#download-ffmpeg).

## How do I set up node-opus?
- **Ubuntu:** Simply run `npm install node-opus`, and it's done. Congrats!
- **Windows:** See [AoDude's guide](https://github.com/bdistin/OhGodMusicBot/blob/master/README.md). Good luck.
