# Audio Synthesizer

### Praveen Swaminathan and Aritra Dutta

---

**Contents:**
- Contributors and contributions
- Potential Application of synthesizer
- Basic setup and Usage
- How to use and documentation (screenshots)


**Contributors:**
1. Praveen Swaminathan: Was in charge of waveform generation (sine, sawtooth, triangle, square) and ADSR envelope classes.

2. Aritra Dutta: Was in charge of GUI layout, and tying waveform and the GUI Layout classes together for the dropdown menus, button presses, and sliders.



**Setup: Installation**
- ``pip install sounddevice``
- ``pip install tkinter``
- ``pip install numpy``



**Setup: Usage**
- Use the dropdown menus for waveform and sliders for ADSR to have desired settings for sound
- Then, for the notes dropdown menu, choose any note you want in the octave (from middle C to C5)
- Finally, click play to hear the transformed sound
- Below is a labeled picture of the UI

![](SynthDemo.png)


**Potential Application**

The synthesizer that we have made can be modified to make many real world digital noises that represent caution or danger, such as ambulance sirens, fire alarms, tornado warnings, etc. It can also be used simply to make music, like DJ beat drops, or record scratching. 


