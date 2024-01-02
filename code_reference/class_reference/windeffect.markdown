 `Component` `Physics`



(NOTE) Applies a wind force in a given direction. The wind force is calculated from the squared wind speed and is scaled by the approximate surface area of the object in the direction of the force.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/windeffect.markdown#windeffect-void)|[ LocalSpaceDirection](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/windeffect.markdown#localspacedirection-zero)|[physicseffect](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/physicseffect.markdown)| |
| |[ WindDirection](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/windeffect.markdown#winddirection-zero-engin)| | |
| |[ WindSpeed](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/windeffect.markdown#windspeed-zero-engine-do)| | |
| |[ WorldWindDirection](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/windeffect.markdown#worldwinddirection-zero)| | |


 #  Properties


---  
 #  LocalSpaceDirection : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Determines if the wind's direction is a local or world-space vector.
> ``` lang=cpp, name=Nada
> var LocalSpaceDirection : Boolean


---  
 #  WindDirection : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> The direction that the wind is blowing.
> ``` lang=cpp, name=Nada
> var WindDirection : Real3


---  
 #  WindSpeed : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The speed that the wind is blowing.
> ``` lang=cpp, name=Nada
> var WindSpeed : Real


---  
 #  WorldWindDirection : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

 `read-only`

> The direction of the wind in world space.
> ``` lang=cpp, name=Nada
> var WorldWindDirection : Real3


---  
 #  Methods


---  
 #  WindEffect : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function WindEffect()
> ``` 


---  
 

 