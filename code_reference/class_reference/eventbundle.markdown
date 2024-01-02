 `Networking`

(NOTE) Event Bundle. Serialized event storage container.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ AddEvent](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/eventbundle.markdown#addevent-zero-engine-doc)|[ GameSession](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/eventbundle.markdown#gamesession-zero-engine)|Object| |
|[ Clear](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/eventbundle.markdown#clear-void)|[ IsEmpty](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/eventbundle.markdown#isempty-zero-engine-docu)| | |
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/eventbundle.markdown#eventbundle-void)| | | |
|[ GetEvents](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/eventbundle.markdown#getevents-zero-engine-do)| | | |
|[ RemoveEvent](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/eventbundle.markdown#removeevent-zero-engine)| | | |


 #  Properties


---  
 #  GameSession : [gamesession](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gamesession.markdown)

> Returns the game session.
> ``` lang=cpp, name=Nada
> var GameSession : GameSession


---  
 #  IsEmpty : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if the event bundle is empty (doesn't contain any events), else false.
> ``` lang=cpp, name=Nada
> var IsEmpty : Boolean


---  
 #  Methods


---  
 #  AddEvent : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Adds the event to back of the event bundle. Returns true if successful, else false (an event of that type has already been added).
> |Name|Type|Description|
> |---|---|---|
> |event|[event](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/event.markdown)| |
> ``` lang=cpp, name=Nada
> function AddEvent(event : Event) : Boolean
> ``` 


---  
 #  Clear : Void

> Clears the event bundle.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Clear()
> ``` 


---  
 #  EventBundle : Void

 `constructor`

> Constructors.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function EventBundle()
> ``` 


---  
 #  EventBundle : Void

 `constructor`

> Constructors.
> |Name|Type|Description|
> |---|---|---|
> |event|[event](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/event.markdown)| |
> ``` lang=cpp, name=Nada
> function EventBundle(event : Event)
> ``` 


---  
 #  EventBundle : Void

 `constructor`

> Constructors.
> |Name|Type|Description|
> |---|---|---|
> |rhs|[eventbundle](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/eventbundle.markdown)| |
> ``` lang=cpp, name=Nada
> function EventBundle(rhs : EventBundle)
> ``` 


---  
 #  EventBundle : Void

 `constructor`

> Constructors.
> |Name|Type|Description|
> |---|---|---|
> |gameSession|[gamesession](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gamesession.markdown)| |
> ``` lang=cpp, name=Nada
> function EventBundle(gameSession : GameSession)
> ``` 


---  
 #  EventBundle : Void

 `constructor`

> Constructors.
> |Name|Type|Description|
> |---|---|---|
> |gameSession|[gamesession](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gamesession.markdown)| |
> |event|[event](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/event.markdown)| |
> ``` lang=cpp, name=Nada
> function EventBundle(gameSession : GameSession, event : Event)
> ``` 


---  
 #  GetEvents : [eventrange](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/eventrange.markdown)

> Returns all the events that have been added to the event bundle.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function GetEvents() : EventRange
> ``` 


---  
 #  RemoveEvent : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Removes the event specified from the event bundle. Returns true if successful, else false (an event of that type has already been added).
> |Name|Type|Description|
> |---|---|---|
> |event|[event](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/event.markdown)| |
> ``` lang=cpp, name=Nada
> function RemoveEvent(event : Event) : Boolean
> ``` 


---  
 #  RemoveEvent : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Removes the event specified from the event bundle. Returns true if successful, else false (an event of that type has already been added).
> |Name|Type|Description|
> |---|---|---|
> ||[string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> ``` lang=cpp, name=Nada
> function RemoveEvent( : String) : Boolean
> ``` 


---  
 

 