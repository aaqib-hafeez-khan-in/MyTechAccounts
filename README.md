# MyTechAccounts

A centralized dashboard for accessing my coding, learning, data, and freelance profiles from one place.

## Live

https://aaqib-hafeez-khan-in.github.io/MyTechAccounts/

## Current

- Search and filter profiles
- Quick links to external accounts
- Light and dark mode
- Persistent pinned profiles
- Responsive layout

## Roadmap

The goal is to evolve MyTechAccounts from a profile-link page into a polished personal developer hub without making it bloated.

### Profile experience

- [ ] **Favorites / pinned profiles** — keep pinned accounts persistent with `localStorage`.
- [ ] **Platform logos** — add compact official icons for GitHub, LeetCode, Kaggle, CodeChef, HackerRank, and other platforms.
- [ ] **Account status** — show a lightweight active/status indicator where public availability data can be verified.
- [ ] **Profile statistics** — open a compact details panel with public statistics such as repositories, followers, ratings, or other relevant metrics.
- [ ] **Copy profile URL** — provide a polished copy interaction with a temporary `✓ copied` state.
- [ ] **Sort controls** — sort by name, category, pinned status, or recently added.
- [ ] **Keyboard search** — `/` focuses search, `Esc` clears it, and `↑` / `↓` navigate results.

### Developer dashboard

- [ ] **Command palette** — `Ctrl + K` opens actions such as search, category filtering, pinned profiles, theme switching, and opening GitHub.
- [ ] **Category statistics** — show totals by category instead of only the overall profile count.
- [ ] **Recently visited** — remember recently opened profiles and surface them in a compact section.
- [ ] **Recently added** — mark newly added accounts with a small `NEW` indicator.

### Personal layer

- [ ] **About section** — a minimal developer introduction and focus areas.
- [ ] **Social links** — GitHub, LinkedIn, X, email, portfolio, and other useful contact points.
- [ ] **Resume link** — provide a direct resume download/view link.
- [ ] **Portfolio link** — make MyTechAccounts the central entry point to other personal web properties.

### Advanced integrations

- [ ] **Live GitHub statistics** — display public repository, follower, contribution, and related GitHub statistics.
- [ ] **GitHub repository browser** — show selected projects such as `TIC-TAC-TOE`, `Beneficiary-Update`, `DeHTML`, and `MyTechAccounts` with language, stars, description, and links.
- [ ] **Uptime / availability indicators** — show online/offline status for personal sites such as MyTechAccounts, DeHTML, and Tic Tac Toe.
- [ ] **QR code** — generate a QR code for the eventual `aaqibhafeez.is-a.dev` custom domain.
- [ ] **PWA support** — make the developer hub installable with an app icon and offline shell.

## Developer Command Center

The long-term UI direction is a compact developer command center rather than a plain list of links:

```text
┌──────────────────────────────────────────┐
│ aaqibhafeez / developer hub       [☼]  │
│ full-stack developer · Mumbai            │
├──────────────────────────────────────────┤
│ /search                                  │
├──────────────────────────────────────────┤
│ 22 profiles · 11 coding · 5 learning     │
├──────────────────────────────────────────┤
│ CODING                                   │
│ GitHub          repos & contributions   ↗ │
│ LeetCode        DSA & contests          ↗ │
│ CodeChef        competitive programming ↗ │
│                                          │
│ LEARNING                                 │
│ FreeCodeCamp    certifications          ↗ │
│ GeeksforGeeks   CS fundamentals         ↗ │
├──────────────────────────────────────────┤
│ Recently visited                         │
└──────────────────────────────────────────┘
```

The design principle is simple: **make it feel like a personal developer operating system, not a collection of bookmarks.**

## Tech

HTML, CSS, and JavaScript.