Using Code
Make sure you have MossAudioSystem package in your Assets folder

Call “MAS_Manager.PlaySoundEffect(ac, position, volume)” to play a sound effect directly.

Call “MAS_Manager.PlayBackgroundMusic(ac, fadeOutTime, fadeInTime, vol)” to fade in new background music

Call “MAS_Manager.StopBackgroundMusic(fadeTime)” to stop playing background music.

Call “MAS_Manager.SetBackgroundMusicVol(volume)” to change background music volume

Call “MAS_Manager.PauseBackgroundMusic()” to pause background music

Call “MAS_Manager.UnPauseBackgroundMusic()” to keep playing


Using Prefab
You can also use prefabs created in MossAudioSystem folder to use the features directly.

MAS_BgFade can help you change background music. 
Create an instance in the scene
Set the audio clip and other information
Call it through a button or other components

MAS_EffPlay can be used in the same way to play sound effect
MAS_Manager can be used in the same way to pause, replay. Set volume of the background music.




