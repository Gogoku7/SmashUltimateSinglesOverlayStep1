# SmashUltimateSinglesOverlayStep1
Step 1 of a project to create a dynamically editable overlay for Super Smash Bros. Ultimate Singles usable for any tournament streamer using HTML, JavaScript, CSS and C#.

**How to use in Open Broadcaster Software (OBS Studio):**
- Add a new Browser source to your scene.

![alt img]()

- Check the Local file checkbox and click Browse.

![alt img]()

- Select gameOverlay.html of this project.
- Set the resolution and framerate. (1920 x 1080 at 60 frames per second recommended)
- Check Refresh browser when scene becomes active checkbox.

![alt img]()

You are now ready to stream with the overlay.

As the streamed set(s) progress, you can update the overlay by changing:

- #player1Character
- #player1NameText:before
- #player1Port
- #player1ScoreText:before
- #player1TwitterText:before
- #player2Character
- #player2NameText:before
- #player2Port
- #player2ScoreText:before
- #player2TwitterText:before
- #roundBoxText:before
- #tournamentBoxText:before

at the bottom of styles.css

At this step, the overlay dynamically updates whenever the CSS is altered!
