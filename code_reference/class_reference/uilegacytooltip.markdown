 `Editor`

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ AddText](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/uilegacytooltip.markdown#addtext-void)|[ BackgroundColor](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/uilegacytooltip.markdown#backgroundcolor-zero-eng)| | |
|[ ClearText](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/uilegacytooltip.markdown#cleartext-void)|[ BorderColor](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/uilegacytooltip.markdown#bordercolor-zero-engine)| | |
|[ SetColorScheme](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/uilegacytooltip.markdown#setcolorscheme-void)|[ Padding](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/uilegacytooltip.markdown#padding-zero-engine-docu)| | |
|[ SetPlacement](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/uilegacytooltip.markdown#setplacement-void)| | | |
|[ SetPriority](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/uilegacytooltip.markdown#setpriority-void)| | | |
|[ Constructor](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/uilegacytooltip.markdown#uilegacytooltip-void)| | | |


 #  Properties


---  
 #  BackgroundColor : [real4](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real4.markdown)

> 
> ``` lang=cpp, name=Nada
> var BackgroundColor : Real4


---  
 #  BorderColor : [real4](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real4.markdown)

> 
> ``` lang=cpp, name=Nada
> var BorderColor : Real4


---  
 #  Padding : [thickness](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/thickness.markdown)

> 
> ``` lang=cpp, name=Nada
> var Padding : Thickness


---  
 #  Methods


---  
 #  AddText : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[string](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> |p1|[real4](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real4.markdown)| |
> ``` lang=cpp, name=Nada
> function AddText(p0 : String, p1 : Real4)
> ``` 


---  
 #  ClearText : Void

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function ClearText()
> ``` 


---  
 #  SetColorScheme : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[ToolTipColorScheme](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/enum_reference.markdown#tooltipcolorscheme)| |
> ``` lang=cpp, name=Nada
> function SetColorScheme(p0 : ToolTipColorScheme)
> ``` 


---  
 #  SetPlacement : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[cameraviewport](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/cameraviewport.markdown)| |
> |p1|[rectangle](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/rectangle.markdown)| |
> ``` lang=cpp, name=Nada
> function SetPlacement(p0 : CameraViewport, p1 : Rectangle)
> ``` 


---  
 #  SetPriority : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[IndicatorSide](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/enum_reference.markdown#indicatorside)| |
> |p1|[IndicatorSide](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/enum_reference.markdown#indicatorside)| |
> |p2|[IndicatorSide](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/enum_reference.markdown#indicatorside)| |
> |p3|[IndicatorSide](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/enum_reference.markdown#indicatorside)| |
> ``` lang=cpp, name=Nada
> function SetPriority(p0 : IndicatorSide, p1 : IndicatorSide, p2 : IndicatorSide, p3 : IndicatorSide)
> ``` 


---  
 #  UiLegacyToolTip : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function UiLegacyToolTip()
> ``` 


---  
 #  UiLegacyToolTip : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[uilegacytooltip](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/uilegacytooltip.markdown)| |
> ``` lang=cpp, name=Nada
> function UiLegacyToolTip(p0 : UiLegacyToolTip)
> ``` 


---  
 

 