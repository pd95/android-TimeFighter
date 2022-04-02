# Time Fighter

My first android app (based on the Ray Wenderlich course 
[Your first Kotlin Android app](https://www.raywenderlich.com/4936497-your-first-kotlin-android-app/).

A simple game where you have to tap a button until the time runs out.

## Content

- Game logic
    - timer management (start timer, end game after 60s)
    - count number of button taps (=score)
    - game state:
        - started
        - end

- UI
    - single button to start (start game after first tap on button), each tap will increment score
    - show number of taps
    - show remaining time
    - show result after time runs out
    - restart game