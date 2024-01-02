 `Sound`

(NOTE) Used with a CustomAudioNode to play audio data directly.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ AddMicUncompressedData](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundbuffer.markdown#addmicuncompresseddata-v)|[ SampleCount](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundbuffer.markdown#samplecount-zero-engine)|[referencecountedobject](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/referencecountedobject.markdown)| |
|[ AddSampleToBuffer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundbuffer.markdown#addsampletobuffer-void)| | | |
|[ GetSampleAtIndex](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundbuffer.markdown#getsampleatindex-zero-en)| | | |
|[ Reset](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/soundbuffer.markdown#reset-void)| | | |


 #  Properties


---  
 #  SampleCount : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> The number of samples currently in the buffer.
> ``` lang=cpp, name=Nada
> var SampleCount : Integer


---  
 #  Methods


---  
 #  AddMicUncompressedData : Void

> 
> |Name|Type|Description|
> |---|---|---|
> ||Array[[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)]| |
> ``` lang=cpp, name=Nada
> function AddMicUncompressedData( : Array[Real])
> ``` 


---  
 #  AddSampleToBuffer : Void

> Adds a new audio sample to the end of the buffer.
> |Name|Type|Description|
> |---|---|---|
> |sample|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function AddSampleToBuffer(sample : Real)
> ``` 


---  
 #  GetSampleAtIndex : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> Returns the sample at a specific index from the beginning of the buffer.
> |Name|Type|Description|
> |---|---|---|
> |index|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function GetSampleAtIndex(index : Integer) : Real
> ``` 


---  
 #  Reset : Void

> Removes all data from the buffer and resets it.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Reset()
> ``` 


---  
 

 