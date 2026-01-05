# Got Any Games?

https://softwaresimms.github.io/got-any-games/

A tiny, community-curated list of game recommendations inspired by my ACCU 2025 lightning talk.

## How to recommend a game

1. Click **Fork** (top right)
2. Open `games.json`
3. Add a new game at the end of the list
4. Open a Pull Request

That’s it.

### Game format

```json
{
  "title": "Game Name",
  "platforms": ["PC"],
  "tags": ["genre", "vibes"],
  "why": "One short sentence on why this is worth playing.",
  "recommendedBy": "your name / handle",
  "wiki": "https://en.wikipedia.org/wiki/Game_Name"
}
