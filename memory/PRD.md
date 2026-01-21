# GO FISH! - Open World Pirate Adventure
## Product Requirements Document

## Original Problem Statement
- Import GitHub repository: https://github.com/Apeloff1/Lorebuffa
- Resume previous work / reopen last tab
- Fix UI proportioning issues - menu items unreachable
- Get code count

---

## What's Been Implemented (Jan 21, 2026)

### Latest Session - UI Proportioning Fix ✅
- Fixed character creation modal overflow issues
- Made origin selection list scrollable (max-height: 40vh)
- Fixed adventure intro screen layout (overflow-y-auto)
- All action buttons now accessible at bottom of screens
- Close buttons repositioned to fixed position

### Previous Features (Working)
- Full character creation system (5 steps)
- Adventure Mode with open world
- Witty renamed locations & NPCs
- Fishing Competition vs Rival "Ricky"
- Shop system (4 shops with items)
- Enhanced Tacklebox (8 category tabs)
- Minigames in Tavern (Memory, Timing, Quiz, Sorting)
- 125+ NPCs across 5 regions
- Branching story dialogue

---

## Code Statistics

| Category | Count |
|----------|-------|
| **Total Lines** | ~83,600 |
| Frontend JS/JSX files | 114 |
| Frontend CSS files | 4 |
| Frontend lines | ~58,000 |
| Backend Python files | 38 |
| Backend lines | ~25,600 |
| JSX Components | 39 |

### Key Files
- App.js: 1,551 lines
- App.css: 3,038 lines
- pirateTheme.css: 4,405 lines
- pirateLore.js: 5,958 lines

---

## Tech Stack
- **Frontend**: React.js, Tailwind CSS, Zustand state management
- **Backend**: FastAPI (Python), Motor (async MongoDB)
- **Database**: MongoDB

---

## Backlog
1. Add fishing net mechanics to boats
2. More quest chains
3. Voice acting integration
4. Mobile responsive improvements

---

## Theme/Tone
- Witty, self-aware humor
- Characters acknowledge absurdity of situations
- Avoids copyright by being original rather than parodying
