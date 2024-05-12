# Nono-ConLuigiDallapicolla-patch

## Credits 

Luigi Nono, _Con Luigi Dallapiccoa_ (1979) 

Patch by Ilia Viazov and Louis Goldford 

## Change Log   

_All notable changes to this project will be documented in this file._   

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

### [0.0] 2024-05-05   
_Original version received from Johannes via email. Nothing works as it should._   

##### Added  

##### Changed  

##### Removed  

### [1.0] 2024-05-09   
_Initial revisions made by Ilia._   

##### Added  
- v1.0 panic button
- v1.0 preset and counter
- v1.0 initial mapping for NanoKontrol2

##### Changed  
- v1.0 corrected ring modulation synthesis core
- v1.0 corrected amplitude sliders (not frequency scaling)  

##### Removed  
- v1.0 scale object 

### [2.0] 2024-05-09   
_Revisions made by Louis._   

##### Added  
- v2.0 3 mic inputs for the 3 generators, with 3 input `live.meter~` objs 
- v2.0 3 outputs to be panned at the mixing board 
- v2.0 `live.gain~` objects set to one channel each 
- v2.0 added extra gain staging for panic

##### Changed  
- v2.0 panic button now uses a `live.text` object instead to show on/off state

##### Removed  
- v2.0 removed erroneous `*~` objects

### [3.0] 2024-05-09   
_Revisions made by Louis._   

##### Added  
- v3.0 3 basic old-school wrapper for NanoKontrol2
- v3.0 in hindsight, this was added without knowing Ilia had used Max's in-built MIDI mapping   

##### Changed  

##### Removed  

### [4.0] 2024-05-10   
_Revisions made by Louis._   

##### Added  
- v4.0 added panning controls 
- v4.0 sliders have initial value closing gating of input signal
- v4.0 added init routine

##### Changed  
- v4.0 reduced again to stereo ouputs

##### Removed  

### [5.0] 2024-05-11   
_Revisions after rehearsal made by Ilia._   

##### Added  

##### Changed  
- v5.0 Fixed inputs sends to generators

##### Removed  


