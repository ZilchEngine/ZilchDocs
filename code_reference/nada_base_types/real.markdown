 `Core`

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Get](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown#get-zero-engine-document)|[ Count](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown#count-zero-engine-docume)| | |
|[ GetAxis](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown#getaxis-zero-engine-docu)|[ NegativeMin](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown#negativemin-zero-engine)| | |
|[ Parse](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown#parse-zero-engine-docume)|[ NegativeValueClosestToZero](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown#negativevalueclosesttoze)| | |
|[ Constructor](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown#real-void)|[ One](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown#one-zero-engine-document)| | |
|[ Reinterpret](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown#reinterpret-zero-engine)|[ PositiveMax](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown#positivemax-zero-engine)| | |
|[ Set](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown#set-void)|[ PositiveValueClosestToZero](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown#positivevalueclosesttoze)| | |
| |[ XAxis](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown#xaxis-zero-engine-docume)| | |
| |[ Zero](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown#zero-zero-engine-documen)| | |


 #  Properties


---  
 #  Count : [integer](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Count : Integer


---  
 #  NegativeMin : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only` `static`

> The smallest (most negative) value that can be represented by a Real.
> ``` lang=cpp, name=Nada
> var NegativeMin : Real


---  
 #  NegativeValueClosestToZero : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only` `static`

> The negative value closest to zero that can be represented by a Real.
> ``` lang=cpp, name=Nada
> var NegativeValueClosestToZero : Real


---  
 #  One : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only` `static`

> The one vector (a vector containing all ones).
> ``` lang=cpp, name=Nada
> var One : Real


---  
 #  PositiveMax : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only` `static`

> The largest (most positive) value that can be represented by a Real.
> ``` lang=cpp, name=Nada
> var PositiveMax : Real


---  
 #  PositiveValueClosestToZero : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only` `static`

> The positive value closest to zero that can be represented by a Real.
> ``` lang=cpp, name=Nada
> var PositiveValueClosestToZero : Real


---  
 #  XAxis : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only` `static`

> 
> ``` lang=cpp, name=Nada
> var XAxis : Real


---  
 #  Zero : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only` `static`

> The zero vector (a vector containing all zeroes).
> ``` lang=cpp, name=Nada
> var Zero : Real


---  
 #  Methods


---  
 #  Get : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[integer](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function Get(p0 : Integer) : Real
> ``` 


---  
 #  GetAxis : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `static`

> Returns an axis vector from the given index (ie. 0 is XAxis, 1 is YAxis, etc...
> |Name|Type|Description|
> |---|---|---|
> |p0|[integer](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function GetAxis(p0 : Integer) : Real
> ``` 


---  
 #  Parse : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `static`

> Attempt to convert the given StringRange to a Real. If parsing fails 0 is returned.
> |Name|Type|Description|
> |---|---|---|
> |p0|[stringrange](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/stringrange.markdown)| |
> ``` lang=cpp, name=Nada
> function Parse(p0 : StringRange) : Real
> ``` 


---  
 #  Real : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Real()
> ``` 


---  
 #  Real : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |scalar|[real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function Real(scalar : Real)
> ``` 


---  
 #  Reinterpret : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `static`

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[integer](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function Reinterpret(p0 : Integer) : Real
> ``` 


---  
 #  Set : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[integer](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> |p1|[real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function Set(p0 : Integer, p1 : Real)
> ``` 


---  
 

 