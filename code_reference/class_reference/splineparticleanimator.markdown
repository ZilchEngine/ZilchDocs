 `Component` `Gameplay`



|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/splineparticleanimator.markdown#splineparticleanimator-v)|[ AutoCalculateLifetime](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/splineparticleanimator.markdown#autocalculatelifetime-ze)|[particleanimator](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleanimator.markdown)| |
| |[ Helix](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/splineparticleanimator.markdown#helix-zilch-engine-docume)| | |
| |[ HelixOffset](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/splineparticleanimator.markdown#helixoffset-zilch-engine)| | |
| |[ HelixRadius](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/splineparticleanimator.markdown#helixradius-zilch-engine)| | |
| |[ HelixWaveLength](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/splineparticleanimator.markdown#helixwavelength-zilch-eng)| | |
| |[ Mode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/splineparticleanimator.markdown#mode-zilch-engine-documen)| | |
| |[ Speed](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/splineparticleanimator.markdown#speed-zilch-engine-docume)| | |
| |[ SpringDampingRatio](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/splineparticleanimator.markdown#springdampingratio-zero)| | |
| |[ SpringFrequencyHz](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/splineparticleanimator.markdown#springfrequencyhz-zilch-e)| | |


 #  Properties


---  
 #  AutoCalculateLifetime : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> If checked, the lifetime on the SplineParticleEmitter will be updated to the time it would take to travel the entire path at the current speed.
> ``` lang=cpp, name=Nada
> var AutoCalculateLifetime : Boolean


---  
 #  Helix : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var Helix : Boolean


---  
 #  HelixOffset : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> Offset in radians for where the helix starts.
> ``` lang=cpp, name=Nada
> var HelixOffset : Real


---  
 #  HelixRadius : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The radius of the helix.
> ``` lang=cpp, name=Nada
> var HelixRadius : Real


---  
 #  HelixWaveLength : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> How fast the helix rotates in radians / second.
> ``` lang=cpp, name=Nada
> var HelixWaveLength : Real


---  
 #  Mode : [SplineAnimatorMode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/enum_reference.markdown#splineanimatormode)

> The current animate mode.
> ``` lang=cpp, name=Nada
> var Mode : SplineAnimatorMode


---  
 #  Speed : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The speed at which the particles move in meters / second.
> ``` lang=cpp, name=Nada
> var Speed : Real


---  
 #  SpringDampingRatio : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> 
> ``` lang=cpp, name=Nada
> var SpringDampingRatio : Real


---  
 #  SpringFrequencyHz : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> Spring properties.
> ``` lang=cpp, name=Nada
> var SpringFrequencyHz : Real


---  
 #  Methods


---  
 #  SplineParticleAnimator : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function SplineParticleAnimator()
> ``` 


---  
 

 