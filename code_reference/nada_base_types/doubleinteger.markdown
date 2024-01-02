 `Core`

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Parse](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/doubleinteger.markdown#parse-zilch-engine-docume)|[ NegativeMin](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/doubleinteger.markdown#negativemin-zilch-engine)| | |
| |[ NegativeValueClosestToZero](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/doubleinteger.markdown#negativevalueclosesttoze)| | |
| |[ PositiveMax](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/doubleinteger.markdown#positivemax-zilch-engine)| | |
| |[ PositiveValueClosestToZero](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/doubleinteger.markdown#positivevalueclosesttoze)| | |


 #  Properties


---  
 #  NegativeMin : [doubleinteger](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/doubleinteger.markdown)

 `read-only` `static`

> The smallest (most negative) value that can be represented by a DoubleInteger.
> ``` lang=cpp, name=Nada
> var NegativeMin : DoubleInteger


---  
 #  NegativeValueClosestToZero : [doubleinteger](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/doubleinteger.markdown)

 `read-only` `static`

> The negative value closest to zero that can be represented by a DoubleInteger.
> ``` lang=cpp, name=Nada
> var NegativeValueClosestToZero : DoubleInteger


---  
 #  PositiveMax : [doubleinteger](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/doubleinteger.markdown)

 `read-only` `static`

> The largest (most positive) value that can be represented by a DoubleInteger.
> ``` lang=cpp, name=Nada
> var PositiveMax : DoubleInteger


---  
 #  PositiveValueClosestToZero : [doubleinteger](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/doubleinteger.markdown)

 `read-only` `static`

> The positive value closest to zero that can be represented by a DoubleInteger.
> ``` lang=cpp, name=Nada
> var PositiveValueClosestToZero : DoubleInteger


---  
 #  Methods


---  
 #  Parse : [doubleinteger](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/doubleinteger.markdown)

 `static`

> Attempt to convert the given StringRange to a DoubleInteger. If parsing fails 0 is returned.
> |Name|Type|Description|
> |---|---|---|
> |p0|[stringrange](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/stringrange.markdown)| |
> ``` lang=cpp, name=Nada
> function Parse(p0 : StringRange) : DoubleInteger
> ``` 


---  
 

 