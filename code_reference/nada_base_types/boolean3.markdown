 `Core`

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean3.markdown#boolean3-void)|[ Count](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean3.markdown#count-zilch-engine-docume)| | |
|[ Get](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean3.markdown#get-zilch-engine-document)|[ One](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean3.markdown#one-zilch-engine-document)| | |
|[ GetAxis](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean3.markdown#getaxis-zilch-engine-docu)|[ XAxis](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean3.markdown#xaxis-zilch-engine-docume)| | |
|[ Set](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean3.markdown#set-void)|[ YAxis](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean3.markdown#yaxis-zilch-engine-docume)| | |
| |[ ZAxis](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean3.markdown#zaxis-zilch-engine-docume)| | |
| |[ Zero](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean3.markdown#zilch-zilch-engine-documen)| | |


 #  Properties


---  
 #  Count : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Count : Integer


---  
 #  One : [boolean3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean3.markdown)

 `read-only` `static`

> The one vector (a vector containing all ones).
> ``` lang=cpp, name=Nada
> var One : Boolean3


---  
 #  XAxis : [boolean3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean3.markdown)

 `read-only` `static`

> 
> ``` lang=cpp, name=Nada
> var XAxis : Boolean3


---  
 #  YAxis : [boolean3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean3.markdown)

 `read-only` `static`

> 
> ``` lang=cpp, name=Nada
> var YAxis : Boolean3


---  
 #  ZAxis : [boolean3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean3.markdown)

 `read-only` `static`

> 
> ``` lang=cpp, name=Nada
> var ZAxis : Boolean3


---  
 #  Zero : [boolean3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean3.markdown)

 `read-only` `static`

> The zero vector (a vector containing all zeroes).
> ``` lang=cpp, name=Nada
> var Zero : Boolean3


---  
 #  Methods


---  
 #  Boolean3 : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Boolean3()
> ``` 


---  
 #  Boolean3 : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |scalar|[boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)| |
> ``` lang=cpp, name=Nada
> function Boolean3(scalar : Boolean)
> ``` 


---  
 #  Boolean3 : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)| |
> |p1|[boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)| |
> |p2|[boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)| |
> ``` lang=cpp, name=Nada
> function Boolean3(p0 : Boolean, p1 : Boolean, p2 : Boolean)
> ``` 


---  
 #  Boolean3 : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)| |
> |p1|[boolean2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean2.markdown)| |
> ``` lang=cpp, name=Nada
> function Boolean3(p0 : Boolean, p1 : Boolean2)
> ``` 


---  
 #  Boolean3 : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[boolean2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean2.markdown)| |
> |p1|[boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)| |
> ``` lang=cpp, name=Nada
> function Boolean3(p0 : Boolean2, p1 : Boolean)
> ``` 


---  
 #  Get : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function Get(p0 : Integer) : Boolean
> ``` 


---  
 #  GetAxis : [boolean3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean3.markdown)

 `static`

> Returns an axis vector from the given index (ie. 0 is XAxis, 1 is YAxis, etc...
> |Name|Type|Description|
> |---|---|---|
> |p0|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function GetAxis(p0 : Integer) : Boolean3
> ``` 


---  
 #  Set : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> |p1|[boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)| |
> ``` lang=cpp, name=Nada
> function Set(p0 : Integer, p1 : Boolean)
> ``` 


---  
 

 