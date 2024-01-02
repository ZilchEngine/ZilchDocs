 `Event` `Physics`



(NOTE) Common interface for all collision events. Contains shared methods to access contact information for a collision.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
| |[ ContactPointCount](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/basecollisionevent.markdown#contactpointcount-zero-e)|[event](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/event.markdown)|[collisionevent](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/collisionevent.markdown)|
| |[ ContactPoints](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/basecollisionevent.markdown#contactpoints-zero-engin)| |[collisiongroupevent](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/collisiongroupevent.markdown)|
| |[ IsGhost](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/basecollisionevent.markdown#isghost-zero-engine-docu)| |[presolveevent](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/presolveevent.markdown)|
| |[ Object](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/basecollisionevent.markdown#object-zero-engine-docum)| | |
| |[ OtherObject](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/basecollisionevent.markdown#otherobject-zero-engine)| | |


 #  Properties


---  
 #  ContactPointCount : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> The number of contact points in this collision.
> ``` lang=cpp, name=Nada
> var ContactPointCount : Integer


---  
 #  ContactPoints : [contactpointrange](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/contactpointrange.markdown)

 `read-only`

> A range for iterating through all contact points.
> ``` lang=cpp, name=Nada
> var ContactPoints : ContactPointRange


---  
 #  IsGhost : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> If this was a ghost collision (detected but not resolved).
> ``` lang=cpp, name=Nada
> var IsGhost : Boolean


---  
 #  Object : [cog](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/cog.markdown)

 `read-only`

> The object that this event was sent to.
> ``` lang=cpp, name=Nada
> var Object : Cog


---  
 #  OtherObject : [cog](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/cog.markdown)

 `read-only`

> The other object in this collision.
> ``` lang=cpp, name=Nada
> var OtherObject : Cog


---  
 #  Methods


---  
 

 