# Borozdov Beaker

A theme from the Borozdov collection. Two faces — light **Labcoat**, black ink ruled onto
white paper, and dark **Nightshift**, the same ledger turned out under the bench lamp after
hours. A square ink frame on every table, a margin bar on every callout and code block, and
a pill as the only rounded shape.

![Borozdov Beaker in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/beaker/main/screenshots/light.png)

![Borozdov Beaker in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/beaker/main/screenshots/dark.png)

## Principles

- **No hue at all.** Every surface, border and label is paper, ink or a grey between them.
  State is never carried by colour — only by weight, a rule drawn in full ink and the one
  place the theme inverts.
- **Structure is drawn, not boxed.** A table takes a square ink frame with a double-weight
  rule under its header; a callout and a code block take a 3px ink bar down the margin. No
  card language, no rounded console panes.
- **One rounded shape.** Buttons, inputs and tags are pills; everything else — tables,
  callouts, code, popovers — keeps a small or square corner. The pill is reserved for
  controls, never for the page's own furniture.
- **One inversion.** True ink on Labcoat, true white on Nightshift's near-black, reserved
  for the filled button, the checked box and the caret — the single moment the whole page
  flips.
- **Developer-native type.** The platform's own sans at 400 for text and 600 for headings;
  no embedded font, no load, no flash of unstyled text.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Tables drawn as a ruled data sheet: a square ink frame, a double rule under the header,
  small-caps header labels
- Callouts and fenced code blocks share a margin-bar treatment instead of a boxed card
- Tags and property pills as outlined pills that invert fully under the pointer
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- A toggle thumb tuned per face so it never disappears against its own track
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No embedded fonts, so the theme stays around 12 KB
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Utility**. Install Borozdov Utility under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Beaker** under Style Settings → Borozdov Utility → Variant. The variant brings
this theme's palette, type and corners; its own layout, and its embedded font if it has
one, come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/beaker/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Beaker/`, then choose Borozdov Beaker under
Settings → Appearance → Themes.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Labcoat» — чёрные чернила по
белой бумаге, и тёмный «Nightshift» — тот же журнал, но при свете настольной лампы после
смены. Квадратная рамка у таблиц, полоса на полях у callout и блоков кода, и таблетка —
единственная скруглённая форма. Шрифты не встроены. В каталоге тема живёт вариантом Borozdov Utility: установите Borozdov Utility и плагин Style Settings, затем выберите Beaker в Style Settings → Borozdov Utility → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
