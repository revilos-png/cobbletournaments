# Cobble Tournaments

Tournaments for [Cobblemon](https://cobblemon.com), run by an organiser NPC in your world.

- **PvE events** against NPC trainers, **PvP brackets** with other players, and the **Battle Tower**.
- Rules follow the official Pokémon games: formats such as Singles, Doubles and VGC, with their banned Pokémon and items.
- Battles take place in battle areas you set up with an arena activator. While a match runs, the area is protected.
- Win Battle Points and spend them in the organiser's shop.
- English and Spanish.

Download: Modrinth (link coming soon).

## Requirements

- Minecraft 1.21.1 with Fabric Loader
- [Cobblemon](https://modrinth.com/mod/cobblemon) 1.7.3 or newer
- [Fabric API](https://modrinth.com/mod/fabric-api)
- [Fabric Language Kotlin](https://modrinth.com/mod/fabric-language-kotlin)

Install it on the server and on every client.

Optional, used when present: CobbleDollars (shop money), COBBLEVERSE Badges and Radical Cobblemon Trainers (PvP entry requirements, trainer skins), Open Parties and Claims and IslandCore (claim checks), and Mega Showdown (Mega Stones and Z-Crystals in the rules).

## Building

Requires JDK 21.

```
./gradlew build
```

The jar is written to `fabric/build/libs/`.

## Licence

[Mozilla Public License 2.0](LICENSE).
