# Temple Dash: Jungle Escape

**Web Analytics — Homework 6**  
**Professor:** Apostolos Filippas  
**Created by:** Ishfaq Shah

## About the game
Temple Dash is a small, playable, Temple Run-style endless runner made with HTML5 Canvas, CSS, and vanilla JavaScript. Your goal is to run as far as possible, collect coins, and avoid obstacles. The runner starts at a faster pace (24 distance units/second) and accelerates up to 52 units/second, so each run gets more challenging.

## How to play
- Move between three lanes to avoid obstacles.
- **Stone blocks:** switch lanes or jump over them.
- **Low branches:** switch lanes or slide underneath them.
- **Holes:** switch lanes or jump over them.
- **Gold coins:** run through them to collect them.
- Score = 2 points per meter + 100 points per coin.
- Try to beat your personal best, saved to your browser using localStorage.

### Controls
| Action | Desktop | Mobile |
|---|---|---|
| Move left/right | Left/Right arrow or A/D | Swipe left/right or tap ◀/▶ |
| Jump | Up arrow, W or Space | Swipe up, tap screen or tap ▲ |
| Slide | Down arrow or S | Swipe down or tap ▼ |
| Pause/resume | P, Escape, or on-screen pause | On-screen pause |
| Restart after ending | R or Play Again | Play Again |
| Mute/unmute | Sound toggle | Sound toggle |

## Run it locally
1. Download or clone this repository.
2. Open **index.html** in Chrome, Safari, Firefox, or Edge.
3. Click **START RUNNING**.

No packages, server, build tools, or internet connection are required. Sounds are generated in the browser using the Web Audio API; all visuals are drawn with Canvas, so there are no external asset dependencies.

## Publish on GitHub Pages
1. Sign in to GitHub and create a new repository, such as `temple-dash`.
2. Upload `index.html` and `README.md` to the root of the repository. Commit the files.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose branch **main**, folder **/(root)**, and click **Save**.
6. Once deployment finishes, the game should be available at `https://YOUR-USERNAME.github.io/temple-dash/` (replace YOUR-USERNAME with your actual GitHub username).
7. Open that link in a browser and play-test it.
8. Paste your real live link in this README:

**Playable game:** _Add your published link here_

## Homework 6 submission checklist
- [ ] Code and README are in a GitHub repository.
- [ ] Game starts, player moves, jumps, slides, collects coins, and can restart.
- [ ] Test on desktop and, if possible, a phone.
- [ ] Confirm the published GitHub Pages URL opens and runs.
- [ ] Invite **@apostolosfilippas** as a GitHub repository collaborator (Settings → Collaborators).
- [ ] Submit your **GitHub repository link** for Homework 6.

## Technical notes
- Single-page HTML/CSS/JavaScript game; HTML5 Canvas for rendering, `requestAnimationFrame` for the game loop.
- Three-lane pseudo-3D perspective, procedural obstacle generation, increasing difficulty, collision detection, coin collection, particles, generated sounds, and high-score persistence.
- The game pauses when the browser tab becomes hidden.
- Faster edition: starting speed increased from 17 to 24, maximum speed from 36 to 52; obstacle spacing adjusted to preserve reaction time.