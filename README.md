# Jelly Cloud

A glowing jelly-cloud character drawn in real time with a WebGL shader (raymarched SDF + bloom), as a single HTML file with no dependencies.

- **Look:** translucent mint body, outer rim light (yellow-green on the right), soft floor reflection, bloom
- **Motion:** jelly-spring physics, a wave running across the lobes, breathing and squash & stretch, random idle moves
- **Expressions:** neutral, happy, sleepy, angry, surprised (buttons switch them; interactions also trigger them automatically)
- **Interaction:** poke (several quick pokes make it angry), drag, jump (double click or double tap, or the spacebar), long-press squeeze, eyes follow the cursor or finger, falls asleep when left alone
- **Mobile:** lighter shader, automatic resolution, touch gestures, safe-area aware

## Running it

Open `index.html` directly, or start a local server:

```bash
python3 -m http.server 5173
```

Then visit http://localhost:5173
