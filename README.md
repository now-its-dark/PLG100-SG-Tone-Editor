![header](/img/header.png)

This is a very WIP Ctrlr editor panel for the [Yamaha PLG100-SG, Formant Synging plug-in board](https://youtu.be/q4-nn8B_L0g?t=3).


**All of the controls from the Sysex specification are present and usable. It's just ugly.**
| Task          | Status        | 
| ------------- |---------------| 
| Control of documented parameters     | ☒ Completed |
| Layout refinement     | ☐ In Progress    |
| Visual design | ☐ In Progress      | 
| Correct param name display in DAW| ☐ In Progress      | 
| Librarian & MIDI file export | ☐ Not started     | 
| Macros & syllable/dictonary input | ☐ Not started     |


Though the intended use of this board was more as a proto-vocaloid / vocal synthesis kind of thing— [enabling lyrics to be sung in Japanese](https://youtu.be/4ebITb69igk?t=8), there is quite a bit of interesting sound design potential available, for purely instrumental applications.

There is an "SG Easy Editor" OPT module created by Yamaha at the time of release, but it is fairly cumbersome to use for tweaky sound design, partially due to age, as it displays very tiny on a hi-res display and also due to the design: it is broken into multiple, separate panel elements. This tool also requres either XGWorks or SOL to host it, which limits how accessible the device can be within a modern DAW.


I'm working on a properly designed UI and also aiming to expand this beyond basic parameter controls, but it is already really fun to use! 
If you are interested in synthesis and have access to one of these boards, I'd love to hear your thoughts.

Some design mocks I'm putting together: 
next step is to tune these a bit and bring the assets into the ctrlr editor.

![mock1](/img/mocksv1/01%20PLG100-SG_Voice_Editor_system.png)
![mock2](/img/mocksv1/02%20PLG100-SG_Voice_Editor_formant.png)
![mock3](/img/mocksv1/03%20PLG100-SG_Voice_Editor_modulation.png)
