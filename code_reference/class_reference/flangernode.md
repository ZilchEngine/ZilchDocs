 `Sound`

(NOTE) Applies a flanger filter to audio generated by its input SoundNodes.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
| |[ FeedbackPercent](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/flangernode.md#feedbackpercent-zilch-eng)|[soundnode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundnode.md)| |
| |[ FeedbackValue](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/flangernode.md#feedbackvalue-zilch-engin)| | |
| |[ MaxDelayMillisec](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/flangernode.md#maxdelaymillisec-zilch-en)| | |
| |[ ModulationFrequency](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/flangernode.md#modulationfrequency-zero)| | |


 #  Properties


---  
 #  FeedbackPercent : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.md)

> DEPRECATED The FeedbackValue property should be used instead.
> ``` lang=cpp, name=Nada
> var FeedbackPercent : Real


---  
 #  FeedbackValue : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.md)

> The percentage of output (0 - 1.0) which is fed back into the filter as input.
> ``` lang=cpp, name=Nada
> var FeedbackValue : Real


---  
 #  MaxDelayMillisec : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.md)

> The maximum delay reached by the modulation. It will oscillate between 0 and this value at the frequency set by the ModulationFrequency property.
> ``` lang=cpp, name=Nada
> var MaxDelayMillisec : Real


---  
 #  ModulationFrequency : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.md)

> The frequency of the oscillator which varies the modulation.
> ``` lang=cpp, name=Nada
> var ModulationFrequency : Real


---  
 #  Methods


---  
 

 