# Nativify

A phone-first web app for advanced English speakers who want to sound native.

- **Say it like a local**: write something your way and see how a native speaker would say it, with each change explained.
- **Decode**: paste slang or a line you half understood, get the meaning and tone, then use the phrases yourself.
- **My phrases**: saved phrases come back for practice on a spaced schedule.

It's a static site (`index.html`, no build step). AI calls go straight from the browser to the Anthropic API using a key the user enters in Settings; the key stays in that browser's local storage. Saved phrases also live in local storage.

To run locally: `python3 -m http.server` in this folder, then open http://localhost:8000.
