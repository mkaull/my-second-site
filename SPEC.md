# TARGET: today's build

- **Thing:** A one-page “Deal Orbit” vacation-package finder where a student selects a destination on an interactive globe and enters travel dates to reveal the cheapest sample vacation packages.
- **Audience:** A college student who wants a quick, visual way to compare affordable trips for a specific location and time period.
- **Requirements:** One working primary interaction: choose a departure city, destination, and valid date range, then view ranked sample packages. Show a plane animation traveling from the chosen departure point to the destination, with selected states and results that are easy to understand. Honor my approved standing rule in AGENTS.md.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, or private data. Label fictional or sample content. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** A dark, polished globe interface with destination markers; after selection, an animated plane follows a visible route to the destination and a large illustrative vacation image becomes the backdrop for the ranked deal cards.
- **Test:** I can choose a departure city and destination, enter a valid date range, watch the route animation, and see clearly labeled sample packages ranked by total price. I can test an incomplete date selection, point to the standing rule's effect, and—after approval and merge—use the same registered Pages URL.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
