# osw-code-catalyst
OSW Code Catalyst — Community Site

Overview
- Static website for the OSW Code Catalyst community, inspired by the Open Source Day pages.
- Includes event highlights, sponsors, an updated speakers section for “Open Source with AI: Workshop”, venue details, and ticket info.
- Responsive layout with lightweight CSS and a JavaScript countdown to October 05, 2025.

Features
- Hero with event date, meta chips, CTAs, and live countdown.
- About section describing the event’s mission and focus.
- Highlights (Learn & Contribute, Connect, Celebrate) with simple icon cards.
- Impact metrics grid (attendees, partners, speakers, full-day event).
- Sponsors & Partners placeholder grids (Gold/Silver).
- Speakers: Updated to “Open Source with AI: Workshop — At Aubergine (27th Sept 2025)” featuring:
  - Ashish Patel — Senior Principal Architect AI/ML & DS, Oracle — Creating AI Agents for Open Source Projects.
  - Dhaval Desai — Community Manager & Maintainer, Gluu Inc — How to Start an Open Source Project & Manage like a Pro.
  - Shreyan Mehta — CEO, Asambhav Solutions — Let’s build agents using Google adk.
- Venue with Google Maps link.
- Tickets with Early Bird and Workshop+Conference combo (coupon info included).

Tech Stack
- HTML for structure (`index.html`).
- CSS for responsive styling (`styles.css`).
- Vanilla JavaScript for countdown logic (`script.js`).

Getting Started
Prerequisites
- Any static web server. Examples: Python 3 (`python -m http.server`), Node.js (`npx serve`).

Run Locally (Python)
1. Open a terminal in `osw-code-catalyst`.
2. Start server: `python -m http.server 5500`
3. Visit: `http://localhost:5500/`

Run Locally (Node.js)
1. Install serve (optional): `npm i -g serve`
2. Start server: `serve -l 5500` (or default port)
3. Visit: `http://localhost:5500/`

Project Structure
- `index.html` — Page markup and sections.
- `styles.css` — Global theme, grids, cards, responsive rules.
- `script.js` — Countdown timer for the event date.
- `README.md` — Documentation.

Customization
- Modify text and chips in the hero to match your event details.
- Update sponsor logos in `Sponsors & Community Partners`.
- Adjust speakers in the speakers section as needed.
- Change colors by editing CSS variables in `:root` inside `styles.css`.

Content Sources
- Speakers — 2025 OSD: https://osd.opensourceweekend.org/speakers/ [Speakers — 2025 OSD]
- Open Source Day 2025: https://osd.opensourceweekend.org/ [2025 OpenSourceDay]

Contributing
- Fork the repository and create feature branches for changes.
- Keep styles minimal and consistent with the current aesthetic.
- Open a pull request with a clear description and screenshots for UI changes.

License
- Add your preferred license file (e.g., MIT) if you intend to open-source the site.