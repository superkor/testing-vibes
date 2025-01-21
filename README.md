# testing-vibes

## Project Overview/Plan
- The goal of this project is to make a Karaoke based game where players would sing (like in a karaoke). 
- From each player's vocals (and the given instrumental piece played for each player), judge each player's singing to determine a winner
 - this can be done by comparing the original song, splitting the vocals and instrumental pieces via AI (to have two separate tracks), and judging the player's singing on the reference vocals
   - potential criterium would be:
     1. tempo (if the tempo is on time with the instrumental)
     2. pitch (if the pitch is similar to the original song)
     3. artistic styling (if the artistic styling is similar to the original song's intentions)
         - styling could be like expressions, articulation, timbre, phrasing, vibrato
     4. other criteria tbd
   - could also not compare against the original song and judge solely on from other players

### Potential Requirements for Components
- A microcontroller or some sort of computer to be the main controller of the game, handling the computations, inputs, outputs, user interfaces
- Mics and audio interfaces
- Display (visual and audio)
- If wireless, some wireless TX/RX devices are required

### Potentially Required Technical Components
- DSP for processing the songs to transmit/capture to and from players via I/O devices
- Communications for interacting with the player (mics, displays, speakers), and between components of the systems (wireless TX/RX)
- AI/ML for splitting vocals from instrumentals

## Status of the Project - TBD
☐ Decided and acquired components for the project <br>
☐ Planning implementation and scope of components <br>
☐ Integration of components <br>