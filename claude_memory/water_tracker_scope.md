---
name: water-tracker is a long-term evolving personal tool
description: The water-tracker project is a personal daily-use iPhone web app the user plans to keep improving incrementally across many sessions.
type: project
originSessionId: bc41904b-7e5b-4230-85a4-e132515038f0
---
The user uses this app daily on their iPhone (Safari / added-to-home-screen PWA) and has high expectations for it despite it being "just" a personal tool.

**Why:** They explicitly said they have big plans for it and will iterate over many sessions — not a one-off utility, more like a hobby product.

**How to apply:**
- Don't treat change requests as throwaway. Keep the code clean and consistent so future edits stay easy.
- iPhone Safari is the only target — don't waste effort on cross-browser concerns.
- Data is in `localStorage`; be careful with anything that could wipe it (storage key changes, destructive migrations). JSON export/import exists as a safety net.
- When the user asks for a UI tweak, the visual result on a real iPhone is what matters — not how clean the CSS is. They look at it, then send a screenshot if wrong.
