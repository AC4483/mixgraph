# Mixgraph

A free web app for DJs to map which songs they can mix into each other, practice the transitions they're learning, and build sets from the ones they've nailed.

**Use it here:** https://ac4483.github.io/mixgraph/

## Features

- **Next**: pick the track that's playing to see every transition you've logged out of it, plus untried tracks that should mix well (compatible Camelot key, BPM within 6%).
- **Practice**: mark transitions as *To try*, *Learning* or *Nailed*. Log each attempt as clean or messy; three clean in your last five marks it as nailed. "Practice today" picks what needs work.
- **Sets**: pick a start track, length and energy shape (build up, peak and cool down, or steady). Mixgraph chains together transitions you've practiced, shows the energy curve and any gaps, and lets you step through the set live.
- **Graph**: every track placed around the Camelot wheel, with arrows for transitions. Color by key or by energy.
- **Tracks**: your library with title, artist, BPM, key and energy (1–10).

## Your data

Everything is saved in your own browser (localStorage). Nothing is sent to a server, so your library stays on the device and browser you use. Clearing your browser data erases it.

## Run it yourself

It's a single file with no build step: open `index.html` in a browser, or host it anywhere static.
