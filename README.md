# Death Star Defense

A Star Wars–themed mini-game built on top of Hakim El Hattab’s original **Core** canvas game. Defend the Death Star by rotating your energy shield to deflect enemy torpedoes and collect vital shield-crystals!

## Features

* **Opening Crawl**: A polished Star Wars–style intro sequence with themed fonts and scrolling text.
* **HUD & UI**: Dynamic status display showing score, time, and FPS. Panels for start, win, and game-over states.
* **Game Logic**:

  * Reset and start: Clicking **Start** resets score, difficulty, timers, player energy, and organism lists.
  * Win/Lose Conditions: Lose when energy drops to zero; win when you exceed **2,000 points**. Shows either a **Restart** button or a **prize-claim link**.
* **Audio**:

  * **Menu Music**: Loops silently until user interaction (to meet autoplay policies), then plays on page load.
  * **Game Music**: Pauses menu theme and starts in-game track on start; pauses again on game over.
* **Polished UX**: Seamless transitions between intro, gameplay, win, and loss states.

## Play Online
https://pereze5.github.io/deathstar_core/ 

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/death-star-defense.git
   ```
2. Open `index.html` in your browser.
3. Ensure `assets/menu.mp3` and `assets/game.mp3` are in place for audio.

## Usage

* Click **Start Sequence!** to begin.
* Rotate your emitter (mouse or touch) and hold **SPACE** to activate the shield.
* Deflect red torpedoes to survive and let green crystals through to recharge.
* Survive until you score 5,000+ points to win and claim your prize link!

## Customization

* Adjust difficulty scaling or score thresholds in `js/core.js`.
* Swap out audio files in `assets/` to change themes.
* Modify styles in `css/main.css` for custom visuals.

## License

This project is MIT–licensed, based on the original [Core game by Hakim El Hattab](http://hakim.se). Feel free to tinker and share!
