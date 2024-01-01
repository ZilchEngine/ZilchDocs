 `Core`

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Get](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real2x2.markdown#get-zero-engine-document)|[ Count](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real2x2.markdown#count-zero-engine-docume)| | |
|[ GetByIndex](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real2x2.markdown#getbyindex-zero-engine-d)|[ CountX](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real2x2.markdown#countx-zero-engine-docum)| | |
|[ Constructor](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real2x2.markdown#real2x2-void)|[ CountY](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real2x2.markdown#county-zero-engine-docum)| | |
|[ Set](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real2x2.markdown#set-void)|[ M00](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real2x2.markdown#m00-zero-engine-document)| | |
|[ SetByIndex](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real2x2.markdown#setbyindex-void)|[ M01](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real2x2.markdown#m01-zero-engine-document)| | |
| |[ M10](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real2x2.markdown#m10-zero-engine-document)| | |
| |[ M11](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real2x2.markdown#m11-zero-engine-document)| | |


 #  Properties


---  
 #  Count : [integer](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Count : Integer


---  
 #  CountX : [integer](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var CountX : Integer


---  
 #  CountY : [integer](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var CountY : Integer


---  
 #  M00 : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

> 
> ``` lang=cpp, name=Nada
> var M00 : Real


---  
 #  M01 : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

> 
> ``` lang=cpp, name=Nada
> var M01 : Real


---  
 #  M10 : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

> 
> ``` lang=cpp, name=Nada
> var M10 : Real


---  
 #  M11 : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

> 
> ``` lang=cpp, name=Nada
> var M11 : Real


---  
 #  Methods


---  
 #  Get : [real2](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real2.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |y|[integer](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function Get(y : Integer) : Real2
> ``` 


---  
 #  Get : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |y|[integer](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> |x|[integer](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function Get(y : Integer, x : Integer) : Real
> ``` 


---  
 #  GetByIndex : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |index|[integer](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function GetByIndex(index : Integer) : Real
> ``` 


---  
 #  Real2x2 : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Real2x2()
> ``` 


---  
 #  Real2x2 : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function Real2x2(p0 : Real)
> ``` 


---  
 #  Real2x2 : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |m00|[real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |m01|[real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |m10|[real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |m11|[real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function Real2x2(m00 : Real, m01 : Real, m10 : Real, m11 : Real)
> ``` 


---  
 #  Set : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |y|[integer](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> |x|[integer](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> |value|[real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function Set(y : Integer, x : Integer, value : Real)
> ``` 


---  
 #  Set : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |y|[integer](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> |value|[real2](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real2.markdown)| |
> ``` lang=cpp, name=Nada
> function Set(y : Integer, value : Real2)
> ``` 


---  
 #  SetByIndex : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |index|[integer](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> |value|[real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function SetByIndex(index : Integer, value : Real)
> ``` 


---  
 

 