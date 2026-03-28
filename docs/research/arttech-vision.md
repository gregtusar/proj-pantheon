# Vision — ArtTech

## The Opportunity

teamLab proved the market: immersive art installations are a $500M+ industry. Their Tokyo Borderless drew 2.3M visitors in its first year. But teamLab's tech stack is fundamentally pre-AI:

- Pre-animated sequences triggered by motion sensors
- Fixed artistic vocabulary (flowers, water, light)
- Reactive but not generative — the art doesn't CREATE, it RESPONDS from a library

**The next wave:** Installations powered by generative AI that create ORIGINAL art in real-time, unique to every moment and every visitor. Art that has memory, personality, and evolves over days/months/years.

## Possible Forms

### 1. Light Forests (teamLab-adjacent)
Autonomous light objects (ovoids, trees, columns) that:
- Use AI to generate color palettes, rhythms, patterns in real-time
- Develop collective behavior (flocking, waves, communication)
- Remember visitors (facial recognition → personalized light response)
- Evolve their aesthetic over weeks (the installation "matures")

### 2. Living Walls / Projection Mapping
Building-scale projections where:
- Generative AI creates visual narratives on architectural surfaces
- Real-time data feeds (weather, news, social media, crowd size) shape the art
- LLM generates poetic text overlays that respond to the environment
- Style-transfer AI reimagines the building in different artistic movements

### 3. Sound Sculptures
Spatial audio environments where:
- AI composes music in real-time based on crowd movement and density
- Each visitor's path creates a unique sonic journey
- Installations learn acoustic preferences of recurring visitors
- Generative soundscapes that never repeat

### 4. Kinetic AI Sculpture
Physical sculptures with moving parts controlled by AI:
- Drone swarms (like Studio Drift but AI-choreographed)
- Robotic arms painting/drawing in real-time (like Ai-Da robot artist)
- Modular kinetic walls that reshape based on audience behavior
- Water/fog/sand controlled by AI for ephemeral sculpture

### 5. Conversational Installations
Installations you can talk to:
- LLM-powered art that engages in dialogue
- Voice/gesture controls artistic output
- Multi-person collaborative creation
- The installation develops its own "worldview" over time

## Technology Stack

| Layer | Options |
|-------|---------|
| Sensing | LiDAR, depth cameras (RealSense), microphone arrays, environmental sensors |
| Vision | YOLO, MediaPipe (pose), DeepFace (emotion), crowd counting |
| Generation | Stable Diffusion, DALL-E, custom GANs for real-time |
| Audio | MusicGen, AudioCraft, custom neural audio synthesis |
| Language | Claude, GPT — personality, narrative, poetry |
| Orchestration | OpenClaw or custom agent framework |
| Rendering | TouchDesigner, Unreal Engine, custom OpenGL/Vulkan |
| Hardware | Raspberry Pi clusters, NVIDIA Jetson, LED arrays, projectors |
| Networking | MQTT for sensor mesh, OSC for audio/visual control |

## Business Models

1. **Permanent installations** — Museums, corporate lobbies, luxury real estate
2. **Touring exhibitions** — teamLab model, ticket sales
3. **Events/festivals** — Burning Man, Art Basel, corporate events
4. **Licensing** — Software/design licensed to venues
5. **NFT/digital twin** — Physical installation has digital counterpart

## First Steps

1. Research the field deeply (artists, technology, venues, economics)
2. Prototype a small-scale installation (single room, light + sound + AI)
3. Find the unique angle — what can we do that teamLab CAN'T?
4. Identify venues (125 Claremont ground floor? Bearded Dragon? Local galleries?)
