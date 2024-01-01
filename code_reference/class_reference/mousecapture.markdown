 `Component` `Gameplay`



|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Capture](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/mousecapture.markdown#capture-zero-engine-docu)|[ IsCaptured](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/mousecapture.markdown#iscaptured-zero-engine-d)|[component](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/component.markdown)| |
|[ Constructor](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/mousecapture.markdown#mousecapture-void)| | | |
|[ ReleaseCapture](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/mousecapture.markdown#releasecapture-void)| | | |


 #  Properties


---  
 #  IsCaptured : [boolean](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns whether or not this has an active mouse capture.
> ``` lang=cpp, name=Nada
> var IsCaptured : Boolean


---  
 #  Methods


---  
 #  Capture : [boolean](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Starts the mouse manipulation. All mouse events will now only go to the owner of this Component. Returns whether or not the manipulation can be started.
> |Name|Type|Description|
> |---|---|---|
> |e|[viewportmouseevent](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/viewportmouseevent.markdown)| |
> ``` lang=cpp, name=Nada
> function Capture(e : ViewportMouseEvent) : Boolean
> ``` 


---  
 #  MouseCapture : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function MouseCapture()
> ``` 


---  
 #  ReleaseCapture : Void

> Releases the mouse manipulation.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function ReleaseCapture()
> ``` 


---  
 #  ReleaseCapture : Void

> Releases the mouse manipulation.
> |Name|Type|Description|
> |---|---|---|
> |e|[viewportmouseevent](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/viewportmouseevent.markdown)| |
> ``` lang=cpp, name=Nada
> function ReleaseCapture(e : ViewportMouseEvent)
> ``` 


---  
 

 