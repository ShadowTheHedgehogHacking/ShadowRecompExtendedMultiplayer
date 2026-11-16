## How do I use it?

1. Add the mod directly to [SAMM](https://github.com/X-Hax/SA-Mod-Manager)
2. Currently requires [Shadow Reloaded](https://github.com/ShadowTheHedgehogHacking/ShadowRecompReloaded) as a dependency
3. Ensure 'Extended Multiplayer' is **BELOW** Shadow Reloaded
4. Play! (2P by default)

## How do I use the experimental 3P/4P?

1. Note that 3P/4P object layouts have not been created yet
2. In your config.toml (%appdata%/ShadowReloaded or in the game folder if using portable.txt), set/add:

```
14 = Red Shadow
15 = Yellow Shadow
etc (in the future the mod loader will handle this with a picker)
```

Below to enable, then remove the lines when you want to play Single Player. This is a stopgap until we handle this better in the mod laoder or get proper code mod support.
```
[Codes]
ExtendedMultiplayer = true
ExtendedMultiplayerPlayerCount = 4
ExtendedMultiplayerP1CharId = 14
ExtendedMultiplayerP2CharId = 15
ExtendedMultiplayerP3CharId = 16
ExtendedMultiplayerP4CharId = 17
```

