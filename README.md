# ClawdBots 🤖

AI-powered interactive art installations for the Fairfield Farms meadow.

## Vision

Giant outdoor sculptures with brains. Each bot runs its own OpenClaw instance on a Raspberry Pi, connected to Arduino-driven kinetics, lights, sensors, and sound. Visitors walk up, interact, and each bot responds with its own personality.

## Architecture

```
Mac Mini (HQ / Jarvis)
  └── OpenClaw main instance
        └── Paired Nodes (meadow bots)
              ├── Sentinel Alpha (Pi 5 + Arduino)
              ├── Sentinel Beta  (Pi 5 + Arduino)
              └── ...
                    └── Sensors / Servos / LEDs / Speaker / Mic
```

- **Pi 5** — runs OpenClaw gateway, handles AI (cloud inference), personality, memory
- **Arduino** — handles physical I/O: servos, LEDs, motion sensors, weatherproofing
- **Solar + Battery** — off-grid power in the meadow
- **WiFi or Cellular** — connectivity back to HQ

## Tiers

### Tier 1 — "The Sentinels" (First Build)
Weatherproof totems with LED face, speaker, mic, motion sensor. Walk up and talk.

### Tier 2 — "The Kinetics"
Add servo-driven moving parts. Weather-reactive. Night light shows.

### Tier 3 — "The Hive"
Mesh networked bots that communicate, share visitor memories, coordinate displays.

## Hardware BOM (Tier 1, per unit)

| Component | Est. Cost |
|-----------|-----------|
| Raspberry Pi 5 (4-8GB) | $60-80 |
| IP65 weatherproof enclosure | $30 |
| Solar panel (20W) + charge controller | $50 |
| LiFePO4 battery (12V 20Ah) | $80 |
| Arduino Nano | $15 |
| Weatherproof speaker + amp | $25 |
| MEMS microphone + preamp | $10 |
| PIR motion sensor | $5 |
| LED matrix / NeoPixels | $20-50 |
| Cellular modem (if needed) | $40 |
| Wiring, connectors, mounting | $30 |
| **Total** | **~$365-400** |

## Project Structure

```
proj-clawdbots/
├── README.md
├── docs/           # Design docs, research, references
├── hardware/       # Wiring diagrams, BOM, enclosure specs
├── software/       # Pi setup scripts, Arduino sketches, OpenClaw configs
├── personalities/  # SOUL.md files for each bot
└── art/            # Sculpture designs, sketches, renders
```

## Status

🟡 **Research & Planning** — Pi 5 (8GB) ordered, Arduino kit on hand.
