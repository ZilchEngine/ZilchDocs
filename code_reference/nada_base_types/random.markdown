 `Core`

(NOTE) Contains utility functions for random generation.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ BellCurve](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#bellcurve-zilch-engine-do)|[ MaxInteger](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#maxinteger-zilch-engine-d)| | |
|[ Boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#boolean-zilch-engine-docu)|[ Seed](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#seed-zilch-engine-documen)| | |
|[ CoinFlip](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#coinflip-zilch-engine-doc)| | | |
|[ DieRoll](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#dieroll-zilch-engine-docu)| | | |
|[ DoubleRange](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#doublerange-zilch-engine)| | | |
|[ DoubleReal](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#doublereal-zilch-engine-d)| | | |
|[ Integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#integer-zilch-engine-docu)| | | |
|[ Probability](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#probability-zilch-engine)| | | |
|[ Quaternion](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#quaternion-zilch-engine-d)| | | |
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#random-void)| | | |
|[ Range](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#range-zilch-engine-docume)| | | |
|[ RangeExclusiveMax](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#rangeexclusivemax-zilch-e)| | | |
|[ RangeInclusiveMax](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#rangeinclusivemax-zilch-e)| | | |
|[ Real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#real-zilch-engine-documen)| | | |
|[ Real2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#real2-zilch-engine-docume)| | | |
|[ Real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#real3-zilch-engine-docume)| | | |
|[ Rotation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#rotation-zilch-engine-doc)| | | |
|[ UnitReal2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#unitreal2-zilch-engine-do)| | | |
|[ UnitReal3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#unitreal3-zilch-engine-do)| | | |
|[ Variance](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/random.markdown#variance-zilch-engine-doc)| | | |


 #  Properties


---  
 #  MaxInteger : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only` `static`

> Returns the max integer value that can be returned.
> ``` lang=cpp, name=Nada
> var MaxInteger : Integer


---  
 #  Seed : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

> The seed controls what random numbers are generated in a sequence (determanistically) The same seed will always generate the same string of random numbers.
> ``` lang=cpp, name=Nada
> var Seed : Integer


---  
 #  Methods


---  
 #  BellCurve : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> Samples a bell curve with standard normal distribution in the range [0,1] This is equivalent to a Gaussian distribution with standard deviation of 1.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function BellCurve() : Real
> ``` 


---  
 #  BellCurve : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> Samples a bell curve with in the range [center - range, center + range] This uses a standard deviation of 1.
> |Name|Type|Description|
> |---|---|---|
> |center|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |range|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function BellCurve(center : Real, range : Real) : Real
> ``` 


---  
 #  BellCurve : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> Samples a bell curve in the range [center - range, center + range] with the given standard deviation. Around 68% will lie within the 1st standard deviation.
> |Name|Type|Description|
> |---|---|---|
> |center|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |range|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |standardDeviation|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function BellCurve(center : Real, range : Real, standardDeviation : Real) : Real
> ``` 


---  
 #  Boolean : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Returns a random boolean value.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Boolean() : Boolean
> ``` 


---  
 #  CoinFlip : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Returns true if the coin flips heads.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function CoinFlip() : Boolean
> ``` 


---  
 #  DieRoll : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

> Randomly rolls a number in the range [1, sides].
> |Name|Type|Description|
> |---|---|---|
> |sides|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function DieRoll(sides : Integer) : Integer
> ``` 


---  
 #  DoubleRange : [doublereal](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/doublereal.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> ||[doublereal](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/doublereal.markdown)| |
> ||[doublereal](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/doublereal.markdown)| |
> ``` lang=cpp, name=Nada
> function DoubleRange( : DoubleReal,  : DoubleReal) : DoubleReal
> ``` 


---  
 #  DoubleReal : [doublereal](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/doublereal.markdown)

> Returns a random double real in the range [0,1].
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function DoubleReal() : DoubleReal
> ``` 


---  
 #  Integer : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

> Returns a random integer in the range of [0, MaxInt].
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Integer() : Integer
> ``` 


---  
 #  Probability : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Takes a given probability that we get a true value.
> |Name|Type|Description|
> |---|---|---|
> |probOfTrue|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function Probability(probOfTrue : Real) : Boolean
> ``` 


---  
 #  Quaternion : [quaternion](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/quaternion.markdown)

> Random unit length quaternion. This is also a unit quaternion.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Quaternion() : Quaternion
> ``` 


---  
 #  Random : Void

 `constructor`

> Default constructor (grabs the random seed)
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Random()
> ``` 


---  
 #  Random : Void

 `constructor`

> Construct a random generator with a specific seed.
> |Name|Type|Description|
> |---|---|---|
> |seed|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function Random(seed : Integer)
> ``` 


---  
 #  Range : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> A random Real in the range [min,max].
> |Name|Type|Description|
> |---|---|---|
> |min|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |max|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function Range(min : Real, max : Real) : Real
> ``` 


---  
 #  RangeExclusiveMax : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

> Integer in the range [min, max].
> |Name|Type|Description|
> |---|---|---|
> |min|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> |max|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function RangeExclusiveMax(min : Integer, max : Integer) : Integer
> ``` 


---  
 #  RangeInclusiveMax : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

> Integer in the range [min, max)
> |Name|Type|Description|
> |---|---|---|
> |min|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> |max|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function RangeInclusiveMax(min : Integer, max : Integer) : Integer
> ``` 


---  
 #  Real : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> Returns a random real in the range [0,1].
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Real() : Real
> ``` 


---  
 #  Real2 : [real2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real2.markdown)

> Randomly generates a Real2 with its length between min and max.
> |Name|Type|Description|
> |---|---|---|
> |minLength|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |maxLength|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function Real2(minLength : Real, maxLength : Real) : Real2
> ``` 


---  
 #  Real3 : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Randomly generates a Real3 with its length between min and max.
> |Name|Type|Description|
> |---|---|---|
> |minLength|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |maxLength|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function Real3(minLength : Real, maxLength : Real) : Real3
> ``` 


---  
 #  Rotation : [quaternion](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/quaternion.markdown)

> Random rotation quaternion. This is the same as calling Quaternion()
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Rotation() : Quaternion
> ``` 


---  
 #  UnitReal2 : [real2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real2.markdown)

> Generates a unit length Real2.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function UnitReal2() : Real2
> ``` 


---  
 #  UnitReal3 : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Generates a unit length Real3.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function UnitReal3() : Real3
> ``` 


---  
 #  Variance : [doublereal](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/doublereal.markdown)

> Integer in the range [base - variance, base + variance].
> |Name|Type|Description|
> |---|---|---|
> ||[doublereal](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/doublereal.markdown)| |
> ||[doublereal](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/doublereal.markdown)| |
> ``` lang=cpp, name=Nada
> function Variance( : DoubleReal,  : DoubleReal) : DoubleReal
> ``` 


---  
 #  Variance : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

> Integer in the range [base - variance, base + variance].
> |Name|Type|Description|
> |---|---|---|
> |base|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> |variance|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function Variance(base : Integer, variance : Integer) : Integer
> ``` 


---  
 #  Variance : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> Returns a number in the range [base - variance, base + variance].
> |Name|Type|Description|
> |---|---|---|
> |base|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |variance|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function Variance(base : Real, variance : Real) : Real
> ``` 


---  
 

 