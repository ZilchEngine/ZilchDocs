 `Geometry`

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugobb.markdown#debugobb-void)|[ Color](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugobb.markdown#color-zilch-engine-docume)| | |
| |[ Corners](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugobb.markdown#corners-zilch-engine-docu)| | |
| |[ Filled](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugobb.markdown#filled-zilch-engine-docum)| | |
| |[ HalfExtents](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugobb.markdown#halfextents-zilch-engine)| | |
| |[ OnTop](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugobb.markdown#ontop-zilch-engine-docume)| | |
| |[ Position](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugobb.markdown#position-zilch-engine-doc)| | |
| |[ Rotation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugobb.markdown#rotation-zilch-engine-doc)| | |
| |[ ViewAligned](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugobb.markdown#viewaligned-zilch-engine)| | |
| |[ ViewScaled](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugobb.markdown#viewscaled-zilch-engine-d)| | |
| |[ ViewScaleOffset](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugobb.markdown#viewscaleoffset-zilch-eng)| | |


 #  Properties


---  
 #  Color : [real4](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real4.markdown)

> 
> ``` lang=cpp, name=Nada
> var Color : Real4


---  
 #  Corners : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var Corners : Boolean


---  
 #  Filled : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var Filled : Boolean


---  
 #  HalfExtents : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> 
> ``` lang=cpp, name=Nada
> var HalfExtents : Real3


---  
 #  OnTop : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var OnTop : Boolean


---  
 #  Position : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> 
> ``` lang=cpp, name=Nada
> var Position : Real3


---  
 #  Rotation : [quaternion](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/quaternion.markdown)

> 
> ``` lang=cpp, name=Nada
> var Rotation : Quaternion


---  
 #  ViewAligned : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var ViewAligned : Boolean


---  
 #  ViewScaled : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var ViewScaled : Boolean


---  
 #  ViewScaleOffset : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> 
> ``` lang=cpp, name=Nada
> var ViewScaleOffset : Real3


---  
 #  Methods


---  
 #  DebugObb : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function DebugObb()
> ``` 


---  
 #  DebugObb : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |aabb|[aabb](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/aabb.markdown)| |
> ``` lang=cpp, name=Nada
> function DebugObb(aabb : Aabb)
> ``` 


---  
 #  DebugObb : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |position|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> |halfExtents|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function DebugObb(position : Real3, halfExtents : Real)
> ``` 


---  
 #  DebugObb : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |position|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> |halfExtents|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |rotation|[quaternion](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/quaternion.markdown)| |
> ``` lang=cpp, name=Nada
> function DebugObb(position : Real3, halfExtents : Real, rotation : Quaternion)
> ``` 


---  
 #  DebugObb : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |position|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> |halfExtents|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> ``` lang=cpp, name=Nada
> function DebugObb(position : Real3, halfExtents : Real3)
> ``` 


---  
 #  DebugObb : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |position|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> |halfExtents|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> |rotation|[quaternion](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/quaternion.markdown)| |
> ``` lang=cpp, name=Nada
> function DebugObb(position : Real3, halfExtents : Real3, rotation : Quaternion)
> ``` 


---  
 #  DebugObb : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |position|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> |halfExtents|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> |rotation|[real3x3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3x3.markdown)| |
> ``` lang=cpp, name=Nada
> function DebugObb(position : Real3, halfExtents : Real3, rotation : Real3x3)
> ``` 


---  
 

 