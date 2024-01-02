 `Component` `Graphics`



(NOTE) Particle Emitter Shared.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ ResetCount](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#resetcount-void)|[ Active](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#active-zilch-engine-docum)|[particleemitter](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemitter.markdown)|[boxparticleemitter](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/boxparticleemitter.markdown)|
| |[ EmitCount](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#emitcount-zilch-engine-do)| |[meshparticleemitter](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/meshparticleemitter.markdown)|
| |[ EmitDelay](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#emitdelay-zilch-engine-do)| |[sphericalparticleemitter](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/sphericalparticleemitter.markdown)|
| |[ EmitRate](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#emitrate-zilch-engine-doc)| |[splineparticleemitter](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/splineparticleemitter.markdown)|
| |[ EmitRateSoftStartTime](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#emitratesoftstarttime-ze)| | |
| |[ EmitterSize](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#emittersize-zilch-engine)| | |
| |[ EmitterVelocityPercent](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#emittervelocitypercent-z)| | |
| |[ EmitVariance](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#emitvariance-zilch-engine)| | |
| |[ FastMovingEmitter](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#fastmovingemitter-zilch-e)| | |
| |[ Fill](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#fill-zilch-engine-documen)| | |
| |[ Lifetime](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#lifetime-zilch-engine-doc)| | |
| |[ LifetimeVariance](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#lifetimevariance-zilch-en)| | |
| |[ RandomSpin](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#randomspin-zilch-engine-d)| | |
| |[ RandomVelocity](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#randomvelocity-zilch-engi)| | |
| |[ Size](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#size-zilch-engine-documen)| | |
| |[ SizeVariance](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#sizevariance-zilch-engine)| | |
| |[ Spin](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#spin-zilch-engine-documen)| | |
| |[ SpinVariance](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#spinvariance-zilch-engine)| | |
| |[ StartVelocity](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#startvelocity-zilch-engin)| | |
| |[ TangentVelocity](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particleemittershared.markdown#tangentvelocity-zilch-eng)| | |


 #  Properties


---  
 #  Active : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Is this emitter currently emitting particles?
> ``` lang=cpp, name=Nada
> var Active : Boolean


---  
 #  EmitCount : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

> Number of particles to emit per reset.
> ``` lang=cpp, name=Nada
> var EmitCount : Integer


---  
 #  EmitDelay : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> Time in seconds to delay the emission of particles from time of creation.
> ``` lang=cpp, name=Nada
> var EmitDelay : Real


---  
 #  EmitRate : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> Rate that particles spawn per second.
> ``` lang=cpp, name=Nada
> var EmitRate : Real


---  
 #  EmitRateSoftStartTime : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> Slowly ramps up to EmitRate over this time.
> ``` lang=cpp, name=Nada
> var EmitRateSoftStartTime : Real


---  
 #  EmitterSize : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Size of the emitter.
> ``` lang=cpp, name=Nada
> var EmitterSize : Real3


---  
 #  EmitterVelocityPercent : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> How much of the objects velocity is added to the particles.
> ``` lang=cpp, name=Nada
> var EmitterVelocityPercent : Real


---  
 #  EmitVariance : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> How much the emit can vary per sample.
> ``` lang=cpp, name=Nada
> var EmitVariance : Real


---  
 #  FastMovingEmitter : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Whether or not we attempt to emit along the vector between the previous position to the current position, which looks better for fast moving particle systems Note: Particle systems that teleport will emit along the teleport line.
> ``` lang=cpp, name=Nada
> var FastMovingEmitter : Boolean


---  
 #  Fill : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> How much area of the emitter to used 0 to 1.
> ``` lang=cpp, name=Nada
> var Fill : Real


---  
 #  Lifetime : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> How a particle's starting lifetime is.
> ``` lang=cpp, name=Nada
> var Lifetime : Real


---  
 #  LifetimeVariance : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> How much lifetime can vary per particle.
> ``` lang=cpp, name=Nada
> var LifetimeVariance : Real


---  
 #  RandomSpin : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Each particle should start with random spin.
> ``` lang=cpp, name=Nada
> var RandomSpin : Boolean


---  
 #  RandomVelocity : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Random Velocity per particle.
> ``` lang=cpp, name=Nada
> var RandomVelocity : Real3


---  
 #  Size : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> Size of each particle spawned.
> ``` lang=cpp, name=Nada
> var Size : Real


---  
 #  SizeVariance : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> How much the size can vary from the base size per particle.
> ``` lang=cpp, name=Nada
> var SizeVariance : Real


---  
 #  Spin : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> Speed in rads per second of the particle.
> ``` lang=cpp, name=Nada
> var Spin : Real


---  
 #  SpinVariance : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> How much spin speed can vary per particle.
> ``` lang=cpp, name=Nada
> var SpinVariance : Real


---  
 #  StartVelocity : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Velocity of each particle at start.
> ``` lang=cpp, name=Nada
> var StartVelocity : Real3


---  
 #  TangentVelocity : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Velocity of each particle in x horizontal tangent y vertical tangent and z outward tangent.
> ``` lang=cpp, name=Nada
> var TangentVelocity : Real3


---  
 #  Methods


---  
 #  ResetCount : Void

> Reset the number of particles to emit back to EmitCount.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function ResetCount()
> ``` 


---  
 

 