# Klipper-Music-Player
Macro that allows you to play music using a gcode shell script
Just run the following in ssh to install 

```
sudo apt update
sudo apt install espeak
sudo apt install aplay
```
After you just need to include audio.cfg in your printer.cfg file and then add your audio to 
```
/home/<username>/printer_data/audio
```
Then just edit the file as needed to include your audio. Its designed to play random songs from a list but if you set the default to 1 it will only play 1.

[Also check out my Klipper Mainsail Themes!](https://github.com/yourbuddydinec/Mainsail-Themes)
