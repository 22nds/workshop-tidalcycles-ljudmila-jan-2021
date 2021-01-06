## 0. Installation
- **Tidal Bootstrap on Mac OS X and Linux Debian**: [https://github.com/tidalcycles/tidal-bootstrap](https://github.com/tidalcycles/tidal-bootstrap)
- **Installing SuperCollider on Linux by Luka Princic**: [https://lukaprincic.si/development-log/installing-supercollider-on-linux-in-2019](https://lukaprincic.si/development-log/installing-supercollider-on-linux-in-2019)

Or install one by one:
- **SuperCollider** [https://supercollider.github.io/](https://supercollider.github.io/)
- **SC3 plugins** [https://supercollider.github.io/sc3-plugins/](https://supercollider.github.io/sc3-plugins/)
- **Quarks** [https://github.com/supercollider-quarks/quarks](https://supercollider.github.io/sc3-plugins/)
- **Vowel Quark** [https://github.com/supercollider-quarks/Vowel](https://supercollider.github.io/sc3-plugins/)
- **SuperDirt** (Tidal's Audio engine) [https://github.com/musikinformatik/SuperDirt](https://github.com/musikinformatik/SuperDirt)
- **SuperDirt startup file fro SuperCollider** [https://github.com/musikinformatik/SuperDirt/blob/develop/superdirt_startup.scd](https://github.com/musikinformatik/SuperDirt/blob/develop/superdirt_startup.scd)
- **Haskel** [https://www.haskell.org/](https://www.haskell.org/)
- **TidalCycles** [https://tidalcycles.org](https://tidalcycles.org)
- **Code editors**:
	- **Atom**: [https://atom.io/](https://atom.io/)
	- **Visual Studio Code**: [https://code.visualstudio.com/](https://code.visualstudio.com/) 
- **Code editor plugins/extensions**
	- **Atom TydalCycles plugin**: [https://atom.io/packages/tidalcycles](https://atom.io/packages/tidalcycles) or [https://github.com/tidalcycles/atom-tidalcycles](https://github.com/tidalcycles/atom-tidalcycles)
	- **Visual Studio Code TidalCycles extension**: [https://marketplace.visualstudio.com/items?itemName=tidalcycles.vscode-tidalcycles](https://marketplace.visualstudio.com/items?itemName=tidalcycles.vscode-tidalcycles) 

## 1. Intro 
- About Workshop
- [TidalCycles Course](https://blog.tidalcycles.org/shop/) by Alex McLean
## 2. MANI short film 
- Code: [https://github.com/22nds/MANI](https://github.com/22nds/MANI)
- Video: [https://vimeo.com/427279482](https://vimeo.com/427279482)
## 3. Soundscaping
- Environmental aspect - animals recorded, traffic sounds, sound polution
- Soundscapes in cities are so noisy
- [Soundscapes from ljubljana](http://www.soundsofchanges.eu/?s=ljubljana)
## 4. Recording sounds 
	- **Nico, 1988** screenshot
	- Audiorecorder (Zoom H4N Pro) or mobile phone or laptop microphone
	- Headphones
	- Windscreen - blocks wind sound
	- Tripod
	- Time and patience, gloves in the winter
## 5. Editing sounds in Audacity and creating samples
- **Audacity**: [https://www.audacityteam.org/](https://www.audacityteam.org/)
- Samples created by Niklas Reppel at Scratch Session (on-the-fly) Toplap Barcelona: [https://www.youtube.com/watch?v=wcXfv2lmPog](https://www.youtube.com/watch?v=wcXfv2lmPog) (Starts at 2:23:20)
- Review samples from SuperDirt - clean, short, frequencies
- Review recording - dirty, long
- **Make the sample**
	- Select the sample from the whole track and copy it
	- Create a new track and paste the sample
	- Remove excess silence at the start and the end
	- Cut out the sample with Z for crossings
	- Loop the sample (Shift + Space)
- **Normalize**
	- Select the whole track
	- Effect > Normalize
- **Remove noise**
	- Select noisy part 
	- Effect > Noise Reduction and Get Noise profile
	- Select the whole track and apply Effect > Noise Reduction
- Add **fade in / fade out** if want it (Effects > Fade In / Effects > Fade Out)
- **Play the sample again in a loop** Shift + Space or Shift and Play button
- Edit the frequencies if needed
- **Export as .wav file** (File > Export)
- **Add metadata** to the sound file

## 6. Naming of files
- Create folders for similar sounds
- Number the files so that you always have a clear reference
- Open files folder in the Code editor to see available files
## 7. Playing with TidalCycles
- Get the samples for the workshop on [GitHub](https://github.com/22nds/workshop-tidalcycles-ljudmila-jan-2021) or use your own
- Start SuperCollider 
- Add the sample files dierctory to startup (File > Open startup file) file and restart Supercollider
- Open the code editor

## 8. TidalCycles Basics
- Playing default samples
- BPM / CPM
- Playing soundscaping samples
- Tidal effects and filters 

## 9. Ideas
- Start with a clean sample, make a beat and then modify it

## 10. Recording
- Record in SuperCollider IDE s.makeGui; or Server > Start recording

## 11. Resources
- Audacity Manual https://manual.audacityteam.org/
- TidalCycles Documentation https://tidalcycles.org/index.php/Userbase
- “Learning TidalCycles” course by Alex McLean, the creator of TidalCycles 
https://blog.tidalcycles.org/shop/ - Part one is open for everybody
- Videos by Mike Hodnick: https://www.youtube.com/c/kindohm/videos
- Ableton: Get started Making Music https://learningmusic.ableton.com/index.html
- TidalCycles Cheat Sheet https://docs.google.com/spreadsheets/d/1yVCrMT2v1IH8JjUI2vK8bhmz2HGCw8yIOrTZEpCzumI/edit?usp=sharing
