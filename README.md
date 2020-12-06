<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/matt-bro/AudioPlayerManager/master/icon.png" alt="Icon" width="200">
  <br>
  AudioPlayerManager
  <br>
</h1>

<h4 align="center">Play and control sounds on iOS easily</h4>


## Description

This is a little helper that I use for projects where I need to play effects sound/background music. 
Dependend on the needs I can play the sounds exclusively (same sound cant be played until it is finished), start, stop, pause, apply volume, mute them.

## Key Features

* Play/Pause/Stop sounds by file name or tag
* Play/Pause/Stop sounds all sounds or just a selection
* Play a sound as a loop
* Apply volume to selected sounds

## Examples

```swift
// Play sound with file name or tag
// Just play the sound once
AudioPlayerManager.shared.playSound(fileName: "powerup14.m4a")

// Loop sound with file name or tag
// Infinite loop for a sound e.g. background sound
AudioPlayerManager.shared.loopSound(fileName: "song18.mp3")

// Play sound exclusively
// Sound of the same file name cant be played while another one is playing
AudioPlayerManager.shared.playSound(fileName: "powerup11.m4a", exclusively: true)

// Play or pause sound
// with filename
AudioPlayerManager.shared.playOrPauseSound(fileName: "powerup14.m4a")
// with tag
AudioPlayerManager.shared.playOrPauseSound(tag: 1)

// Stop/pause all sounds
AudioPlayerManager.shared.stopAllSounds()
AudioPlayerManager.shared.pauseAllSounds()

// Stop/pause all sound except (file name, tag)
AudioPlayerManager.shared.stopAllSounds()
AudioPlayerManager.shared.pauseAllSounds()

// Apply volume to all sounds
AudioPlayerManager.shared.applyVolumeToAllSounds(volume: 1.0)
```

## How To Use

Just drop the AudioPlayerManager into your XCode project.


## License

MIT

---

> GitHub [@matt-bro](https://github.com/matt-bro) &nbsp;&middot;&nbsp;
