# Desktop configuration 
1. Clone this to your ~/.config folder.

# Note regarding volume 
1. Do check the openbox rc file and change the volume control to follwing if the keyboard shortcut doesn't work.
## For volume up by 5%.
2. `amixer -D pulse sset Master 5%+`
## For volume down by 5%.
3. `amixer -D pulse sset Master 5%-`
## For mute.
4. `amixer -D pulse sset Master 100%-`
