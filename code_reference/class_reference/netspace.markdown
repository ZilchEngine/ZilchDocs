 `Component` `Networking`



(NOTE) Network Space. Manages the replication of a single space on the network.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netspace.markdown#netspace-void)|[ NetObjectCount](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netspace.markdown#netobjectcount-zilch-engi)|[netobject](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown)| |
| |[ NetUserCount](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netspace.markdown#netusercount-zilch-engine)| | |


 #  Properties


---  
 #  NetObjectCount : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> Returns the number of net objects in this space (but not including the net space itself).
> ``` lang=cpp, name=Nada
> var NetObjectCount : Integer


---  
 #  NetUserCount : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> Returns the number of net users in this space.
> ``` lang=cpp, name=Nada
> var NetUserCount : Integer


---  
 #  Methods


---  
 #  NetSpace : Void

 `constructor`

> Constructor.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function NetSpace()
> ``` 


---  
 

 