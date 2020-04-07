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
AudioPlayerManager.shared.playSoundExclusively(fileName: "powerup11.m4a")
```

- Play or pause sound
- Stop all sounds
- Stop all sound except (file name, tag)
- Pause all sounds
- Pause all sounds except (file name, tag)
- Apply volume to all sounds
- Apply volume to all sounds with file name or tag


