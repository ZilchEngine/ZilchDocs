 `Geometry`

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ GetPoint](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/segment.markdown#getpoint-zero-engine-doc)|[ End](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/segment.markdown#end-zero-engine-document)| | |
|[ GetTValue](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/segment.markdown#gettvalue-zero-engine-do)|[ Start](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/segment.markdown#start-zero-engine-docume)| | |
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/segment.markdown#segment-void)| | | |


 #  Properties


---  
 #  End : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> 
> ``` lang=cpp, name=Nada
> var End : Real3


---  
 #  Start : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> 
> ``` lang=cpp, name=Nada
> var Start : Real3


---  
 #  Methods


---  
 #  GetPoint : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Returns the point at the given t-value.
> |Name|Type|Description|
> |---|---|---|
> |tValue|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function GetPoint(tValue : Real) : Real3
> ``` 


---  
 #  GetTValue : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> Returns the t-value that would result in the given point projected onto the segment.
> |Name|Type|Description|
> |---|---|---|
> |point|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> ``` lang=cpp, name=Nada
> function GetTValue(point : Real3) : Real
> ``` 


---  
 #  Segment : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Segment()
> ``` 


---  
 #  Segment : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |start|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> |end|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> ``` lang=cpp, name=Nada
> function Segment(start : Real3, end : Real3)
> ``` 


---  
 #  Segment : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[segment](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/segment.markdown)| |
> ``` lang=cpp, name=Nada
> function Segment(p0 : Segment)
> ``` 


---  
 

 