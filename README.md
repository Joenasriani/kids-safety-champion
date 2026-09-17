# Safety Champion Adventure

Play: https://kids-safety-champion.vercel.app/

Safety Champion Adventure is a five-level letter-assembly safety game developed as part of a multi-game interactive children’s edutainment activation in the UAE.

## Game structure

Each run builds a five-question mission from three prompt banks:

- two one-word safety answers;
- two two-word safety answers;
- one three-word safety answer.

For each level, the answer letters are shuffled. The player selects the letters in order to reconstruct the answer. The most recently entered letter can be removed by selecting its filled slot.

**safety prompt → shuffled answer letters → ordered letter selection → completed answer → next level**

If a completed answer is incorrect, the same level reloads. Completing all five levels reaches the game’s Safety Champion result screen.

## Safety topics represented

The current question bank includes scenarios involving unknown pills or substances, medicine supervision, strangers, unsafe offers, trusted adults, and unknown online contacts.

## Activation context

This game belongs to the same `kids-*` game set developed for the multi-game interactive children’s edutainment activation in the UAE.

## Evidence boundary

The game implements safety prompts and answer reconstruction. The repository does not contain a study measuring safety knowledge retention, behavior change, or transfer outside the game. The in-game “Certified Safety Champion” message is a completion reward inside the game, not an external credential.

## Repository scope

The playable implementation is contained entirely in `index.html`.

`index.html` is preserved as the game artifact. Documentation and discovery files must not alter questions, answers, mission composition, letter order, undo behavior, progression, controls, visuals, timing, or runtime behavior.
