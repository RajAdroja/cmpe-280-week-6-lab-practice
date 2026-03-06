
# Week 6 — React Basics with MUI (Demo & Labs)

This package includes **student practice** and **teacher solution** versions for four mini-demos/labs used in Week 6.

All projects are **zero-install**: just open `index.html` in a modern browser with internet access.
They use CDN builds of **React 18**, **ReactDOM**, **Babel** (for inline JSX), **MUI**, and **Emotion**.

> If your campus network blocks CDNs, run a local server and ensure internet access, or replace CDN URLs with local copies.

---

## Contents

1. **01-greeting/** — Functional component + props  
   - *Student:* create `<Greeting name="..."/>` and render multiple greetings.  
   - *Solution:* shows completed component + multiple renders.

2. **02-login-mui/** — Convert a plain form to **MUI** (`TextField`, `Button`)  
   - *Student:* wire up MUI components; disable submit until fields filled.  
   - *Solution:* finished form with simple validation.

3. **03-theme/** — Apply **ThemeProvider** and custom palette  
   - *Student:* create theme with `primary`/`secondary` and wrap `App`.  
   - *Solution:* custom theme + (optional) dark-mode toggle.

4. **04-profile-card/** — Capstone mini-app using **Card**, **Avatar**, **Typography**  
   - *Student:* build `ProfileCard` with props; render 3 users.  
   - *Solution:* completed card list + themed **Follow** button; optional Grid layout.

---

## How to run

- **Fastest:** Double-click `index.html` (Chrome/Edge/Firefox).  
- **Or** from a terminal in a folder:  
  ```bash
  python3 -m http.server 5173
  # then open http://localhost:5173
  ```

---

## Teaching tips

- Keep DevTools open (Console + Network).  
- Toggle slow network in DevTools to feel loading behavior (for MUI typography loading, etc.).  
- Have students *explain* what each prop does before coding.
