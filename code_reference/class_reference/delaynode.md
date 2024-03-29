 `Sound`

(NOTE) Applies a delay filter to audio generated by its input SoundNodes.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ InterpolateWetPercent](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/delaynode.md#interpolatewetpercent-vo)|[ Delay](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/delaynode.md#delay-zilch-engine-docume)|[soundnode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundnode.md)| |
|[ InterpolateWetValue](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/delaynode.md#interpolatewetvalue-void)|[ FeedbackPercent](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/delaynode.md#feedbackpercent-zilch-eng)| | |
| |[ FeedbackValue](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/delaynode.md#feedbackvalue-zilch-engin)| | |
| |[ WetPercent](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/delaynode.md#wetpercent-zilch-engine-d)| | |
| |[ WetValue](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/delaynode.md#wetvalue-zilch-engine-doc)| | |


 #  Properties


---  
 #  Delay : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.md)

> The length of the delay, in seconds.
> ``` lang=cpp, name=Nada
> var Delay : Real


---  
 #  FeedbackPercent : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.md)

> DEPRECATED The FeedbackValue property should be used instead.
> ``` lang=cpp, name=Nada
> var FeedbackPercent : Real


---  
 #  FeedbackValue : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.md)

> The percentage of output (from 0 to 1.0f) which is fed back into the filter as input, creating an echo-like effect.
> ``` lang=cpp, name=Nada
> var FeedbackValue : Real


---  
 #  WetPercent : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.md)

> DEPRECATED The WetValue property should be used instead.
> ``` lang=cpp, name=Nada
> var WetPercent : Real


---  
 #  WetValue : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.md)

> The percentage of the node's output (0 - 1.0) which has the delay filter applied to it.
> ``` lang=cpp, name=Nada
> var WetValue : Real


---  
 #  Methods


---  
 #  InterpolateWetPercent : Void

> DEPRECATED The InterpolateWetValue method should be used instead.
> |Name|Type|Description|
> |---|---|---|
> |wetPercent|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.md)| |
> |time|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.md)| |
> ``` lang=cpp, name=Nada
> function InterpolateWetPercent(wetPercent : Real, time : Real)
> ``` 


---  
 #  InterpolateWetValue : Void

> Interpolates the WetValue property from its current value to the value passed in as the first parameter, over the number of seconds passed in as the second parameter.
> |Name|Type|Description|
> |---|---|---|
> |wetPercent|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.md)| |
> |time|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.md)| |
> ``` lang=cpp, name=Nada
> function InterpolateWetValue(wetPercent : Real, time : Real)
> ``` 


---  
 

 