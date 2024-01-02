 `Physics`

(NOTE) A block of information for solving a joint (or constraint) type. This is used to configure how one joint is solved independently of another joint.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
| |[ AngularBaumgarte](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/constraintconfigblock.markdown#angularbaumgarte-zilch-en)|[safeid32object](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/safeid32object.markdown)|[contactblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/contactblock.markdown)|
| |[ AngularErrorCorrection](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/constraintconfigblock.markdown#angularerrorcorrection-z)| |[customjointblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/customjointblock.markdown)|
| |[ LinearBaumgarte](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/constraintconfigblock.markdown#linearbaumgarte-zilch-eng)| |[fixedanglejointblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/fixedanglejointblock.markdown)|
| |[ LinearErrorCorrection](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/constraintconfigblock.markdown#linearerrorcorrection-ze)| |[gearjointblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gearjointblock.markdown)|
| |[ PositionCorrectionType](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/constraintconfigblock.markdown#positioncorrectiontype-z)| |[linearaxisjointblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/linearaxisjointblock.markdown)|
| |[ Slop](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/constraintconfigblock.markdown#slop-zilch-engine-documen)| |[manipulatorjointblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/manipulatorjointblock.markdown)|
| | | |[phygunjointblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/phygunjointblock.markdown)|
| | | |[positionjointblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/positionjointblock.markdown)|
| | | |[prismaticjoint2dblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/prismaticjoint2dblock.markdown)|
| | | |[prismaticjointblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/prismaticjointblock.markdown)|
| | | |[pulleyjointblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/pulleyjointblock.markdown)|
| | | |[relativevelocityjointblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/relativevelocityjointblock.markdown)|
| | | |[revolutejoint2dblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/revolutejoint2dblock.markdown)|
| | | |[revolutejointblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/revolutejointblock.markdown)|
| | | |[stickjointblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/stickjointblock.markdown)|
| | | |[universaljointblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/universaljointblock.markdown)|
| | | |[uprightjointblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uprightjointblock.markdown)|
| | | |[weldjointblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/weldjointblock.markdown)|
| | | |[wheeljoint2dblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/wheeljoint2dblock.markdown)|
| | | |[wheeljointblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/wheeljointblock.markdown)|


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

> What method should be used to fix errors in joints.
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
 

 