# Design notes

## Tokens
| Name | Hex | Use |
|---|---|---|
| Void | `#0a0820` | Background |
| Shard | `#3df5ff` | Player, collectibles, primary button |
| Hazard | `#ff3d9a` | Obstacles |
| Spark | `#ffc83d` | Focus ring, explosions |
| Ink | `#e9e7ff` | Text |

## UX principles applied
- One input model: pointer position maps straight to ship position, so there is nothing to learn.
- Color carries meaning: cyan is good, pink is danger, and shapes differ too (diamond vs. square).
- Failure explains itself: the end screen shows score and best, with a single "Retry" action.
- Motion is purposeful: screen shake and particles only on impact, ship trail only while flying.
- Mobile first: safe-area insets, touch drag, `touch-action: none`, DPR capped at 2.
- Accessibility: visible focus ring, high-contrast text, `viewport-fit=cover`.
