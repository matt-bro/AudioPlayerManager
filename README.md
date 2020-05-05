# AudioPlayerManager
Play multiple audio files and manage them

## Functions

### Play sound with file name or tag
Just play the sound once
```swift
AudioPlayerManager.shared.playSound(fileName: "powerup14.m4a")
```
### Loop sound with file name or tag
Infinite loop for a sound e.g. background sound
```swift
AudioPlayerManager.shared.loopSound(fileName: "song18.mp3")
```
### Play sound exclusively
Sound of the same file name cant be played while another one is playing
```swift
AudioPlayerManager.shared.playSound(fileName: "powerup11.m4a", exclusively: true)
```
### Play or pause sound
```swift
//with filename
AudioPlayerManager.shared.playOrPauseSound(fileName: "powerup14.m4a")
//with tag
AudioPlayerManager.shared.playOrPauseSound(tag: 1)
```
### Stop/pause all sounds
```swift
AudioPlayerManager.shared.stopAllSounds()

AudioPlayerManager.shared.pauseAllSounds()
```
### Stop/pause all sound except (file name, tag)
```swift
AudioPlayerManager.shared.stopAllSounds()

AudioPlayerManager.shared.pauseAllSounds()
```
### Apply volume to all sounds
```swift
AudioPlayerManager.shared.applyVolumeToAllSounds(volume: 1.0)
```


