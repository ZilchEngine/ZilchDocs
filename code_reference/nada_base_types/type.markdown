 `Core`

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ IsA](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/type.markdown#isa-zilch-engine-document)|[ IsAny](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/type.markdown#isany-zilch-engine-docume)|[reflectionobject](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/reflectionobject.markdown)|[anytype](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/anytype.markdown)|
|[ IsCastableTo](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/type.markdown#iscastableto-zilch-engine)|[ IsDelegate](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/type.markdown#isdelegate-zilch-engine-d)| |[boundtype](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boundtype.markdown)|
|[ IsRawCastableTo](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/type.markdown#israwcastableto-zilch-eng)|[ IsEnum](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/type.markdown#isenum-zilch-engine-docum)| |[delegatetype](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/delegatetype.markdown)|
| |[ IsEnumOrFlags](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/type.markdown#isenumorflags-zilch-engin)| |[indirectiontype](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/indirectiontype.markdown)|
| |[ IsFlags](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/type.markdown#isflags-zilch-engine-docu)| | |
| |[ IsHandle](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/type.markdown#ishandle-zilch-engine-doc)| | |
| |[ IsValue](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/type.markdown#isvalue-zilch-engine-docu)| | |
| |[ Library](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/type.markdown#library-zilch-engine-docu)| | |
| |[ Name](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/type.markdown#name-zilch-engine-documen)| | |


 #  Properties


---  
 #  IsAny : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var IsAny : Boolean


---  
 #  IsDelegate : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var IsDelegate : Boolean


---  
 #  IsEnum : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var IsEnum : Boolean


---  
 #  IsEnumOrFlags : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var IsEnumOrFlags : Boolean


---  
 #  IsFlags : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var IsFlags : Boolean


---  
 #  IsHandle : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var IsHandle : Boolean


---  
 #  IsValue : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var IsValue : Boolean


---  
 #  Library : [library](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/library.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Library : Library


---  
 #  Name : [string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Name : String


---  
 #  Methods


---  
 #  IsA : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |baseType|[type](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/type.markdown)| |
> ``` lang=cpp, name=Nada
> function IsA(baseType : Type) : Boolean
> ``` 


---  
 #  IsCastableTo : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |toType|[type](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/type.markdown)| |
> ``` lang=cpp, name=Nada
> function IsCastableTo(toType : Type) : Boolean
> ``` 


---  
 #  IsRawCastableTo : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |toType|[type](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/type.markdown)| |
> ``` lang=cpp, name=Nada
> function IsRawCastableTo(toType : Type) : Boolean
> ``` 


---  
 

 