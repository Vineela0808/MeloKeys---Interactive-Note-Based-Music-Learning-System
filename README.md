# MeloKeys---Interactive-Note-Based-Music-Learning-System
## Abstract 
The project is an interactive music system designed to facilitate note-wise music recording and playback. It serves as an excellent learning tool for beginners or individuals exploring music as a hobby. By providing a visual representation of musical notes both key-wise and note-wise, the system enhances the learning experience. Users interact through push buttons that function as keys, each corresponding to a stored musical note. Integrated LEDs beneath each key offer visual feedback upon pressing, reinforcing the learning process. Additionally, a recording feature allows users to capture and replay their performances, enabling guided learning and practice.
## System Overview
Users interact with push-button keys, each mapped to a specific musical note (C, D, E, F, G, A, B, and high C). These keys are connected to a Parallax Propeller Activity Board via a Zero PCB, ensuring seamless signal processing. Upon pressing a key, the corresponding note is played through a speaker, and an LED beneath the key illuminates, visually reinforcing the learning process.
## Components Used
- **Parallax Propeller Activity Board** (Microcontroller)
- **Zero PCB** (For interfacing components)
- **Momentary push buttons** (8 for musical notes)
- **Latching push buttons** (2 for recording and playback)
- **LEDs** (Red & Blue for visual feedback)
- **3D-printed keyboard and base**
- **Speaker** (For sound output)
- **LCD Screen** (For real-time feedback display)
- **Resistors & Wires** (For circuit connections)
## Key Features
- **3D-Printed Keyboard & Base:** A **cantilever beam design** for smooth key presses, with a structured base for housing all electrical components.
- **Push Buttons:**  
  - **Momentary push buttons** (8 keys) to play musical notes.  
  - **Latching push buttons** (2 keys) for **recording and playback** functionalities.
- **LED Indicators:**  
  - **Blue LEDs** illuminate for notes D, E, F, G, A, and B when pressed.  
  - **Red LEDs** remain permanently lit to indicate octave boundaries.
- **Recording & Playback:**  
  - A **record button** allows users to capture musical sequences.  
  - A **playback button** replays the recorded sequences.  
- **LCD Screen:** Displays **real-time feedback** on played notes, recording status, and playback sequences.
- **Speaker Output:** Produces sound for both real-time and recorded notes.
## Working Pattern
** Upon switching on, the system acts like a normal keyboard allowing users to play with 
each key lighting up. 
** A record button, upon selecting, starts recording the following notes played using the 
keys along with the length of time of each note approximating it to a 
whole/half/quarter/semi-quarter note. 
** The recording stops when the record button is selected again
** Upon selecting the play button, the recorded sequence is played with each key of the 
note lighting up and displaying the corresponding note using the 7-segment display. 


