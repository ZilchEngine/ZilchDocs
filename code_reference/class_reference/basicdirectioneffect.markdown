 `Component` `Physics`



(NOTE) Common interface for all directional force effects. Used to group together all common logic/variables for the force/gravity variants.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
| |[ Direction](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/basicdirectioneffect.markdown#direction-zilch-engine-do)|[physicseffect](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/physicseffect.markdown)|[forceeffect](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/forceeffect.markdown)|
| |[ LocalSpaceDirection](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/basicdirectioneffect.markdown#localspacedirection-zero)| |[gravityeffect](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gravityeffect.markdown)|
| |[ Strength](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/basicdirectioneffect.markdown#strength-zilch-engine-doc)| | |
| |[ WorldDirection](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/basicdirectioneffect.markdown#worlddirection-zilch-engi)| | |


 #  Properties


---  
 #  Direction : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> The direction that the effect will be applied in (may be in local or world space depending on the LocalSpaceDirection property).
> ``` lang=cpp, name=Nada
> var Direction : Real3


---  
 #  LocalSpaceDirection : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Determines if the direction that the effect is applied is in local or world space. This vector is normalized when calculating forces.
> ``` lang=cpp, name=Nada
> var LocalSpaceDirection : Boolean


---  
 #  Strength : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The magnitude of the force to apply.
> ``` lang=cpp, name=Nada
> var Strength : Real


---  
 #  WorldDirection : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

 `read-only`

> The world direction of the effect. If the effect is not in local space then this is the same as Direction.
> ``` lang=cpp, name=Nada
> var WorldDirection : Real3


---  
 #  Methods


---  
 

 