# Year 7 Unit 6 – Fruit Catch Quest (interactive unit)

The Fruit Catch Scratch course rebuilt in the Year 7 interactive-unit format (the same framework as Units 1–5 and the Year 7 dashboard).

- Six levels, one per lesson: Meet Scratch, Move the cat, Make it rain apples, Catch & score, Lives, speed & game over, Polish, test & share.
- Each level: Recall → Learn → I do → We do → You do (Cautious / Challenge / Confident = bronze / silver / gold) → Exit ticket.
- Also has labs, a boss (The Bug Swarm), a knowledge organiser and a certificate.
- Progress is saved in the browser under `y7u6-fruit-catch-v1`.

`index.html` is a single self-contained file. Videos, screenshots and sprites load from this repo's `media/` folder via jsDelivr (`cdn.jsdelivr.net/gh/Mohanad-Nassar/Year-7-Scratch-Course-@main/media/`). The Scratch blocks are drawn with scratchblocks 3.6.4, also from jsDelivr. The page therefore needs an internet connection, and the media must stay on the `main` branch.

To load the media from somewhere else, set `window.Y7_SCRATCH_MEDIA` to that base URL before the page script runs.
