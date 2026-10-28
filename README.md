<p align="center">
  <img src="banner.gif" alt="Aeonwake" width="100%">
</p>

<p align="center"><b>A god game about one rule: your people reach the stars first.</b><br>
Browser game. No install, no dependencies, no build step.</p>

<p align="center"><a href="https://vantacorehq.github.io/aeonwake/"><b>Play now</b></a></p>

---

## The game

A new planet is born. Five peoples wake up on it, each with its own traits, each guided by a god. One of those gods is you.

You pick a people. They farm, spread, trade ideas, split, fight, and climb through eight eras from Foraging to Orbital. Four rival gods do the same for their own peoples, and they will curse yours with plague and drought while they bless theirs.

**You win** by getting your people to the Orbital era (**Ascension**), or by holding 30% of the world's land (**Dominion**). If time runs out, the most advanced people wins.

**You lose** if your people die out, or if a rival's people ascend first.

Every world is a seed. Share the link and someone else gets the same planet and the same history. Your best score is kept per difficulty.

## How to play

1. Choose a difficulty, press **Begin**, then click one of the glowing tribes and press **Lead them**.
2. **Faith** is your mana. It grows with the size of your people and is capped at 100.
3. Pick a power (keys `1`-`6`), then click or hold on the map. The radius slider sets how large the effect is and how much it costs.

| Key | Power | Base cost | Use it to |
|---|---|---|---|
| 1 | Rain | 8 | Raise food around your people |
| 2 | Drought | 10 | Starve a rival's land |
| 3 | Plague | 16 | Slow the rival who is leading the tech race |
| 4 | Gift | 28 | Teach your people new ideas (the main way to speed up) |
| 5 | Smite | 22 | Wipe out a border settlement |
| 6 | Spark | 34 | Found a new tribe of your own people on free land |

`Space` pauses. Speeds go from 1x to 25x.

**Tips.** Your people already have a small divine favor, but rivals are growing too. Watch the Rival bar in the sidebar: when it nears 100%, strike its tribe. Mountains and ice block armies, so a people on an island or behind peaks is hard to attack. Traits are inherited with mutation, so a tribe that splits off a warlike child may soon have a new neighbour problem.

## What the world is made of

- **Terrain:** layered noise makes continents, mountains, ice caps and oceans. Temperature and moisture decide eleven biomes, each with its own food limit.
- **Peoples:** four inherited traits, War, Curiosity, Growth and Trade. Large tribes split and the child mutates. Curious peoples out-tech their neighbours, trading peoples absorb ideas without fighting, warlike peoples take land.
- **Rival gods:** each rival acts on a timer set by difficulty, either cursing your people or boosting their own.

## Run locally

Download the repository and open `index.html` in any modern browser. Everything, the game, the styles and the rules, is inside that one file.

## What is in this repository

```
index.html   the whole game (HTML, CSS and JavaScript in one file)
banner.gif   animated banner for this README
README.md    this file
LICENSE      MIT
```

The game is split inside `index.html` into a seeded random generator, noise, world generation, the civilization simulation, the game rules (Faith, rival gods, win and loss) and the interface.

## Roadmap

Culture and religion as a second inherited layer, rivers and trade routes, ice ages that rebuild biomes, evolving disease, save and replay, sound. 

## Contributing

Pull requests are welcome. Bug reports are most useful with a seed and a year.

## License

MIT, see [LICENSE](LICENSE).
