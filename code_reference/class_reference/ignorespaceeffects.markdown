 `Component` `Physics`



(NOTE) Allows a cog to ignore certain effect types (such as gravity or drag) that are being applied to the entire space (effects on Space or LevelSettings).

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ GetIgnoreState](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ignorespaceeffects.markdown#getignorestate-zilch-engi)|[ IgnoreBuoyancy](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ignorespaceeffects.markdown#ignorebuoyancy-zilch-engi)|[component](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/component.markdown)| |
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ignorespaceeffects.markdown#ignorespaceeffects-void)|[ IgnoreCustom](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ignorespaceeffects.markdown#ignorecustom-zilch-engine)| | |
|[ SetIgnoreState](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ignorespaceeffects.markdown#setignorestate-void)|[ IgnoreDrag](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ignorespaceeffects.markdown#ignoredrag-zilch-engine-d)| | |
| |[ IgnoreFlow](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ignorespaceeffects.markdown#ignoreflow-zilch-engine-d)| | |
| |[ IgnoreForce](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ignorespaceeffects.markdown#ignoreforce-zilch-engine)| | |
| |[ IgnoreGravity](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ignorespaceeffects.markdown#ignoregravity-zilch-engin)| | |
| |[ IgnorePointForce](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ignorespaceeffects.markdown#ignorepointforce-zilch-en)| | |
| |[ IgnorePointGravity](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ignorespaceeffects.markdown#ignorepointgravity-zero)| | |
| |[ IgnoreThrust](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ignorespaceeffects.markdown#ignorethrust-zilch-engine)| | |
| |[ IgnoreTorque](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ignorespaceeffects.markdown#ignoretorque-zilch-engine)| | |
| |[ IgnoreVortex](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ignorespaceeffects.markdown#ignorevortex-zilch-engine)| | |
| |[ IgnoreWind](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ignorespaceeffects.markdown#ignorewind-zilch-engine-d)| | |


 #  Properties


---  
 #  IgnoreBuoyancy : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Whether or not to ignore buoyancy effects.
> ``` lang=cpp, name=Nada
> var IgnoreBuoyancy : Boolean


---  
 #  IgnoreCustom : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Whether or not to ignore custom effects.
> ``` lang=cpp, name=Nada
> var IgnoreCustom : Boolean


---  
 #  IgnoreDrag : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Whether or not to ignore drag effects.
> ``` lang=cpp, name=Nada
> var IgnoreDrag : Boolean


---  
 #  IgnoreFlow : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Whether or not to ignore flow effects.
> ``` lang=cpp, name=Nada
> var IgnoreFlow : Boolean


---  
 #  IgnoreForce : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Whether or not to ignore force effects.
> ``` lang=cpp, name=Nada
> var IgnoreForce : Boolean


---  
 #  IgnoreGravity : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Whether or not to ignore gravity effects.
> ``` lang=cpp, name=Nada
> var IgnoreGravity : Boolean


---  
 #  IgnorePointForce : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Whether or not to ignore point force effects.
> ``` lang=cpp, name=Nada
> var IgnorePointForce : Boolean


---  
 #  IgnorePointGravity : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Whether or not to ignore point gravity effects.
> ``` lang=cpp, name=Nada
> var IgnorePointGravity : Boolean


---  
 #  IgnoreThrust : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Whether or not to ignore thrust effects.
> ``` lang=cpp, name=Nada
> var IgnoreThrust : Boolean


---  
 #  IgnoreTorque : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Whether or not to ignore torque effects.
> ``` lang=cpp, name=Nada
> var IgnoreTorque : Boolean


---  
 #  IgnoreVortex : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Whether or not to ignore vortex effects.
> ``` lang=cpp, name=Nada
> var IgnoreVortex : Boolean


---  
 #  IgnoreWind : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Whether or not to ignore wind effects.
> ``` lang=cpp, name=Nada
> var IgnoreWind : Boolean


---  
 #  Methods


---  
 #  GetIgnoreState : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Should the given effect type be ignored?
> |Name|Type|Description|
> |---|---|---|
> |effectType|[PhysicsEffectType](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/enum_reference.markdown#physicseffecttype)| |
> ``` lang=cpp, name=Nada
> function GetIgnoreState(effectType : PhysicsEffectType) : Boolean
> ``` 


---  
 #  IgnoreSpaceEffects : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function IgnoreSpaceEffects()
> ``` 


---  
 #  SetIgnoreState : Void

> Set if an effect type should be ignored.
> |Name|Type|Description|
> |---|---|---|
> |effectType|[PhysicsEffectType](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/enum_reference.markdown#physicseffecttype)| |
> |ignore|[boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)| |
> ``` lang=cpp, name=Nada
> function SetIgnoreState(effectType : PhysicsEffectType, ignore : Boolean)
> ``` 


---  
 

 