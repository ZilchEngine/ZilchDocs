 `Resource` `Graphics`



(NOTE) A composition of shader fragments that defines a shader program that is used when rendering Graphicals.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ RuntimeClone](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/material.markdown#runtimeclone-zero-engine)|[ CompositionLabel](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/material.markdown#compositionlabel-zero-en)|[dataresource](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/dataresource.markdown)| |
| |[ ReferencedByList](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/material.markdown#referencedbylist-zero-en)| | |
| |[ RenderGroups](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/material.markdown#rendergroups-zero-engine)| | |


 #  Properties


---  
 #  CompositionLabel : [integer](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var CompositionLabel : Integer


---  
 #  ReferencedByList : [rendergrouplist](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/rendergrouplist.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var ReferencedByList : RenderGroupList


---  
 #  RenderGroups : [rendergrouplist](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/rendergrouplist.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var RenderGroups : RenderGroupList


---  
 #  Methods


---  
 #  RuntimeClone : [material](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/material.markdown)

> Creates an anonymous copy that can be independently modified, destroyed when all references are gone.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function RuntimeClone() : Material
> ``` 


---  
 

 