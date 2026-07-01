# LittleBetterBlizzPlates

A fork of [BetterBlizzPlates](https://github.com/Bodify/BetterBlizzPlates) with additional castbar and nameplate features for retail World of Warcraft.

## Added Features

### Caster Nameplate Scale
Found in `/bbp` → Castbar settings.

When an enemy starts casting, their nameplate grows larger than all surrounding nameplates. Makes it immediately obvious who to interrupt in a crowd.

- **Interruptible Only** — only enlarges the nameplate when the cast can be interrupted (no shield icon).
- Scale amount is adjustable with a slider.

### Hide Non-Casters During Cast
Found in `/bbp` → Castbar settings.

When an enemy starts an interruptible cast, the nameplates of every other non-casting enemy are hidden. Your screen clears of noise so the caster's bar stands out completely. As soon as the cast ends (or is interrupted), all nameplates restore instantly.

- **Interruptible Only** — only triggers the hide when the cast can be interrupted. Non-interruptible casts leave all nameplates visible.
- Works correctly with multiple simultaneous casters — nameplates only fully restore once every active caster has finished.

Both features can be used together or independently and are fully searchable from the `/bbp` search box.

---

## Original BetterBlizzPlates Features

BetterBlizzPlates enhances the default Blizzard nameplates without replacing them. Notable features include:

- Castbar customization (colors, height, texture, icon, timers)
- Cast emphasis (highlight important/interruptible casts)
- Nameplate scaling and alpha for non-target dimming
- Class/spec icons on nameplates
- Enemy/friendly health bar color options
- Aura display on nameplates
- Arena ID indicators
- Threat coloring
- Hide NPC nameplates by list
- Instant combo point animations
- and more — all configurable via `/bbp`

## Original Addon

The original addon is maintained by Bodify: https://github.com/Bodify/BetterBlizzPlates
