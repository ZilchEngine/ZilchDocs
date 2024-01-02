 `Physics`

(NOTE) Used to filter objects during cast operations.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
| |[ IgnoreChildren](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/basecastfilter.markdown#ignorechildren-zilch-engi)| |[castfilter](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/castfilter.markdown)|
| |[ IgnoreDynamic](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/basecastfilter.markdown#ignoredynamic-zilch-engin)| | |
| |[ IgnoreGhost](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/basecastfilter.markdown#ignoreghost-zilch-engine)| | |
| |[ IgnoreKinematic](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/basecastfilter.markdown#ignorekinematic-zilch-eng)| | |
| |[ IgnoreStatic](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/basecastfilter.markdown#ignorestatic-zilch-engine)| | |


 #  Properties


---  
 #  IgnoreChildren : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> This flag is currently only used for SweepCollider tests on PhysicsSpace. This is used to ignore all objects that are a child of the Collider that is being swept.
> ``` lang=cpp, name=Nada
> var IgnoreChildren : Boolean


---  
 #  IgnoreDynamic : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Should Colliders with RigidBodies marked Dynamic be ignored during casts?
> ``` lang=cpp, name=Nada
> var IgnoreDynamic : Boolean


---  
 #  IgnoreGhost : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Should Colliders marked Ghost be ignored during casts?
> ``` lang=cpp, name=Nada
> var IgnoreGhost : Boolean


---  
 #  IgnoreKinematic : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Should Colliders with RigidBodies marked Kinematic be ignored during casts?
> ``` lang=cpp, name=Nada
> var IgnoreKinematic : Boolean


---  
 #  IgnoreStatic : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Should Colliders with RigidBodies marked Static be ignored during casts? Note: Collider's with no RigidBody are treated as static.
> ``` lang=cpp, name=Nada
> var IgnoreStatic : Boolean


---  
 #  Methods


---  
 

 