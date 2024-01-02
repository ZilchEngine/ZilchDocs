 `Component` `Engine`



(NOTE) Time space component controls time for a Space.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Step](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/timespace.markdown#step-void)|[ Dt](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/timespace.markdown#dt-zilch-engine-documenta)|[component](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/component.markdown)| |
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/timespace.markdown#timespace-void)|[ DtOrZero](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/timespace.markdown#dtorzilch-zilch-engine-doc)| | |
|[ TogglePause](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/timespace.markdown#togglepause-void)|[ Frame](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/timespace.markdown#frame-zilch-engine-docume)| | |
| |[ GloballyPaused](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/timespace.markdown#globallypaused-zilch-engi)| | |
| |[ MaxDt](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/timespace.markdown#maxdt-zilch-engine-docume)| | |
| |[ MinDt](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/timespace.markdown#mindt-zilch-engine-docume)| | |
| |[ Paused](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/timespace.markdown#paused-zilch-engine-docum)| | |
| |[ RealDt](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/timespace.markdown#realdt-zilch-engine-docum)| | |
| |[ RealTimePassed](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/timespace.markdown#realtimepassed-zilch-engi)| | |
| |[ StepCount](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/timespace.markdown#stepcount-zilch-engine-do)| | |
| |[ TimeMode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/timespace.markdown#timemode-zilch-engine-doc)| | |
| |[ TimePassed](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/timespace.markdown#timepassed-zilch-engine-d)| | |
| |[ TimeScale](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/timespace.markdown#timescale-zilch-engine-do)| | |


 #  Properties


---  
 #  Dt : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Dt : Real


---  
 #  DtOrZero : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var DtOrZero : Real


---  
 #  Frame : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

> The current frame we are on (starts at 0 and counts up for every frame that is run) This value counts up regardless of if the space is paused.
> ``` lang=cpp, name=Nada
> var Frame : Integer


---  
 #  GloballyPaused : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var GloballyPaused : Boolean


---  
 #  MaxDt : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The maximum amount of time we send when running in 'ActualFrametime' mode If this value is set too high and the user does anything to pause their system or the game (example grabbing the window) then a large frame time will be sent out and physics objects will jump very far (causing tunneling and random bounces)
> ``` lang=cpp, name=Nada
> var MaxDt : Real


---  
 #  MinDt : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> The minimum amount of time we send when running in 'ActualFrametime' mode Ideally this is set to a very small non-zero value to prevent any division by zero errors.
> ``` lang=cpp, name=Nada
> var MinDt : Real


---  
 #  Paused : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> If the time space is paused then we cease sending out logic update events When paused, the Dt will remain at whatever it was (it will NOT be set to 0)
> ``` lang=cpp, name=Nada
> var Paused : Boolean


---  
 #  RealDt : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var RealDt : Real


---  
 #  RealTimePassed : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> 
> ``` lang=cpp, name=Nada
> var RealTimePassed : Real


---  
 #  StepCount : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

> Causes the engine to update multiple times before rendering a frame.
> ``` lang=cpp, name=Nada
> var StepCount : Integer


---  
 #  TimeMode : [TimeMode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/enum_reference.markdown#timemode)

> When set to fixed framerate the Dt/frame time will never change (it will send whatever the project frame-rate-limiter is set to) This means it is important to run with a frame-rate limiter of some kind otherwise the game will appear to run much faster/slower Note: For determinism, you should always run in FixedFrametime mode When set to actual framerate we will send out the real time that the engine is encountering (clamped by MinDt / MaxDt)
> ``` lang=cpp, name=Nada
> var TimeMode : TimeMode


---  
 #  TimePassed : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> 
> ``` lang=cpp, name=Nada
> var TimePassed : Real


---  
 #  TimeScale : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> Scale the speed of time for interesting effects like bullet time or fast paced gameplay. TimeScale is clamped to be positive.
> ``` lang=cpp, name=Nada
> var TimeScale : Real


---  
 #  Methods


---  
 #  Step : Void

> Allows the engine to be advance one frame forward. Useful for debugging one frame at a time.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Step()
> ``` 


---  
 #  TimeSpace : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function TimeSpace()
> ``` 


---  
 #  TogglePause : Void

> Toggles the state of paused.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function TogglePause()
> ``` 


---  
 

 