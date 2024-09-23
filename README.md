Using Code
Make sure you have MossAudioSystem package in your Assets folder

Call “MAS_Manager.PlaySoundEffect(ac, position, volume)” to play a sound effect directly.
![alt text]([http://url/to/img.png](https://github.com/chewingF/MossAusioSys/blob/main/Readme%20Imgae/Image1.png))
Call “MAS_Manager.PlayBackgroundMusic(ac, fadeOutTime, fadeInTime, vol)” to fade in new background music
![alt text]([http://url/to/img.png](https://github.com/chewingF/MossAusioSys/blob/main/Readme%20Imgae/Image2.png))
Call “MAS_Manager.StopBackgroundMusic(fadeTime)” to stop playing background music.
![alt text]([http://url/to/img.png](https://github.com/chewingF/MossAusioSys/blob/main/Readme%20Imgae/Image3.png))
Call “MAS_Manager.SetBackgroundMusicVol(volume)” to change background music volume
![alt text]([http://url/to/img.png](https://github.com/chewingF/MossAusioSys/blob/main/Readme%20Imgae/Image4.png))
Call “MAS_Manager.PauseBackgroundMusic()” to pause background music
![alt text]([http://url/to/img.png](https://github.com/chewingF/MossAusioSys/blob/main/Readme%20Imgae/Image5.png))
Call “MAS_Manager.UnPauseBackgroundMusic()” to keep playing
![alt text]([http://url/to/img.png](https://github.com/chewingF/MossAusioSys/blob/main/Readme%20Imgae/Image6.png))

Using Prefab
You can also use prefabs created in MossAudioSystem folder to use the features directly.

MAS_BgFade can help you change background music. 
Create an instance in the scene
![alt text]([http://url/to/img.png](https://github.com/chewingF/MossAusioSys/blob/main/Readme%20Imgae/Image7.png))
Set the audio clip and other information
![alt text]([http://url/to/img.png](https://github.com/chewingF/MossAusioSys/blob/main/Readme%20Imgae/Image8.png))
Call it through a button or other components
![alt text]([http://url/to/img.png](https://github.com/chewingF/MossAusioSys/blob/main/Readme%20Imgae/Image9.png))

MAS_EffPlay can be used in the same way to play sound effect
MAS_Manager can be used in the same way to pause, replay. Set volume of the background music.




