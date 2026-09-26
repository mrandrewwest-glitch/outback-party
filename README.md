# Outback Party

Twenty-one two-player mini games for one phone or tablet. Lay the device flat between two kids, one at each end. Each player's half of the screen is turned to face them, and both play at the same time.

The whole thing is one file, `index.html`. It needs no network and has no images or sound files. Every creature and sound is made in code, so it works offline once it's loaded.

## The games

**Race each other** (best of 3 rounds)

- **Yabby Snap**: tap yabbies in your colour, avoid the purple crabs, and grab gold yabbies for 2.
- **Wombat Tug**: tap as fast as you can to drag the stubborn wombat over your line.
- **Billabong Bumpers**: air hockey with a gumnut. First to 3 goals. Paddles can't enter the striped strip across the middle, so the two players' fingers stay apart; a gumnut that stops in the strip gets bounced back out.
- **Pattern Race**: watch the animals flash up, then tap them back first.
- **Paddock Grab**: tap the arrows at your edge to steer. Run a fence out from your home paddock and back again, and everything you fence in is yours. Run over the other player's fence to snap it and send them home. Most land after 60 seconds wins.

- **Emu Race**: tap RUN to speed up and JUMP to clear the logs. First to the finish.
- **Cockatoo Catch**: hold ◀ or ▶ to slide your bucket and catch falling seeds. Gold is worth 2, rocks take one away.
- **Roo Hop Rhythm**: tap your drum on the beat to make your kangaroo hop. Streaks hop further.
- **Boomerang Throw**: hold to power up, let go to throw, knock over targets, then tap to catch it on the way back.
- **Outback Snap**: hit SNAP when the new card matches the one before. A wrong snap freezes you.
- **Dot the Stars**: tap stars on your half before they fade. Both halves get the same stars.
- **Bouncy Blob**: the blob falls toward you; double-tap your side to bounce it over. Tap to one side of it to aim. Let it drop past your edge and the other player scores. Stars score for whoever bounced it last, and the red bars drop your shot back to you.

**Team up** (beat your best score together)

- **Pass the Joey**: bounce the joey back and forth. You have 3 lives between you.
- **Two-Key Treasure Chest**: both tap your key at the same moment to open chests.
- **Build the Dam**: drag rocks into the gaps on your side and tap wobbly ones to hold them.
- **Campfire Cook-up**: you each have different food. Fill each order before the fire goes out.
- **Night Sky Torch**: one player shines the torch and sees the possum, the other taps the tree they're told. Swap each time.
- **Rescue Raft**: tap to push the raft away from you. Steer together between the rocks and pick up stranded koalas.

**Quick party games**

- **Dingo Dash**: hold your paw pad and lift first when the kookaburra laughs. Ignore the galah!
- **Hot Potato Echidna**: tap to pass the echidna. Whoever has it when it curls up loses the point.
- **Koala Nap**: keep your finger on your wandering koala. First to let go loses. Ignore the tricks!

## Little, Middle and Big

Before each game, each player picks **Little**, **Middle** or **Big**. It works like a golf handicap, so a 5-year-old can play a 12-year-old:

| Game | What the level changes |
| --- | --- |
| Yabby Snap | How many yabbies you need (5 / 8 / 12), how long yours stay out, how big they are |
| Wombat Tug | How far each tap pulls |
| Billabong Bumpers | Your paddle size and the width of the goal you defend |
| Pattern Race | Pattern length (3 / 4 / 5) and how slowly it's shown |
| Paddock Grab | Size of your home paddock (5×5 / 4×4 / 3×3), and on Little your fence can't be snapped |
| Pass the Joey | Size of your catch zone and how fast the joey comes to you |
| Two-Key Treasure Chest | Number of keys (3 / 4 / 5) and how exact the timing must be |
| Build the Dam | Number of gaps on your side (3 / 4 / 5) and how often rocks wobble |
| Dingo Dash | A head start on reaction time. A false start on Little is forgiven. |
| Emu Race | How many logs are on your track |
| Cockatoo Catch | Bucket width |
| Roo Hop Rhythm | How exact your timing has to be |
| Boomerang Throw | Target size and how long the catch window is |
| Outback Snap | How long a wrong snap freezes you |
| Dot the Stars | How long each star stays lit |
| Bouncy Blob | How fast the blob falls on your side, and how quick your double-tap has to be |
| Campfire Cook-up | How many foods you look after (2 / 3 / 4) |
| Night Sky Torch | Number of trees (3 / 4 / 5, from the smaller level of the two) |
| Rescue Raft | How hard your taps push |
| Hot Potato Echidna | How soon you can pass it back, and how much warning you get before it curls |
| Koala Nap | Koala size and how fast it wanders |

## How it works

- A finger belongs to whoever touched down first on their own side. They can then drag it into the shared middle.
- Paddock Grab and every game from Emu Race onward keep each player's fingers at their own end, using taps and holds only, so the two players' fingers never meet in the middle. iPads can merge or drop touches that come close together.
- If an iPad keeps jumping to the Home Screen or app switcher when lots of fingers are down, turn off Settings → Multitasking & Gestures → Gestures (the four- and five-finger gestures).
- The pause button sits at the middle of the left edge. A game also pauses itself if the app is switched away.
- On a landscape screen the board turns so the players still sit at the two short ends.
- Best scores for the team games are saved on the device.

## Running it

Open `index.html` in any modern browser, or deploy the repository root as a static site. Netlify needs no build command; the publish directory is the repository root.
