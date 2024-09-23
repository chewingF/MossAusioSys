Using Code
Make sure you have MossAudioSystem package in your Assets folder

Call “MAS_Manager.PlaySoundEffect(ac, position, volume)” to play a sound effect directly.

![alt text](https://github.com/chewingF/MossAusioSys/blob/main/Readme%20Imgae/Image1.png?raw=true)

Call “MAS_Manager.PlayBackgroundMusic(ac, fadeOutTime, fadeInTime, vol)” to fade in new background music

![alt text](https://github.com/chewingF/MossAusioSys/blob/main/Readme%20Imgae/Image2.png?raw=true)

Call “MAS_Manager.StopBackgroundMusic(fadeTime)” to stop playing background music.

![alt text](https://github.com/chewingF/MossAusioSys/blob/main/Readme%20Imgae/Image3.png?raw=true)

Call “MAS_Manager.SetBackgroundMusicVol(volume)” to change background music volume

![alt text](https://github.com/chewingF/MossAusioSys/blob/main/Readme%20Imgae/Image4.png?raw=true)

Call “MAS_Manager.PauseBackgroundMusic()” to pause background music

![alt text](https://github.com/chewingF/MossAusioSys/blob/main/Readme%20Imgae/Image5.png?raw=true)

Call “MAS_Manager.UnPauseBackgroundMusic()” to keep playing

![alt text](https://github.com/chewingF/MossAusioSys/blob/main/Readme%20Imgae/Image6.png?raw=true)


Using Prefab
You can also use prefabs created in MossAudioSystem folder to use the features directly.

MAS_BgFade can help you change background music. 
Create an instance in the scene

![alt text](https://github.com/chewingF/MossAusioSys/blob/main/Readme%20Imgae/Image7.png?raw=true)

Set the audio clip and other information

![alt text](https://github.com/chewingF/MossAusioSys/blob/main/Readme%20Imgae/Image8.png?raw=true)

Call it through a button or other components

![alt text](https://github.com/chewingF/MossAusioSys/blob/main/Readme%20Imgae/Image9.png?raw=true)


MAS_EffPlay can be used in the same way to play sound effect
MAS_Manager can be used in the same way to pause, replay. Set volume of the background music.




