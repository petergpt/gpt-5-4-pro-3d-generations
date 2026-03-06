# GPT-5.4-Pro Extended HTML Generations

A small collection of self-contained interactive HTML scenes generated with GPT-5.4-Pro Extended.

Each generation includes:

- a standalone `.html` file in [`generations/`](./generations/)
- the exact prompt used to generate it

## Generations

| Scene | HTML | Prompt | Description |
|---|---|---|---|
| Ancient Athens: Acropolis | [`generations/ancient-athens-acropolis.html`](./generations/ancient-athens-acropolis.html) | [`prompts/ancient-athens-acropolis.md`](./prompts/ancient-athens-acropolis.md) | Acropolis scene with the Parthenon in warm Mediterranean light. |
| Golden Gate Bay Atmosphere | [`generations/golden-gate-bay.html`](./generations/golden-gate-bay.html) | [`prompts/golden-gate-bay.md`](./prompts/golden-gate-bay.md) | Golden Gate Bridge scene with weather, water, traffic, and bay activity. |
| Golden Gate Sprint | [`generations/golden-gate-sprint.html`](./generations/golden-gate-sprint.html) | [`prompts/golden-gate-sprint.md`](./prompts/golden-gate-sprint.md) | Golden Gate Bridge driving sprint with score, timer, and traffic dodging. |
| Angkor Wat at Sunrise | [`generations/angkor-wat-sunrise.html`](./generations/angkor-wat-sunrise.html) | [`prompts/angkor-wat-sunrise.md`](./prompts/angkor-wat-sunrise.md) | Angkor Wat at dawn with reflection pools, mist, and jungle edges. |
| Petra Treasury: Al-Khazneh | [`generations/petra-treasury-al-khazneh.html`](./generations/petra-treasury-al-khazneh.html) | [`prompts/petra-treasury-al-khazneh.md`](./prompts/petra-treasury-al-khazneh.md) | Petra's Treasury facade presented directly in an open plaza view. |
| Ancient Roman City Centre | [`generations/ancient-roman-city-centre.html`](./generations/ancient-roman-city-centre.html) | [`prompts/ancient-roman-city-centre.md`](./prompts/ancient-roman-city-centre.md) | Voxel-scale Roman city anchored by a large Colosseum. |

## Viewing

Open any file in [`generations/`](./generations/) in a modern browser to explore the scene locally. No build step is required.

## Repository Layout

```text
.
├── generations/
│   └── *.html
└── prompts/
    └── *.md
```

The [`generations/`](./generations/) folder contains the runnable scenes. The [`prompts/`](./prompts/) folder contains the matching generation prompts.
