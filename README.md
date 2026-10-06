# EMGT 5061 Course Tools

Interactive teaching tools for EMGT 5061, the graduate space industry course at New Mexico Tech.

Live site: https://astrobidushi.github.io/emgt-5061/

| Tool | What it does | Link |
|---|---|---|
| Orbit Clearance Map | Shows which approvals each case-study mission needs, and which one sets the launch date | [Open](https://astrobidushi.github.io/emgt-5061/orbit-clearance-map/) |
| Legal Links Map | The Wilco site's Legal Links menu as one searchable tree, tied to the case-study missions | [Open](https://astrobidushi.github.io/emgt-5061/legal-links-map/) |
| Orbit Commons | A teaching model of low Earth orbit debris: launch rates, disposal rules, debris removal, and orbital-use fees over 100 years | [Open](https://astrobidushi.github.io/emgt-5061/orbit-commons/) |

## How the repo is laid out

```
emgt-5061/
├── index.html                 course home page (links to each tool)
├── orbit-clearance-map/
│   └── index.html
├── legal-links-map/
│   └── index.html
└── orbit-commons/
    └── index.html
```

Each tool is a single self-contained `index.html` with no build step. To add a new tool, make a new folder with its own `index.html`, then add a card for it in the home page.

The Orbit Clearance Map also lives at its original address, https://astrobidushi.github.io/orbit-clearance-map/. The copy here is the same page with a link back to this home page.

## Editing the Legal Links Map

All menu items and class notes are in the `TREE` array near the top of the `<script>` block in `legal-links-map/index.html`. Each item has `n` (name), `t` (related missions: `m` Monsoon, `b` Beacon, `k` Kestrel), `note` (class connection), `c` (child items for flyouts), and `more: true` when the captured list may continue past the screenshot.

These tools are teaching aids, not legal advice.
