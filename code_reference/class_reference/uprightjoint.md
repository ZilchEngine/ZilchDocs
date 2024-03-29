 `Component` `Physics`



(NOTE) A joint to keep an object upright. Locks two axes of the objects together but allows free rotation on the plane defined by that axis. This constraint is useful for keeping any object upright. This could also be used to auto correct an object slowly by lowering the max impulse value of the constraint.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uprightjoint.md#uprightjoint-void)|[ LocalAxisA](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uprightjoint.md#localaxisa-zilch-engine-d)|[joint](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/joint.md)| |
| |[ LocalAxisB](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uprightjoint.md#localaxisb-zilch-engine-d)| | |
| |[ WorldAxis](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uprightjoint.md#worldaxis-zilch-engine-do)| | |


 #  Properties


---  
 #  LocalAxisA : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.md)

> The locally defined axis on object A . 
> ``` lang=cpp, name=Nada
> var LocalAxisA : Real3


---  
 #  LocalAxisB : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.md)

> The locally defined axis on object B . 
> ``` lang=cpp, name=Nada
> var LocalAxisB : Real3


---  
 #  WorldAxis : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.md)

> The axis in world space that is being rotated about . 
> ``` lang=cpp, name=Nada
> var WorldAxis : Real3


---  
 #  Methods


---  
 #  UprightJoint : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function UprightJoint()
> ``` 


---  
 

 