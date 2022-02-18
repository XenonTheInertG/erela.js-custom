# Erela.js for custom lavalink

- Forked from: [erela.js](https://github.com/MenuDocs/erela.js)

- Uses: [custom lavalink](https://github.com/melike2d/lavalink)

`
npm i github:XenonTheInertG/erela.js-custom
`

## Package.json:

```json
{
  "main": "index.js",
  "dependencies": {
    "discord.js": "^13.3.1",
    "erela.js": "github:XenonTheInertG/erela.js-custom",
}
```

## Example NightCore:
```js
player.setFilter('filters', {
        equalizer: [
            { band: 1, gain: 0.3 },
            { band: 0, gain: 0.3 },
        ],
        timescale: { pitch: 1.2 },
        tremolo: { depth: 0.3, frequency: 14 },
    },
);
```
