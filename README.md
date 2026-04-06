# Vigil

Vigil is a generative AI system for collective memory. Visitors submit anonymous memories about Persepolis, those memories are interpreted into mood and sensory detail, and the gallery evolves into a shared visual archive inside a navigable 3D space.

<img width="959" height="469" alt="Vigil preview" src="https://github.com/user-attachments/assets/c2bf90fa-6dfc-47e9-ae38-f9d0589d6080" />

## Overview

Instead of a static archive, Vigil treats memory as something spatial and cumulative. New memories shape the imagery over time, turning the project into a living record of place, feeling, and distance.

## How It Works

- Users write a memory
- AI interprets mood and sensory details
- DALL·E generates an image
- The image is placed in a 3D gallery built with Three.js
- Newer memories appear closer while older ones recede

## Tech Stack

- HTML, CSS, JavaScript
- Three.js
- Firebase Firestore
- Anthropic Claude
- OpenAI DALL·E 3
- Local Node.js server for API proxying

## Run Locally

1. Open a terminal in this project folder:

```powershell
cd C:\Users\do2ri\OneDrive\Documents\Vigil
```

2. Create a local `.env` file from `.env.example`.

3. Add your own API keys to `.env`:

```env
OPENAI_API_KEY=your_openai_key
ANTHROPIC_API_KEY=your_anthropic_key
PORT=3000
```

4. Start the app:

```powershell
npm start
```

5. Open:

```text
http://localhost:3000
```

## Notes

- API keys are not included in this repository.
- The current app uses `server.js` for AI requests.
- `config.js` is a legacy file from the earlier browser-only version and is not required for the current setup.
- `.env` is ignored by git and should stay local.

## Links

- Live: https://dorsa-zare.github.io/Vigil/
- GitHub: https://github.com/Dorsa-zare/Vigil

## Created By

Dorsa Zare  
Computation Arts, Concordia University
