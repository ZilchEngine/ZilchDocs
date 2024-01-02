 `Component` `UiWidget`



(NOTE) Layouts are in charge of calling UpdateTransform on all children, regardless of whether or not they ignore layouts.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Debug](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uilayout.markdown#debug-void)|[ PaddingBottom](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uilayout.markdown#paddingbottom-zilch-engin)|[component](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/component.markdown)|[uidocklayout](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uidocklayout.markdown)|
| |[ PaddingLeft](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uilayout.markdown#paddingleft-zilch-engine)| |[uifilllayout](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uifilllayout.markdown)|
| |[ PaddingRight](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uilayout.markdown#paddingright-zilch-engine)| |[uistacklayout](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uistacklayout.markdown)|
| |[ PaddingTop](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uilayout.markdown#paddingtop-zilch-engine-d)| | |


 #  Properties


---  
 #  PaddingBottom : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> 
> ``` lang=cpp, name=Nada
> var PaddingBottom : Real


---  
 #  PaddingLeft : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> Padding getter / setters for binding until we have Thickness binding.
> ``` lang=cpp, name=Nada
> var PaddingLeft : Real


---  
 #  PaddingRight : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> 
> ``` lang=cpp, name=Nada
> var PaddingRight : Real


---  
 #  PaddingTop : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

> 
> ``` lang=cpp, name=Nada
> var PaddingTop : Real


---  
 #  Methods


---  
 #  Debug : Void

> Calling this will set a breakpoint before the layout is done.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Debug()
> ``` 


---  
 

 