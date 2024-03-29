 `Sound`

(NOTE) Applies a band pass filter to audio generated by its input SoundNodes (removes low and high frequencies)

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
| |[ CentralFrequency](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/bandpassnode.md#centralfrequency-zilch-en)|[soundnode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundnode.md)| |
| |[ QualityFactor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/bandpassnode.md#qualityfactor-zilch-engin)| | |


 #  Properties


---  
 #  CentralFrequency : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.md)

> The center frequency of the band. Frequencies above and below this band will be attenuated.
> ``` lang=cpp, name=Nada
> var CentralFrequency : Real


---  
 #  QualityFactor : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.md)

> The Q number of the band pass filter: higher numbers make the band smaller, while smaller numbers make it wider. The default value is 0.669.
> ``` lang=cpp, name=Nada
> var QualityFactor : Real


---  
 #  Methods


---  
 

 