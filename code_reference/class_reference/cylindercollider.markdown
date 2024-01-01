 `Component` `Physics`



(NOTE) Defines the collision volume for a cylinder defined by a height and radius.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Constructor](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/cylindercollider.markdown#cylindercollider-void)|[ Direction](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/cylindercollider.markdown#direction-zero-engine-do)|[collider](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/collider.markdown)| |
| |[ Height](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/cylindercollider.markdown#height-zero-engine-docum)| | |
| |[ Radius](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/cylindercollider.markdown#radius-zero-engine-docum)| | |
| |[ WorldHeight](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/cylindercollider.markdown#worldheight-zero-engine)| | |
| |[ WorldRadius](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/cylindercollider.markdown#worldradius-zero-engine)| | |


 #  Properties


---  
 #  Direction : [AxisDirection](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/enum_reference.markdown#axisdirection)

> The direction that the height is defined along. Allows the user to change whether the cylinder's height is along the x, y, or z axis.
> ``` lang=cpp, name=Nada
> var Direction : AxisDirection


---  
 #  Height : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The local space distance from the top of the cylinder to the bottom.
> ``` lang=cpp, name=Nada
> var Height : Real


---  
 #  Radius : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The local space radius of the cylinder.
> ``` lang=cpp, name=Nada
> var Radius : Real


---  
 #  WorldHeight : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only`

> The full height of the cylinder after scale is applied.
> ``` lang=cpp, name=Nada
> var WorldHeight : Real


---  
 #  WorldRadius : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only`

> The radius of the cylinder after scale is applied.
> ``` lang=cpp, name=Nada
> var WorldRadius : Real


---  
 #  Methods


---  
 #  CylinderCollider : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function CylinderCollider()
> ``` 


---  
 

 