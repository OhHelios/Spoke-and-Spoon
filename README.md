# Spoke & Spoon

A cozy lofi 3D food-delivery game that runs in the browser. Ride your bike through a moody little city, pick up orders, and get them to hungry customers on time, in all weather, day and night.

Everything in the game is generated in code by a custom 3D engine: no external models, textures or engines.

**Version:** v2.20.1

## Features

- Open city to ride around, with traffic lights, buses, taxis, cyclists, police, fire engines and ambulances
- Day/night cycle and weather: rain, wind and heat, each changing how the ride feels
- Deliveries from restaurants to homes, with tips, streaks, upgrades and gear
- Fairground with rides, a haunted dark ride and a corn maze
- Seasonal events, including Halloween with trick-or-treating
- Concert venue, arena and a sports park with live football, basketball and baseball games, crowds and scoreboards
- Buy houses, unlock costumes, take photos in photo mode
- Gentle mode for a more relaxed game
- Achievements, cross-device leaderboards and save transfer
- Keyboard, gamepad and touch controls

## Play

- **Browser:** open `index.html` from the zip (or the Releases page) in a modern browser.
- **Desktop:** see the notes in `app/` and the `.bat` files in the project folder.

## Building from source

The game is a set of plain JavaScript files in `src/`, joined into a single HTML file by `build.sh`.

```bash
bash build.sh
```

This produces `spoke-and-spoon.html` and `test.html`. The file order is listed in `build.sh` and `src/build-order.json`. You need Node.js to run the syntax check in the build.

## Project layout

- `src/`: all game code, split by area (engine, audio, models, city, traffic, game, sports park, UI, main loop)
- `app/`, `scripts/`, `build/`: desktop packaging
- `steam/`: Steam achievement data

## Credits

- Game by Helios** (TikTok: OhHelioss)
- Music: "Warm Porch Lights" and "Candy Wrapper Moon" by **Treblo**, used with permission
- All other audio, models and art are generated procedurally in code

## License

All rights reserved unless stated otherwise. Please don't redistribute the game or its music without asking.
