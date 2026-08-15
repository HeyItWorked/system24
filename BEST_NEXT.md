# System24 Best Next

System24 Best Next is a personal, local-only customization built on top of
[refact0r/system24](https://github.com/refact0r/system24). It preserves the
original TUI direction while adding a more expressive profile and navigation
system for Vesktop/Vencord.

## Install

Download [`theme/system24-best-next.theme.css`](theme/system24-best-next.theme.css)
and place it in the Vesktop or Vencord themes directory. The file is
self-contained, so it does not depend on this fork being published with GitHub
Pages.

## Main controls

Edit these variables near the beginning of the theme:

```css
--best-next-color: #55d6ff;
--profile-preset: cyber; /* session | cyber | mainframe | void */
--spicetify-text-touch: on; /* off | on */
--text-touch-active-fill: 12%;
--premium-profiles: on; /* off | on */
--premium-scope: all; /* all | premium */
--premium-glow: 0.55;
--scanline-opacity: 0.06;
```

The primary color drives the application accent, navigation markers, avatar
bezels, profile framing, and terminal details. A secondary contrast color is
derived automatically.

## What changed

- Expanded terminal surfaces for chat, navigation, members, input, dialogs,
  menus, settings, and profile cards.
- Presence-aware avatar bezels across messages, DMs, members, user panels, and
  profile contexts.
- Selectable `session`, `cyber`, `mainframe`, and `void` profile compositions.
- `all | premium` scope control for local fake-Nitro use.
- Reduced-motion support and pointer-safe decorative overlays.
- Responsive panel labels with consistent sizing, contrast, and stacking.
- Optional Spicetify Text-inspired panel legends, tree markers, and restrained
  active-row fills adapted for Discord rather than copied from Spotify.
- Current Discord/Vesktop profile selectors, including settings profile cards.

## Attribution

The upstream project, license, contributor history, fonts, and original theme
assets remain credited to refact0r and the System24 contributors. Best Next is
a personal derivative and does not include or reproduce Discord Shop artwork.

The optional text-touch layer takes visual inspiration from
[darkthemer's Text theme](https://github.com/spicetify/spicetify-themes/tree/master/text)
in the official Spicetify Themes repository. Its Discord selectors and
implementation are original to this fork; upstream CSS was used as a design
reference rather than copied into the theme.
