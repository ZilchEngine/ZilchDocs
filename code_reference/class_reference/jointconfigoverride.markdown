 `Component` `Physics`



(NOTE) Overrides a joint's configuration values of slop, linear/angular Baumgarte, and linear/angular error correction. Slop is the amount of error allowed before position correction takes effect. Baumgarte is used to correct error with a penalty impulse. Baumgarte is split into linear and angular portions because of stability. Error correction is only used when the joint is solved with post stabilization.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/jointconfigoverride.markdown#jointconfigoverride-void)|[ AngularBaumgarte](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/jointconfigoverride.markdown#angularbaumgarte-zero-en)|[component](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/component.markdown)| |
| |[ AngularErrorCorrection](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/jointconfigoverride.markdown#angularerrorcorrection-z)| | |
| |[ LinearBaumgarte](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/jointconfigoverride.markdown#linearbaumgarte-zero-eng)| | |
| |[ LinearErrorCorrection](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/jointconfigoverride.markdown#linearerrorcorrection-ze)| | |
| |[ PositionCorrectionType](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/jointconfigoverride.markdown#positioncorrectiontype-z)| | |
| |[ Slop](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/jointconfigoverride.markdown#slop-zero-engine-documen)| | |


 #  Properties


---  
 #  AngularBaumgarte : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The exponential constant for correcting angular error with a penalty impulse.
> ``` lang=cpp, name=Nada
> var AngularBaumgarte : Real


---  
 #  AngularErrorCorrection : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The max amount of error that can be corrected by the angular portion of any constraint in one frame (only for PostStabilization).
> ``` lang=cpp, name=Nada
> var AngularErrorCorrection : Real


---  
 #  LinearBaumgarte : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The exponential constant for correcting linear error with a penalty impulse.
> ``` lang=cpp, name=Nada
> var LinearBaumgarte : Real


---  
 #  LinearErrorCorrection : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The max amount of error that can be corrected by the linear portion of any constraint in one frame (only for PostStabilization).
> ``` lang=cpp, name=Nada
> var LinearErrorCorrection : Real


---  
 #  PositionCorrectionType : [ConstraintPositionCorrection](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/enum_reference.markdown#constraintpositioncorrection)

> The kind of position correction that this joint should use.
> ``` lang=cpp, name=Nada
> var PositionCorrectionType : ConstraintPositionCorrection


---  
 #  Slop : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The amount of error allowed before position correction takes effect.
> ``` lang=cpp, name=Nada
> var Slop : Real


---  
 #  Methods


---  
 #  JointConfigOverride : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function JointConfigOverride()
> ``` 


---  
 

 