# Failsion
Fuze 4 0.2.14 crash collection
## List of crash methods
- ResFail
## Explanations
- ResFail    
ResFail seems to rapidly change resolution and, what I assume to be an attempt at framerate/RAM optimization, doesn't error, and seems to draw into potentially invalid memory. Depending on where the screen data / screen buffer (the data to be written after update() is stored) is, it miiiiiiiight be possible to execute a small payload using this. Unlikely, though.
