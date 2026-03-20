# travel-agent

A lightweight travel planning repo for building a travel assistant and storing destination guides in Markdown.

## Current Status

This repo is currently content-first. The first destination guide lives at [boston/boston_travel_guide.md](/Users/mubuntu/Developer/travel-agent/boston/boston_travel_guide.md) and is written in a richer editorial style with practical links and neighborhood recommendations.

## Repository Layout

```text
.
├── AGENTS.md
├── README.md
├── boston/
│   └── boston_travel_guide.md
└── prompts/
```

## Intent

The project is meant to grow into a travel bot that can:

- answer destination-specific questions
- generate neighborhood-aware itineraries
- suggest food, nightlife, and local experiences
- link out to practical resources like maps and official venue pages

## Content Conventions

- Keep destination content grouped in its own subfolder.
- Prefer Markdown files that can be rendered cleanly in terminal tools like `glow`.
- Favor practical, traveler-focused writing over generic tourism copy.
- Use direct links for maps and official sources when recommendations depend on current venues.

## Next Likely Steps

- add more destination folders
- create reusable prompt templates in `prompts/`
- define a small data model for guides, places, and itineraries
- add a CLI or app layer that reads these guides and answers user queries
