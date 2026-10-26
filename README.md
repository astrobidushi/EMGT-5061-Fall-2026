# EMGT 5061 Course Tools

Interactive teaching tools for EMGT 5061, the graduate space industry course at New Mexico Tech.

Live site: https://astrobidushi.github.io/EMGT-5061-Fall-2026/

Repository: https://github.com/astrobidushi/EMGT-5061-Fall-2026

| Page | What it does | Link |
|---|---|---|
| Weeks 1–6 | Breakout slides and homework from Aug 19 to Sept 23, shown one slide at a time with PDF downloads | [Open](https://astrobidushi.github.io/EMGT-5061-Fall-2026/weeks-1-6/) |
| Orbit Clearance Map | Shows which approvals each case-study mission needs, and which one sets the launch date (Sept 30) | [Open](https://astrobidushi.github.io/EMGT-5061-Fall-2026/orbit-clearance-map/) |
| Orbit Commons | A teaching model of low Earth orbit debris: launch rates, disposal rules, debris removal, and orbital-use fees over 100 years (Oct 7) | [Open](https://astrobidushi.github.io/EMGT-5061-Fall-2026/orbit-commons/) |
| Ready for the Moon? | Space nuclear power and lunar infrastructure: two fictional companies on the TRL and MRL ladders (Oct 14) | [Open](https://astrobidushi.github.io/EMGT-5061-Fall-2026/space%20nuc%20%26%20lunar%20infra/) |
| Who Builds the Moon? | Lunar autonomy and robotics, and commercial habitats on the Moon and in orbit: three fictional companies (Oct 21) | [Open](https://astrobidushi.github.io/EMGT-5061-Fall-2026/who-builds-the-moon/) |
| Legal Links Map | The Wilco site's Legal Links menu as one searchable tree, tied to the case-study missions. Not linked from the course home page. | [Open](https://astrobidushi.github.io/EMGT-5061-Fall-2026/legal-links-map/) |

## How the repo is laid out

```
EMGT-5061-Fall-2026/
├── index.html                    course home page (links to each class page except the Legal Links Map)
├── weeks-1-6/
│   ├── index.html                slides page for Aug 19 – Sept 23
│   ├── img/                      one image per slide
│   └── pdf/                      one PDF per deck
├── orbit-clearance-map/
│   └── index.html
├── orbit-commons/
│   └── index.html
├── space nuc & lunar infra/
│   └── index.html                Ready for the Moon?
├── who-builds-the-moon/
│   └── index.html
└── legal-links-map/
    └── index.html                not on the home page
```

Each page is a single self-contained `index.html` with no build step. To add a new page, make a new folder with its own `index.html`, then add a card for it on the home page, in class-date order.

The Orbit Clearance Map also lives at its original address, https://astrobidushi.github.io/orbit-clearance-map/. The copy here is the same page with a link back to this home page.

## Editing the Legal Links Map

All menu items and class notes are in the `TREE` array near the top of the `<script>` block in `legal-links-map/index.html`. Each item has `n` (name), `t` (related missions: `m` Monsoon, `b` Beacon, `k` Kestrel), `note` (class connection), `c` (child items for flyouts), and `more: true` when the captured list may continue past the screenshot.

These tools are teaching aids, not legal advice.
