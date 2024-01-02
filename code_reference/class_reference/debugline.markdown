 `Geometry`

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugline.markdown#debugline-void)|[ BoxHeads](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugline.markdown#boxheads-zilch-engine-doc)| | |
| |[ Color](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugline.markdown#color-zilch-engine-docume)| | |
| |[ DualHeads](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugline.markdown#dualheads-zilch-engine-do)| | |
| |[ End](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugline.markdown#end-zilch-engine-document)| | |
| |[ Filled](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugline.markdown#filled-zilch-engine-docum)| | |
| |[ HeadSize](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugline.markdown#headsize-zilch-engine-doc)| | |
| |[ OnTop](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugline.markdown#ontop-zilch-engine-docume)| | |
| |[ Start](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugline.markdown#start-zilch-engine-docume)| | |
| |[ ViewAligned](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugline.markdown#viewaligned-zilch-engine)| | |
| |[ ViewScaled](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugline.markdown#viewscaled-zilch-engine-d)| | |
| |[ ViewScaleOffset](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debugline.markdown#viewscaleoffset-zilch-eng)| | |


 #  Properties


---  
 #  BoxHeads : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var BoxHeads : Boolean


---  
 #  Color : [real4](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real4.markdown)

> 
> ``` lang=cpp, name=Nada
> var Color : Real4


---  
 #  DualHeads : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var DualHeads : Boolean


---  
 #  End : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> 
> ``` lang=cpp, name=Nada
> var End : Real3


---  
 #  Filled : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var Filled : Boolean


---  
 #  HeadSize : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> 
> ``` lang=cpp, name=Nada
> var HeadSize : Real


---  
 #  OnTop : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var OnTop : Boolean


---  
 #  Start : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> 
> ``` lang=cpp, name=Nada
> var Start : Real3


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
 #  DebugLine : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function DebugLine()
> ``` 


---  
 #  DebugLine : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |ray|[ray](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ray.markdown)| |
> ``` lang=cpp, name=Nada
> function DebugLine(ray : Ray)
> ``` 


---  
 #  DebugLine : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |ray|[ray](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ray.markdown)| |
> |t|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function DebugLine(ray : Ray, t : Real)
> ``` 


---  
 #  DebugLine : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |start|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> |end|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> ``` lang=cpp, name=Nada
> function DebugLine(start : Real3, end : Real3)
> ``` 


---  
 #  DebugLine : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |start|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> |end|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> |headSize|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function DebugLine(start : Real3, end : Real3, headSize : Real)
> ``` 


---  
 #  DebugLine : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |segment|[segment](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/segment.markdown)| |
> ``` lang=cpp, name=Nada
> function DebugLine(segment : Segment)
> ``` 


---  
 

 