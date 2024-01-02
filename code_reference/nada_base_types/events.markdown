 `Core`

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Connect](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/events.markdown#connect-void)| | | |
|[ Send](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/events.markdown#send-zilch-engine-documen)| | | |


 #  Properties


---  
 #  Methods


---  
 #  Connect : Void

 `static`

> 
> |Name|Type|Description|
> |---|---|---|
> |sender|[anyhandle](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/anyhandle.markdown)| |
> |eventName|[string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> |callback|delegate()| |
> ``` lang=cpp, name=Nada
> function Connect(sender : AnyHandle, eventName : String, callback : delegate())
> ``` 


---  
 #  Send : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `static`

> 
> |Name|Type|Description|
> |---|---|---|
> |sender|[anyhandle](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/anyhandle.markdown)| |
> |eventName|[string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> |event|[eventdata](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/eventdata.markdown)| |
> ``` lang=cpp, name=Nada
> function Send(sender : AnyHandle, eventName : String, event : EventData) : Integer
> ``` 


---  
 

 