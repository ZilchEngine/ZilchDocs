 `Geometry`

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/plane.markdown#plane-void)|[ Data](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/plane.markdown#data-zilch-engine-documen)| | |
|[ Set](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/plane.markdown#set-void)|[ Distance](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/plane.markdown#distance-zilch-engine-doc)| | |
| |[ Normal](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/plane.markdown#normal-zilch-engine-docum)| | |


 #  Properties


---  
 #  Data : [real4](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real4.markdown)

> 
> ``` lang=cpp, name=Nada
> var Data : Real4


---  
 #  Distance : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Distance : Real


---  
 #  Normal : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Normal : Real3


---  
 #  Methods


---  
 #  Plane : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Plane()
> ``` 


---  
 #  Plane : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[plane](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/plane.markdown)| |
> ``` lang=cpp, name=Nada
> function Plane(p0 : Plane)
> ``` 


---  
 #  Plane : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |normal|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> |point|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> ``` lang=cpp, name=Nada
> function Plane(normal : Real3, point : Real3)
> ``` 


---  
 #  Plane : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |data|[real4](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real4.markdown)| |
> ``` lang=cpp, name=Nada
> function Plane(data : Real4)
> ``` 


---  
 #  Set : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |normal|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> |point|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> ``` lang=cpp, name=Nada
> function Set(normal : Real3, point : Real3)
> ``` 


---  
 #  Set : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |data|[real4](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real4.markdown)| |
> ``` lang=cpp, name=Nada
> function Set(data : Real4)
> ``` 


---  
 

 