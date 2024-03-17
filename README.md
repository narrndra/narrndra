## Libraries used:
cv2 (OpenCV): to capture video from the camera, detect faces and display frames.
Keyboard: used to verify keyboard input.
os: used to interact with the operating system.
web browser: used to open music files using the default system media player.
random: used to select a random playlist.
time: used to add delay.
face_recognition: Used for face detection using the Haar Cascade classifier.
Function:
Initialization:
Code that initializes the camera (shutter) to capture video.
Install Haar Cascade classifier for face detection.
Playlist starts:< br>
Our playlists are started by emotions: happy, sad, angry.
Give music information the right relationship for each emotion.
Function:
play_song(): Use the default system environment to play the current song
switch_playlist(): Randomly switch the playlist to your desired appearance.
Main loop:
The program enters an endless loop and continues capturing frames from the camera.
Faces are detected in each frame using the Haar Cascade classifier.
If a face is detected:
Select the playlist according to the desired view.
Play the song now.
Wait to press the spacebar to move to the next song.
Now the song index is increased.
The face is highlighted with a rectangle on the visible frame.
The loop continues until the "q" key is pressed, at which point the program exits.
