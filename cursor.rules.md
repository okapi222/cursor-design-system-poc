# Cursor Design System Rules (POC)

## Always follow these files first
When generating UI designs or frontend code for this repo, you MUST follow:
- standards/house-style.md
- tokens/colors.json
- tokens/typography.json

## General rules
- Prefer simple, clean layouts with whitespace.
- Use the spacing tokens for padding/margins (do not invent random spacing).
- Use typography tokens for font sizes and weights.
- Use color tokens for backgrounds, text, borders, and semantic states.

## Output rules (important)
- When writing UI code, reference tokens by name (e.g., color.brand.primary) and do not hardcode hex values unless asked.
- If something is missing from tokens, propose a token addition instead of inventing a one-off value.
- If a request conflicts with house style, explain the conflict and suggest the closest compliant option.

## Component rules (for now)
- Only implement components that exist in components/ or are explicitly requested.
- Start with Button and TextInput patterns. Prefer reuse over new patterns.
