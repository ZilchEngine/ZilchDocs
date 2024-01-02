 `Event` `Widget`



(NOTE) Mouse events for actions concerning the mouse.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ IsButtonUp](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/mouseevent.markdown#isbuttonup-zero-engine-d)|[ AltPressed](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/mouseevent.markdown#altpressed-zero-engine-d)|[event](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/event.markdown)|[mousedragevent](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/mousedragevent.markdown)|
| |[ Button](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/mouseevent.markdown#button-zero-engine-docum)| |[mousefiledropevent](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/mousefiledropevent.markdown)|
| |[ ButtonDown](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/mouseevent.markdown#buttondown-zero-engine-d)| |[viewportmouseevent](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/viewportmouseevent.markdown)|
| |[ CtrlPressed](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/mouseevent.markdown#ctrlpressed-zero-engine)| | |
| |[ HandledEvent](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/mouseevent.markdown#handledevent-zero-engine)| | |
| |[ Mouse](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/mouseevent.markdown#mouse-zero-engine-docume)| | |
| |[ Movement](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/mouseevent.markdown#movement-zero-engine-doc)| | |
| |[ Position](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/mouseevent.markdown#position-zero-engine-doc)| | |
| |[ Scroll](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/mouseevent.markdown#scroll-zero-engine-docum)| | |
| |[ ShiftPressed](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/mouseevent.markdown#shiftpressed-zero-engine)| | |


 #  Properties


---  
 #  AltPressed : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var AltPressed : Boolean


---  
 #  Button : [MouseButtons](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/enum_reference.markdown#mousebuttons)

> 
> ``` lang=cpp, name=Nada
> var Button : MouseButtons


---  
 #  ButtonDown : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> State of all the mouse buttons.
> ``` lang=cpp, name=Nada
> var ButtonDown : Boolean


---  
 #  CtrlPressed : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var CtrlPressed : Boolean


---  
 #  HandledEvent : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var HandledEvent : Boolean


---  
 #  Mouse : [mouse](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/mouse.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Mouse : Mouse


---  
 #  Movement : [real2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real2.markdown)

> 
> ``` lang=cpp, name=Nada
> var Movement : Real2


---  
 #  Position : [real2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real2.markdown)

> 
> ``` lang=cpp, name=Nada
> var Position : Real2


---  
 #  Scroll : [real2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real2.markdown)

> 
> ``` lang=cpp, name=Nada
> var Scroll : Real2


---  
 #  ShiftPressed : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var ShiftPressed : Boolean


---  
 #  Methods


---  
 #  IsButtonUp : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |button|[MouseButtons](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/enum_reference.markdown#mousebuttons)| |
> ``` lang=cpp, name=Nada
> function IsButtonUp(button : MouseButtons) : Boolean
> ``` 


---  
 

 