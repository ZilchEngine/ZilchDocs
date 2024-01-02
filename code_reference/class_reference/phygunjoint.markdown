 `Component` `Physics`



(NOTE) Legacy. A physics gun joint is an experimental joint for picking up objects. This acts as a weld between an object and the world. Primarily an experiment for picking up objects as a player. Should be custom implemented in script with CustomJoint instead.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/phygunjoint.markdown#phygunjoint-void)|[ LocalPoint](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/phygunjoint.markdown#localpoint-zilch-engine-d)|[joint](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/joint.markdown)| |
| |[ TargetPoint](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/phygunjoint.markdown#targetpoint-zilch-engine)| | |
| |[ TargetRotation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/phygunjoint.markdown#targetrotation-zilch-engi)| | |
| |[ WorldPoint](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/phygunjoint.markdown#worldpoint-zilch-engine-d)| | |
| |[ WorldRotation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/phygunjoint.markdown#worldrotation-zilch-engin)| | |


 #  Properties


---  
 #  LocalPoint : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> The local point on the object that should match the target point.
> ``` lang=cpp, name=Nada
> var LocalPoint : Real3


---  
 #  TargetPoint : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> The point in world space that the object's point should match.
> ``` lang=cpp, name=Nada
> var TargetPoint : Real3


---  
 #  TargetRotation : [quaternion](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/quaternion.markdown)

> The world space rotation that the basis of the object should match. Used to set the desired rotation of the object in world space.
> ``` lang=cpp, name=Nada
> var TargetRotation : Quaternion


---  
 #  WorldPoint : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> The world point on the object that should match the target point.
> ``` lang=cpp, name=Nada
> var WorldPoint : Real3


---  
 #  WorldRotation : [quaternion](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/quaternion.markdown)

> Used to set the world rotation basis of the object that should be matched to the target rotation.
> ``` lang=cpp, name=Nada
> var WorldRotation : Quaternion


---  
 #  Methods


---  
 #  PhyGunJoint : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function PhyGunJoint()
> ``` 


---  
 

 