 `Event` `Physics`



(NOTE) Event data for applying custom physics effects.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/customphysicseffectevent.markdown#customphysicseffectevent)|[ Dt](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/customphysicseffectevent.markdown#dt-zero-engine-documenta)|[event](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/event.markdown)| |
| |[ Effect](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/customphysicseffectevent.markdown#effect-zero-engine-docum)| | |
| |[ RigidBody](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/customphysicseffectevent.markdown#rigidbody-zero-engine-do)| | |


 #  Properties


---  
 #  Dt : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The timestep of the current physics frame (in seconds).
> ``` lang=cpp, name=Nada
> var Dt : Real


---  
 #  Effect : [customphysicseffect](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/customphysicseffect.markdown)

> The effect that sent out this event.
> ``` lang=cpp, name=Nada
> var Effect : CustomPhysicsEffect


---  
 #  RigidBody : [rigidbody](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/rigidbody.markdown)

> The RigidBody to apply forces to.
> ``` lang=cpp, name=Nada
> var RigidBody : RigidBody


---  
 #  Methods


---  
 #  CustomPhysicsEffectEvent : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function CustomPhysicsEffectEvent()
> ``` 


---  
 

 