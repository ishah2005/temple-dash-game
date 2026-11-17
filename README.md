# Temple Dash: Jungle Escape 🏃🌴

**Web Analytics — Homework 6**  
**Student:** Ishfaq Shah  
**Professor:** Apostolos Filippas  
**Built with:** HTML5, CSS, and JavaScript

## Play the game

🎮 **[Play Temple Dash online](https://ishah2005.github.io/temple-dash-game/)**

> The online link works after GitHub Pages has been enabled. If the page is unavailable, follow the instructions under **Run locally** below.

**[View the source code](https://github.com/ishah2005/temple-dash-game)**

## Game overview

Temple Dash: Jungle Escape is a fast-paced, Temple Run-inspired endless runner. The player runs down an ancient jungle path, switches between three lanes, jumps over obstacles, slides under branches, and collects gold coins. The goal is simple: **survive as long as possible and beat your high score**.

The runner starts at **42 distance units per second** and gradually accelerates to a maximum of **95**, making each attempt more challenging.

## How to play

1. Press **START RUNNING**.
2. Move between the three lanes to avoid incoming hazards.
3. **Jump** over stone blocks and gaps; **slide** under low branches.
4. Collect coins to increase your score.
5. When you crash, view your results and press **Play Again** to try to beat your personal best.

**Scoring:** 2 points per distance unit traveled, plus 100 points for each collected coin. High scores are saved in the browser on the same device.

## Controls

| Action | Keyboard | Phone / tablet |
| --- | --- | --- |
| Move left | Left arrow or A | Swipe left or tap ◀ |
| Move right | Right arrow or D | Swipe right or tap ▶ |
| Jump | Up arrow, W, or Space | Swipe up or tap ▲ |
| Slide | Down arrow or S | Swipe down or tap ▼ |
| Pause / resume | P, Escape, or pause button | Pause button |
| Restart after a crash | R or Play Again | Play Again |
| Sound on / off | On-screen sound toggle | On-screen sound toggle |

## Game features

- Three-lane jungle running with a pseudo-3D perspective
- Jumping, sliding, and lane-switching
- Stone blocks, low branches, and holes
- Collectible gold coins and score tracking
- Increasing running speed and procedurally generated hazards
- Sound effects and animated visual effects
- Personal-best score saved using browser local storage
- Game-over screen with instant replay
- Desktop keyboard controls and mobile touch controls

## Run locally

1. On this repository, select **Code → Download ZIP**.
2. Unzip the downloaded folder.
3. Open **index.html** in a modern web browser (Chrome, Safari, Firefox, or Edge).
4. Press **START RUNNING** to play.

No additional packages, Python installation, command line, or development server are needed. The game is self-contained in `index.html`; graphics are drawn with HTML5 Canvas, and audio is generated in the browser.

## GitHub Pages setup

The repository already contains the required `index.html` at its root. To publish the game:

1. Go to [this repository's Pages settings](https://github.com/ishah2005/temple-dash-game/settings/pages).
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then click **Save**.
4. After GitHub finishes deploying, open [the live game](https://ishah2005.github.io/temple-dash-game/) and test the controls.

## Homework 6 submission

**Repository to submit:** https://github.com/ishah2005/temple-dash-game

Before submitting:

- [ ] Open the game and confirm it starts, moves, jumps, slides, and restarts.
- [ ] Check that the coin counter, score, and high score work correctly.
- [ ] Enable GitHub Pages and verify the playable link above.
- [ ] Invite **[@apostolosfilippas](https://github.com/apostolosfilippas)** as a repository collaborator using **Settings → Collaborators**.
- [ ] Submit the repository URL on Blackboard.

## Technical details

The game uses HTML5 Canvas for rendering, JavaScript and `requestAnimationFrame` for animation and game logic, procedural hazard spawning, collision checks, Web Audio API sounds, and `localStorage` for the high score. It also pauses when the browser tab is hidden.

This project was created for **Fordham University's Web Analytics Homework 6**.
