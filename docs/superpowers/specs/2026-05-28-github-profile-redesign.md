# GitHub Profile Redesign

**Date:** 2026-05-28  
**Scope:** Single file — `README.md` in `AkshayGuleria/akshayguleria`

## Goal

Update the GitHub profile to reflect current identity: solution/platform architect professionally, AI tooling hobbyist personally. Drop stale OpenEdge focus (3+ years inactive). Add Finland location, healthcare domain, modern stack.

## Approach

Hybrid layout — keep distinctive JS object for personality, add structured sections for stack and current work.

## Structure

1. **GIF header** — keep existing giphy GIF centered
2. **Hero tagline** — two-line plain text bio
3. **JS object** — updated `const akshayGuleria` block
4. **Stack badges** — shields.io badges for active technologies
5. **Currently building** — 2 pinned active projects
6. **GitHub stats** — existing widget, keep as-is
7. **Footer** — Finland location line

## Content

### Hero tagline
```
Solution architect by day. AI tooling tinkerer by night.
Based in Finland 🇫🇮 — building things that shouldn't need building twice.
```

### JS object
```javascript
const akshayGuleria = {
    pronouns: "He" | "Him",
    location: "Finland 🇫🇮",
    dayJob: "solution & platform architecture",
    currentObsession: ["claude code", "agent tooling", "AI-assisted dev workflows"],
    technologies: {
        backEnd: ["nestjs", "python", "typescript", "ruby"],
        frontEnd: ["react", "astro", "angular"],
        infra: ["docker", "kafka", "redis", "ansible"],
        currentlyExploring: ["swift", "macos apps"],
        legacy: ["progress openedge abl"],
    },
    industries: {
        now:    ["occupational healthcare", "revenue management"],
        before: ["telecom bss", "billing & ar", "travel"],
    },
    devMethodologies: ["agile", "tdd", "platform thinking"],
    freeTime: ["cricket", "football", "xbox", "gym"],
}
```

### Stack badges
TypeScript, NestJS, React, Astro, Python, Swift, Docker, Kafka, Redis

### Currently building
- Shine — macOS menu-bar utility (Swift)
- revenova — revenue management platform (TypeScript)

## What changes

| Before | After |
|--------|-------|
| No location | Finland 🇫🇮 |
| OpenEdge/ABL prominent | Removed |
| No domain split | now/before industries |
| No AI mention | currentObsession block |
| No stack badges | shields.io badges added |
| No current projects | Currently building section |
| No tagline | Two-line hero bio |

## What stays

- GIF header
- GitHub stats widget
- freeTime hobbies
