 `Event` `Physics`



(NOTE) An event sent out when specified by a CollisionFilter in a CollisionTable. Used to hook up events based upon certain CollisionGroup types colliding.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
| |[ FirstPoint](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/collisiongroupevent.markdown#firstpoint-zero-engine-d)|[basecollisionevent](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/basecollisionevent.markdown)| |
| |[ TypeAName](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/collisiongroupevent.markdown#typeaname-zero-engine-do)| | |
| |[ TypeBName](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/collisiongroupevent.markdown#typebname-zero-engine-do)| | |


 #  Properties


---  
 #  FirstPoint : [contactpoint](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/contactpoint.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var FirstPoint : ContactPoint


---  
 #  TypeAName : [string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)

 `read-only`

> Returns the CollisionGroup name of object A.
> ``` lang=cpp, name=Nada
> var TypeAName : String


---  
 #  TypeBName : [string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)

 `read-only`

> Returns the CollisionGroup name of object B.
> ``` lang=cpp, name=Nada
> var TypeBName : String


---  
 #  Methods


---  
 

 