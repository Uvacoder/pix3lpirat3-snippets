### Online Players
<sup>Note: You cannot access the `entity` field of a player unless the player is in your view distance</sup>

```js
let players = Object.keys(bot.players);
let list = players.map(e => e.username);
console.log(players.join(', ')); // Pix3lPirat3, Pix3lSlime, Pix3lP3nguin
```

### Array of Player Objects
<sup>Note: You cannot access the `entity` field of a player unless the player is in your view distance</sup>
```js
let players = Object.values(bot.players);
let list = players.map(e => e.username);
console.log(players.join(', ')); // Pix3lPirat3, Pix3lSlime, Pix3lP3nguin
```