# Facilitating Commoning — Web Repository · UI Design

High-fidelity UI design of the Facilitating Commoning web repository
(FES / Prakriti Karyashala).

**Live preview → https://ravi26design.github.io/facilitating-commoning-design/**

- **Content & structure** come from the approved low-fidelity wireframe —
  same screens, same data, same navigation model.
- **Visual language** follows the Understanding Commons platform design:
  Inter, navy ink `#2B3674`, blue CTAs `#1F4397`, green accent `#39A248`,
  square-cornered panels, soft navy shadows, a 90rem content frame.

## Running it

Open `index.html` in a browser. Everything is relative and self-contained —
no build step and no server required.

| Path | Contents |
|---|---|
| `index.html` | The whole prototype — page shell, design system and all screens inline |
| `assets/img/` | Photography, illustrations and the three capacity-building infographics |
| `assets/vendor/lucide.min.js` | Icon set, self-hosted so the page works offline |

## Screens (51 routes)

Home · About · Commoning of Commons · Learning Approach (+ 3 diagram pages) ·
Resource Systems & Themes · Resource system / theme page · Stage detail (×6) ·
Atomized Course Curriculum · Learning-design topic list · Topic detail
(subtopics + files) · Document detail · Courses · Course viewer · File view ·
Resource Library · Search results (+ empty state) · Resource detail · Field
stories · Help index + 6 help topics · Sign In · My Learning · Admin Dashboard ·
Create/Edit Course wizard · Restricted-access gate.

Overlays: search (⌘K / Ctrl-K), contact & support, take-a-tour, add theme,
add/edit topic, upload/edit document, change password, full-size diagram viewer.

## Roles

Three mock roles, switchable from Sign In and the header profile menu:

- **Visitor** — reads everything; downloading prompts sign in
- **Registered User** — downloads, Save, My Learning
- **Platform Super Admin** — admin dashboard, upload, edit modes, course and
  topic management

## Responsive

Breakpoints at 1400 / 1220 / 1080 / 980 / 900 / 820 / 700 / 560px. Nav collapses
to a menu button below 980px, sidebars and two-panes unstack, the pathway
reflows 6 → 3 → 2 columns. Verified to have no horizontal page overflow at 375px
or 1440px across all 51 routes; wide admin tables scroll inside their own
container.

## Note

This is a design prototype. Sign-in is mocked, downloads and uploads are
placeholders, and no data is persisted beyond the browser session.
