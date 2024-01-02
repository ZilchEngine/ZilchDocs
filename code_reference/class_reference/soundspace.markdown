 `Component` `Sound`



(NOTE) Sound functionality associated with a Space.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ InterpolateDecibels](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#interpolatedecibels-void)|[ Decibels](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#decibels-zilch-engine-doc)|[component](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/component.markdown)| |
|[ InterpolatePitch](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#interpolatepitch-void)|[ InputNode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#inputnode-zilch-engine-do)| | |
|[ InterpolateSemitones](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#interpolatesemitones-voi)|[ MuteAudio](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#muteaudio-zilch-engine-do)| | |
|[ InterpolateVolume](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#interpolatevolume-void)|[ OutputNode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#outputnode-zilch-engine-d)| | |
|[ PlayCue](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#playcue-zilch-engine-docu)|[ Paused](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#paused-zilch-engine-docum)| | |
|[ PlayCuePaused](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#playcuepaused-zilch-engin)|[ PauseWithTimeSpace](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#pausewithtimespace-zero)| | |
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#soundspace-void)|[ Pitch](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#pitch-zilch-engine-docume)| | |
| |[ PitchWithTimeSpace](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#pitchwithtimespace-zero)| | |
| |[ Semitones](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#semitones-zilch-engine-do)| | |
| |[ SoundNodeInput](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#soundnodeinput-zilch-engi)| | |
| |[ SoundNodeOutput](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#soundnodeoutput-zilch-eng)| | |
| |[ Volume](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundspace.markdown#volume-zilch-engine-docum)| | |


 #  Properties


---  
 #  Decibels : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The volume adjustment, in decibels, applied to all sounds in the space. A value of 0 does nothing, 6 will double the sound's volume, -6 will halve it.
> ``` lang=cpp, name=Nada
> var Decibels : Real


---  
 #  InputNode : [soundnode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundnode.markdown)

 `read-only`

> DEPRECATED The SoundNodeInput property should be used instead.
> ``` lang=cpp, name=Nada
> var InputNode : SoundNode


---  
 #  MuteAudio : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Silences all audio output from this space but processes audio normally.
> ``` lang=cpp, name=Nada
> var MuteAudio : Boolean


---  
 #  OutputNode : [soundnode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundnode.markdown)

 `read-only`

> DEPRECATED The SoundNodeOutput property should be used instead.
> ``` lang=cpp, name=Nada
> var OutputNode : SoundNode


---  
 #  Paused : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Setting this Property to true will pause all audio in the space. Setting it to false will resume all audio.
> ``` lang=cpp, name=Nada
> var Paused : Boolean


---  
 #  PauseWithTimeSpace : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> If true, the audio of the space will pause when the space is paused.
> ``` lang=cpp, name=Nada
> var PauseWithTimeSpace : Boolean


---  
 #  Pitch : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The pitch adjustment applied to all sounds in the space. A value of 0 will do nothing, 1 will raise the pitch by an octave and speed up the sound, -1 will lower the sound by an octave and slow it down.
> ``` lang=cpp, name=Nada
> var Pitch : Real


---  
 #  PitchWithTimeSpace : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> If true, the audio in the SoundSpace will be pitched according to the TimeScale of the Space(if time slows down the audio will slow down and lower in pitch, if it speeds up the audio will speed up and raise in pitch).
> ``` lang=cpp, name=Nada
> var PitchWithTimeSpace : Boolean


---  
 #  Semitones : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The pitch adjustment, in semitones (or half-steps), applied to all sounds in the space. A value of 0 will do nothing, 12 will raise the pitch by an octave and speed up the sound,.
> ``` lang=cpp, name=Nada
> var Semitones : Real


---  
 #  SoundNodeInput : [soundnode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundnode.markdown)

 `read-only`

> The SoundNode which is the ultimate output of all sounds in this space.
> ``` lang=cpp, name=Nada
> var SoundNodeInput : SoundNode


---  
 #  SoundNodeOutput : [soundnode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundnode.markdown)

 `read-only`

> The SoundNode which can be used to attach other nodes which should process all audio in the SoundSpace.
> ``` lang=cpp, name=Nada
> var SoundNodeOutput : SoundNode


---  
 #  Volume : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The volume adjustment applied to all sounds in the space. A value of 1 does nothing, 2 will double the volume, 0.5 will halve it.
> ``` lang=cpp, name=Nada
> var Volume : Real


---  
 #  Methods


---  
 #  InterpolateDecibels : Void

> Interpolates the SoundSpace's Decibels property from its current value to the value passed in as the first parameter, over the number of seconds passed in as the second parameter.
> |Name|Type|Description|
> |---|---|---|
> |decibels|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |interpolationTime|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function InterpolateDecibels(decibels : Real, interpolationTime : Real)
> ``` 


---  
 #  InterpolatePitch : Void

> Interpolates the SoundSpace's Pitch property from its current value to the value passed in as the first parameter, over the number of seconds passed in as the second parameter.
> |Name|Type|Description|
> |---|---|---|
> |pitch|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |time|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function InterpolatePitch(pitch : Real, time : Real)
> ``` 


---  
 #  InterpolateSemitones : Void

> Interpolates the SoundSpace's Semitones property from its current value to the value passed in as the first parameter, over the number of seconds passed in as the second parameter.
> |Name|Type|Description|
> |---|---|---|
> |pitch|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |time|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function InterpolateSemitones(pitch : Real, time : Real)
> ``` 


---  
 #  InterpolateVolume : Void

> Interpolates the SoundSpace's Volume property from its current value to the value passed in as the first parameter, over the number of seconds passed in as the second parameter.
> |Name|Type|Description|
> |---|---|---|
> |value|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |interpolationTime|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function InterpolateVolume(value : Real, interpolationTime : Real)
> ``` 


---  
 #  PlayCue : [soundinstance](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundinstance.markdown)

> Plays the passed-in SoundCue non-positionally and returns the resulting SoundInstance.
> |Name|Type|Description|
> |---|---|---|
> |cue|[soundcue](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundcue.markdown)| |
> ``` lang=cpp, name=Nada
> function PlayCue(cue : SoundCue) : SoundInstance
> ``` 


---  
 #  PlayCuePaused : [soundinstance](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundinstance.markdown)

> Plays the passed-in SoundCue non-positionally and returns the resulting SoundInstance, which starts off paused.
> |Name|Type|Description|
> |---|---|---|
> |cue|[soundcue](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundcue.markdown)| |
> ``` lang=cpp, name=Nada
> function PlayCuePaused(cue : SoundCue) : SoundInstance
> ``` 


---  
 #  SoundSpace : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function SoundSpace()
> ``` 


---  
 

 