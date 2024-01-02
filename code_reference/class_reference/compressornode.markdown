 `Sound`

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
| |[ AttackMillisec](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/compressornode.markdown#attackmillisec-zilch-engi)|[soundnode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundnode.markdown)| |
| |[ InputGainDecibels](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/compressornode.markdown#inputgaindecibels-zilch-e)| | |
| |[ KneeWidth](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/compressornode.markdown#kneewidth-zilch-engine-do)| | |
| |[ OutputGainDecibels](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/compressornode.markdown#outputgaindecibels-zero)| | |
| |[ Ratio](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/compressornode.markdown#ratio-zilch-engine-docume)| | |
| |[ ReleaseMillisec](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/compressornode.markdown#releasemillisec-zilch-eng)| | |
| |[ ThresholdDecibels](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/compressornode.markdown#thresholddecibels-zilch-e)| | |


 #  Properties


---  
 #  AttackMillisec : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The time for the compressor to ramp to full effect after the input reaches the threshold.
> ``` lang=cpp, name=Nada
> var AttackMillisec : Real


---  
 #  InputGainDecibels : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The volume adjustment applied to the audio input, in decibels.
> ``` lang=cpp, name=Nada
> var InputGainDecibels : Real


---  
 #  KneeWidth : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The knee width of the compressor, in decibels.
> ``` lang=cpp, name=Nada
> var KneeWidth : Real


---  
 #  OutputGainDecibels : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The volume adjustment applied to the compressor output, in decibels.
> ``` lang=cpp, name=Nada
> var OutputGainDecibels : Real


---  
 #  Ratio : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The ratio of the volume reduction applied by the compressor.
> ``` lang=cpp, name=Nada
> var Ratio : Real


---  
 #  ReleaseMillisec : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The time for the compressor to ramp from full effect to off after the input drops below the threshold.
> ``` lang=cpp, name=Nada
> var ReleaseMillisec : Real


---  
 #  ThresholdDecibels : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The threshold, in decibels, at which the volume of the input is affected by the compressor.
> ``` lang=cpp, name=Nada
> var ThresholdDecibels : Real


---  
 #  Methods


---  
 

 