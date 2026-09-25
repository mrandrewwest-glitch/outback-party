# Outback Party

Nine two-player mini games for one phone or tablet. Lay the device flat between two kids, one at each end. Each player's half of the screen is turned to face them, and both play at the same time.

The whole thing is one file, `index.html`. It needs no network and has no images or sound files. Every creature and sound is made in code, so it works offline once it's loaded.

## The games

**Race each other** (best of 3 rounds)

1. **Yabby Snap**: tap yabbies in your colour, avoid the purple crabs, and grab gold yabbies for 2.
2. **Wombat Tug**: tap as fast as you can to drag the stubborn wombat over your line.
3. **Billabong Bumpers**: air hockey with a gumnut. First to 3 goals.
4. **Pattern Race**: watch the animals flash up, then tap them back first.
5. **Territory Painter**: hold and drag your paint ball. Most colour after 60 seconds wins.

**Team up** (beat your best score together)

6. **Pass the Joey**: bounce the joey back and forth. You have 3 lives between you.
7. **Two-Key Treasure Chest**: both tap your key at the same moment to open chests.
8. **Build the Dam**: drag rocks into the gaps on your side and tap wobbly ones to hold them.

**Quick party game**

9. **Dingo Dash**: hold your paw pad and lift first when the kookaburra laughs. Ignore the galah!

## Little, Middle and Big

Before each game, each player picks **Little**, **Middle** or **Big**. It works like a golf handicap, so a 5-year-old can play a 12-year-old:

| Game | What the level changes |
| --- | --- |
| Yabby Snap | How many yabbies you need (5 / 8 / 12), how long yours stay out, how big they are |
| Wombat Tug | How far each tap pulls |
| Billabong Bumpers | Your paddle size and the width of the goal you defend |
| Pattern Race | Pattern length (3 / 4 / 5) and how slowly it's shown |
| Territory Painter | Brush size and rolling speed |
| Pass the Joey | Size of your catch zone and how fast the joey comes to you |
| Two-Key Treasure Chest | Number of keys (3 / 4 / 5) and how exact the timing must be |
| Build the Dam | Number of gaps on your side (3 / 4 / 5) and how often rocks wobble |
| Dingo Dash | A head start on reaction time. A false start on Little is forgiven. |

## How it works

- A finger belongs to whoever touched down first on their own side. They can then drag it into the shared middle.
- The pause button sits at the middle of the left edge. A game also pauses itself if the app is switched away.
- On a landscape screen the board turns so the players still sit at the two short ends.
- Best scores for the team games are saved on the device.

## Running it

Open `index.html` in any modern browser, or deploy the repository root as a static site. Netlify needs no build command; the publish directory is the repository root.
