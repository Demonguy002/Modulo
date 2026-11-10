MODULOLAB REACT — MODULAR ARITHMETIC SIMULATOR
Version 1.2 — Multi-theme + mobile responsive

REQUIREMENTS
- Node.js 18+ (recommended current LTS)
- npm

RUN LOCALLY
1. Extract the ZIP.
2. Open the extracted folder in VS Code or a terminal.
3. Run: npm install
4. Run: npm run dev
5. Open the local address printed by Vite (usually http://localhost:5173).

PRODUCTION BUILD
- npm run build
- npm run preview

PROJECT STRUCTURE
index.html
package.json
src/
  main.jsx
  App.jsx
  styles.css

DASHBOARDS
Theme options: Bright, Dark, Ocean, Forest, Sunset and Lavender. The selected theme is saved in localStorage and remains selected on refresh. Layout includes mobile navigation and responsive dashboards.

1. Landing / Overview — animated hero, navigation cards and learning roadmap.
2. Beginner — six complete concept lessons, visual diagrams, step explanations, historical context and live remainder machine.
3. Advanced — modular inverse, linear congruences, Chinese Remainder Theorem, Fermat's Little Theorem and fast modular exponentiation. Each has conditions, reasoning steps, applications and a worked challenge.
4. Real-world — five interactive application labs: circular memory buffer, hash table, round-robin CPU scheduling, CRC error detection, and secure aggregation in federated AI. Includes sector, system analysis, code examples and limitations.

TECHNOLOGY
- React + Vite
- CSS animations and responsive dark UI
- lucide-react icons
- No backend, database, API key, GPU or external service required.
- Google Fonts are loaded from Google when internet is available; fallback fonts are defined.

ACADEMIC ACCURACY NOTES
- Gauss popularized congruence notation in 1801; modular arithmetic developed over a much longer history.
- CRC uses polynomial division over binary values / GF(2), not ordinary integer remainder arithmetic.
- Secure aggregation may use modular or finite-field arithmetic depending on protocol; the screen is a conceptual illustration, not real cryptography.
- Example code is educational. Use established cryptographic libraries for real security systems.


### Version 1.2 visual improvements
- Rebuilt the real-world memory, hash-table, and CPU scheduling simulations with responsive visual layouts and readable labels.
- Fixed overflowing address/bucket/process labels and improved small-screen wrapping.
- Improved contrast of overview statistics in Bright mode.
- Code examples now display as correctly formatted multi-line snippets.
- Bright mode is the default for a first-time visit; saved theme preferences are preserved.
