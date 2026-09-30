# Booth Practice

A single-page training game for Dash0 booth staff. It walks through 34 real booth conversations (competitor comparisons, OpenTelemetry, pricing, Agent0, Darkplane, and persona-specific questions) so you can rehearse answers before an event.

## How it works

- Read the attendee's line and say your answer out loud first.
- Reveal three options and pick the one closest to what you said.
- Best answers earn 10 points, partly right answers earn 5, and back-to-back best answers add a streak bonus.
- After each round you get a short "Learn" note and links to the relevant Dash0 docs and comparison pages.
- Play solo or in pair mode, where two people take turns.

Scores are kept in your browser only (localStorage). Nothing is sent anywhere.

## Running it

It's one static file, `index.html`, with no build step. Open it in a browser, or use the GitHub Pages site for this repository.

## Keeping it accurate

Model answers were drafted from public Dash0 docs, pricing, and comparison pages in September 2026. Product details change quickly, so check the linked sources and confirm with product marketing before relying on a claim.
