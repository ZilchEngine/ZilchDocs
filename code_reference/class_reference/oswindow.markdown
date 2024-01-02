 `Engine`

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ ClientToScreen](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/oswindow.markdown#clienttoscreen-zilch-engi)|[ ClientSize](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/oswindow.markdown#clientsize-zilch-engine-d)|[threadsafeid32eventobject](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/threadsafeid32eventobject.markdown)|[windowsoswindow](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/windowsoswindow.markdown)|
|[ HasFocus](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/oswindow.markdown#hasfocus-zilch-engine-doc)|[ MinSize](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/oswindow.markdown#minsize-zilch-engine-docu)| | |
|[ ScreenToClient](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/oswindow.markdown#screentoclient-zilch-engi)|[ MouseCapture](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/oswindow.markdown#mousecapture-zilch-engine)| | |
| |[ MouseCursor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/oswindow.markdown#mousecursor-zilch-engine)| | |
| |[ MouseTrap](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/oswindow.markdown#mousetrap-zilch-engine-do)| | |
| |[ Parent](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/oswindow.markdown#parent-zilch-engine-docum)| | |
| |[ Position](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/oswindow.markdown#position-zilch-engine-doc)| | |
| |[ Size](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/oswindow.markdown#size-zilch-engine-documen)| | |
| |[ State](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/oswindow.markdown#state-zilch-engine-docume)| | |
| |[ Title](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/oswindow.markdown#title-zilch-engine-docume)| | |
| |[ Visible](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/oswindow.markdown#visible-zilch-engine-docu)| | |


 #  Properties


---  
 #  ClientSize : [integer2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer2.markdown)

> 
> ``` lang=cpp, name=Nada
> var ClientSize : Integer2


---  
 #  MinSize : [integer2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer2.markdown)

> 
> ``` lang=cpp, name=Nada
> var MinSize : Integer2


---  
 #  MouseCapture : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var MouseCapture : Boolean


---  
 #  MouseCursor : [Cursor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/enum_reference.markdown#cursor)

> 
> ``` lang=cpp, name=Nada
> var MouseCursor : Cursor


---  
 #  MouseTrap : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var MouseTrap : Boolean


---  
 #  Parent : [oswindow](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/oswindow.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Parent : OsWindow


---  
 #  Position : [integer2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer2.markdown)

> 
> ``` lang=cpp, name=Nada
> var Position : Integer2


---  
 #  Size : [integer2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer2.markdown)

> 
> ``` lang=cpp, name=Nada
> var Size : Integer2


---  
 #  State : [WindowState](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/enum_reference.markdown#windowstate)

> 
> ``` lang=cpp, name=Nada
> var State : WindowState


---  
 #  Title : [string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)

> 
> ``` lang=cpp, name=Nada
> var Title : String


---  
 #  Visible : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> ``` lang=cpp, name=Nada
> var Visible : Boolean


---  
 #  Methods


---  
 #  ClientToScreen : [integer2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer2.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[integer2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer2.markdown)| |
> ``` lang=cpp, name=Nada
> function ClientToScreen(p0 : Integer2) : Integer2
> ``` 


---  
 #  HasFocus : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function HasFocus() : Boolean
> ``` 


---  
 #  ScreenToClient : [integer2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer2.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[integer2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer2.markdown)| |
> ``` lang=cpp, name=Nada
> function ScreenToClient(p0 : Integer2) : Integer2
> ``` 


---  
 

 