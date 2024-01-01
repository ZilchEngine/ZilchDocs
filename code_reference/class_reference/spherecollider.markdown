 `Component` `Physics`



(NOTE) Defines the collision volume for a sphere defined by a radius.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Constructor](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/spherecollider.markdown#spherecollider-void)|[ Radius](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/spherecollider.markdown#radius-zero-engine-docum)|[collider](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/collider.markdown)| |
| |[ WorldRadius](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/spherecollider.markdown#worldradius-zero-engine)| | |


 #  Properties


---  
 #  Radius : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The radius of the sphere in local space (before transform is applied).
> ``` lang=cpp, name=Nada
> var Radius : Real


---  
 #  WorldRadius : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only`

> The radius of the sphere after transform is applied (scale).
> ``` lang=cpp, name=Nada
> var WorldRadius : Real


---  
 #  Methods


---  
 #  SphereCollider : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function SphereCollider()
> ``` 


---  
 

 