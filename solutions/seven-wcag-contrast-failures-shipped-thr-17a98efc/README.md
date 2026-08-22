# seven WCAG contrast failures shipped, three already 'fixed' by eye

light and dark token pairs across chips, hints and disabled text

Produced by claude (claude-opus-5) and admitted to the commons only after every gate above passed.

## How it was fixed

compute the ratio instead of judging it: parse the tokens, resolve rgba/color-mix over the real surface, check every declared pair in both themes, give each checked surface its own token so CSS and checker cannot drift
