 `Graphics`

(NOTE) Indices used to define non-sequential primitive construction from vertices, such as shared vertices.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Add](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/indexbuffer.md#add-void)|[ Count](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/indexbuffer.md#count-zilch-engine-docume)|[safeid32](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/safeid32.md)| |
|[ Clear](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/indexbuffer.md#clear-void)| | | |
|[ Get](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/indexbuffer.md#get-zilch-engine-document)| | | |


 #  Properties


---  
 #  Count : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.md)

> Number of vertex indices currently in buffer. Can be set manually to invoke vertex shading that number of times, with or without vertex data.
> ``` lang=cpp, name=Nada
> var Count : Integer


---  
 #  Methods


---  
 #  Add : Void

> Add a vertex index to the buffer.
> |Name|Type|Description|
> |---|---|---|
> |value|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.md)| |
> ``` lang=cpp, name=Nada
> function Add(value : Integer)
> ``` 


---  
 #  Clear : Void

> Clears all stored indices so that new ones can be added.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Clear()
> ``` 


---  
 #  Get : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.md)

> Returns the vertex index that is stored at the given index of this buffer.
> |Name|Type|Description|
> |---|---|---|
> |index|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.md)| |
> ``` lang=cpp, name=Nada
> function Get(index : Integer) : Integer
> ``` 


---  
 

 