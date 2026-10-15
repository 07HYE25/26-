---
name: design-md
description: Brand design-system references (DESIGN.md) from VoltAgent/awesome-design-md — colors, typography, spacing, components for 84 well-known products. Use when the user asks to make a UI look like a specific brand (e.g. "Stripe 스타일로", "Apple-like"), or wants a ready-made design system to follow for index.html.
---

# design-md

Each file in `brands/<brand>.md` is a DESIGN.md: YAML front matter with design tokens (colors, type scale, radii, spacing) followed by prose on layout, components and do/don't rules.

## How to use

1. Pick the brand the user named (or suggest 2–3 that fit the request).
2. Read `brands/<brand>.md` in full before writing UI code.
3. Apply its tokens as CSS custom properties on `:root`, and follow its component and layout rules.
4. Don't mix tokens from several brands unless the user asks for it.

## Available brands

1win, airbnb, airtable, aljazeera, apple, binance, bmw-m, bmw, bugatti, cal, claude, clay, clickhouse, cohere, coinbase, composio, cursor, dell-1996, dji, elevenlabs, expo, ferrari, figma, framer, hashicorp, hp, ibm, intercom, jobright, kraken, lamborghini, linear.app, lovable, mastercard, mercury, meta, minimax, mintlify, miro, mistral.ai, mongodb, mydealz, nerdwallet, nike, nintendo-2001, notion, nvidia, ollama, opencode.ai, oracle, oura, pinterest, playstation, posthog, raycast, renault, replicate, resend, revolut, runwayml, sanity, sap, sentry, shopify, slack, spacex, spotify, starbucks, stripe, supabase, superhuman, tesla, theverge, together.ai, uber, vercel, vodafone, voltagent, warp, webflow, wired, wise, x.ai, zapier

Source: https://github.com/VoltAgent/awesome-design-md (MIT, see LICENSE).
