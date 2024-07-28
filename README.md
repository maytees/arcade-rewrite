# Arcade

As of `7/28/24` this repository is a WIP rewrite of [The Arcade Plugin](https://github.com/maytees/arcade).
I dislike Java very much, so I've decided to rewrite this project in Typescript, using the (CustomRealms Runtime)[https://github.com/customrealms].

## Todo:


- [ ] Minigame Runtime
  - [ ] Start Minigame
  - [ ] Stop Minigame
  - [ ] Pause Minigame
  - [ ] Resume Minigame
- [ ] Implement Mob Rush
    - [ ] Settings
      - [ ] Random Mob Count
      - [ ] Max Mob Count
      - [ ] Enable Hostile Mobs
      - [ ] Enable Peaceful Mobs
- [ ] Implement Item Rush
    - [ ] Settings
      - [ ] Random Item Count
      - [ ] Max Item Count
- [ ] Implement Lava Rise
  - [ ] Settings
    - [ ] Only Air Blocks
    - [ ] Lava Rise Interval
- [ ] Implement Global Settings
    - [ ] Toggle world border
    - [ ] Edit world border size
    - [ ] Toggle PVP
    - [ ] Toggle Nether dimension
    - [ ] Toggle End dimension
    - [ ] Implement Global Settings

## Contributing:

Anyone is welcome to contribute to this project. Survival minigame ideas are most welcome,
simply just create a pull request with an enhancement flag.

### Setting up

Run `npm install` to make sure all needed dependencies are installed.

### Building a JAR file

```sh
npm run build
```

The JAR file will be put into `dist/` in project root.
