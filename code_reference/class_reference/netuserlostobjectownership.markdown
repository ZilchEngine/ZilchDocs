 `Event` `Networking`



(NOTE) Dispatched after the net user loses network ownership of a net object.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
| |[ CurrentNetUserOwner](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netuserlostobjectownership.markdown#currentnetuserowner-zero)|[event](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/event.markdown)| |
| |[ LostObject](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netuserlostobjectownership.markdown#lostobject-zero-engine-d)| | |


 #  Properties


---  
 #  CurrentNetUserOwner : [cog](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/cog.markdown)

 `read-only`

> The object's current network user owner.
> ``` lang=cpp, name=Nada
> var CurrentNetUserOwner : Cog


---  
 #  LostObject : [cog](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/cog.markdown)

 `read-only`

> The object this user just lost network ownership of.
> ``` lang=cpp, name=Nada
> var LostObject : Cog


---  
 #  Methods


---  
 

 