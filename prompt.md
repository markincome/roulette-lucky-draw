Build an HTML page for a roulette lucky draw (大樂透) game.

The wheel should spin with a smooth, springy feel and slow down after a few seconds.
At the center, place a SPIN button and an arrow pointing up — the arrow shows the winning number.

UI:
- Input for the maximum number (default: 49)
- Input for the number of draws (default: 6)
- Seed button — generates and shows a random seed
- Clear button — clears the winners list
- Stop button — disabled at first; enabled while spinning so the user can stop early
- SPIN button — same as clicking the center SPIN

Behavior when SPIN is clicked:
- The wheel spins and randomly picks the set number of draws

After each draw:
- Remove the selected number from the pool so it can’t repeat
- Pause 0.5 seconds before the next draw
- Add the number to the winners list. Individual winner can remove from list and add to draw again by click top right 'X' on the number.
