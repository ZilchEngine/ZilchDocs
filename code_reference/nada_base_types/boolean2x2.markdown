 `Core`

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean2x2.markdown#boolean2x2-void)|[ Count](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean2x2.markdown#count-zilch-engine-docume)| | |
|[ Get](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean2x2.markdown#get-zilch-engine-document)|[ CountX](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean2x2.markdown#countx-zilch-engine-docum)| | |
|[ GetByIndex](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean2x2.markdown#getbyindex-zilch-engine-d)|[ CountY](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean2x2.markdown#county-zilch-engine-docum)| | |
|[ Set](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean2x2.markdown#set-void)|[ M00](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean2x2.markdown#m00-zilch-engine-document)| | |
|[ SetByIndex](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean2x2.markdown#setbyindex-void)|[ M01](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean2x2.markdown#m01-zilch-engine-document)| | |
| |[ M10](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean2x2.markdown#m10-zilch-engine-document)| | |
| |[ M11](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean2x2.markdown#m11-zilch-engine-document)| | |


 #  Properties


---  
 #  Count : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Count : Integer


---  
 #  CountX : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var CountX : Integer


---  
 #  CountY : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var CountY : Integer


---  
 #  M00 : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var M00 : Boolean


---  
 #  M01 : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var M01 : Boolean


---  
 #  M10 : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var M10 : Boolean


---  
 #  M11 : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var M11 : Boolean


---  
 #  Methods


---  
 #  Boolean2x2 : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Boolean2x2()
> ``` 


---  
 #  Boolean2x2 : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)| |
> ``` lang=cpp, name=Nada
> function Boolean2x2(p0 : Boolean)
> ``` 


---  
 #  Boolean2x2 : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |m00|[boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)| |
> |m01|[boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)| |
> |m10|[boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)| |
> |m11|[boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)| |
> ``` lang=cpp, name=Nada
> function Boolean2x2(m00 : Boolean, m01 : Boolean, m10 : Boolean, m11 : Boolean)
> ``` 


---  
 #  Get : [boolean2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean2.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |y|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function Get(y : Integer) : Boolean2
> ``` 


---  
 #  Get : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |y|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> |x|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function Get(y : Integer, x : Integer) : Boolean
> ``` 


---  
 #  GetByIndex : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |index|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function GetByIndex(index : Integer) : Boolean
> ``` 


---  
 #  Set : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |y|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> |value|[boolean2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean2.markdown)| |
> ``` lang=cpp, name=Nada
> function Set(y : Integer, value : Boolean2)
> ``` 


---  
 #  Set : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |y|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> |x|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> |value|[boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)| |
> ``` lang=cpp, name=Nada
> function Set(y : Integer, x : Integer, value : Boolean)
> ``` 


---  
 #  SetByIndex : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |index|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> |value|[boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)| |
> ``` lang=cpp, name=Nada
> function SetByIndex(index : Integer, value : Boolean)
> ``` 


---  
 

 