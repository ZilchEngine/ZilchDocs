 `Engine`

(NOTE) A Joystick is associated with a hardware joystick, and provides the ability to query axes and buttons.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Calibrating](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/joystick.markdown#calibrating-zilch-engine)|[ AxisCount](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/joystick.markdown#axiscount-zilch-engine-do)|[eventobject](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/eventobject.markdown)| |
|[ EndCalibration](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/joystick.markdown#endcalibration-void)|[ ButtonCount](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/joystick.markdown#buttoncount-zilch-engine)| | |
|[ GetAxisIndex](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/joystick.markdown#getaxisindex-zilch-engine)|[ DisabledValue](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/joystick.markdown#disabledvalue-zilch-engin)| | |
|[ GetAxisName](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/joystick.markdown#getaxisname-zilch-engine)|[ IsActive](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/joystick.markdown#isactive-zilch-engine-doc)| | |
|[ GetAxisValue](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/joystick.markdown#getaxisvalue-zilch-engine)|[ Name](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/joystick.markdown#name-zilch-engine-documen)| | |
|[ GetAxisValueByName](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/joystick.markdown#getaxisvaluebyname-zero)| | | |
|[ GetButtonValue](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/joystick.markdown#getbuttonvalue-zilch-engi)| | | |
|[ LoadInputMapping](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/joystick.markdown#loadinputmapping-void)| | | |
|[ SaveInputMapping](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/joystick.markdown#saveinputmapping-void)| | | |
|[ StartCalibration](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/joystick.markdown#startcalibration-void)| | | |


 #  Properties


---  
 #  AxisCount : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var AxisCount : Integer


---  
 #  ButtonCount : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> Get the number of buttons or axes.
> ``` lang=cpp, name=Nada
> var ButtonCount : Integer


---  
 #  DisabledValue : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only` `static`

> A value that means a joystick axis is invalid. For example when a HAT-switch is not pressed down, it will return this value.
> ``` lang=cpp, name=Nada
> var DisabledValue : Real


---  
 #  IsActive : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Gets whether or not the joystick is active.
> ``` lang=cpp, name=Nada
> var IsActive : Boolean


---  
 #  Name : [string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)

 `read-only`

> Get the name of the Joystick.
> ``` lang=cpp, name=Nada
> var Name : String


---  
 #  Methods


---  
 #  Calibrating : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Calibrating() : Boolean
> ``` 


---  
 #  EndCalibration : Void

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function EndCalibration()
> ``` 


---  
 #  GetAxisIndex : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |name|[string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> ``` lang=cpp, name=Nada
> function GetAxisIndex(name : String) : Integer
> ``` 


---  
 #  GetAxisName : [string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |index|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function GetAxisName(index : Integer) : String
> ``` 


---  
 #  GetAxisValue : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> Queries an axes and returns a value between [-1, 1]. The valid range of axes is between 0 and 'GetMaxAxes'. If the axis is not valid, then the value returned is 0. If the axis is disabled, then the value returned is Joystick.DisabledValue.
> |Name|Type|Description|
> |---|---|---|
> |index|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function GetAxisValue(index : Integer) : Real
> ``` 


---  
 #  GetAxisValueByName : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |name|[string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> ``` lang=cpp, name=Nada
> function GetAxisValueByName(name : String) : Real
> ``` 


---  
 #  GetButtonValue : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Queries a button and returns true if it is down, false if it is up The valid range of buttons is between 0 and 'GetMaxButtons' If the button is not valid, then the value returned is false.
> |Name|Type|Description|
> |---|---|---|
> |index|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function GetButtonValue(index : Integer) : Boolean
> ``` 


---  
 #  LoadInputMapping : Void

> Load an input mapping.
> |Name|Type|Description|
> |---|---|---|
> |name|[string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> ``` lang=cpp, name=Nada
> function LoadInputMapping(name : String)
> ``` 


---  
 #  SaveInputMapping : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |name|[string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> ``` lang=cpp, name=Nada
> function SaveInputMapping(name : String)
> ``` 


---  
 #  StartCalibration : Void

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function StartCalibration()
> ``` 


---  
 

 