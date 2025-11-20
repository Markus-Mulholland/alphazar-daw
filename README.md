# alphazar-daw
Firmware and design files for an Ableton HID powered by a Pico

# Feature List

## mk1

### Interface
5 Switches
1 Knob

### Functions
- Track Controls
  - Select: scroll
  - Arm: tap
  - Mute/Unmute: tap
  - Solo: hold
  - Volume: hold + scroll
- Transport Controls
  - Play: tap
  - Stop: tap
  - Record: tap
  - Tempo Tap
- Master Volume: hold + scroll

#### Ideas
- Joystick for scroll
- hold + pot for scroll
  
#### Track Selector
Select the track you would like to work with. This uses ableton's track-select UI to show a visual highlight of the selected track.
If a track has been armed, changing the selected track will arm the track that you navigate to.

Interface: Tap left top and middle buttons to move up and down the list of tracks.

#### Mute/Unmute Selected Track
Mute or unmute the selected track.

#### Solo
Solo the selected track by holding the Mute/Unmute button

#### Arm Selected Track
Arm the selected track for recording.


#### Start Recording
Start/Stop the arrangement recording on the armed track


#### Volume Pot
Adjust the volume on the selected track

Interface: Pot using ADC












# Useful reading
https://www.beyondlogic.org/usbnutshell/usb2.shtml#Connectors
https://www.ableton.com/en/manual/midi-and-key-remote-control/
