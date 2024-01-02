 `Component` `UiWidget`



|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ GetChildren](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidgetcomponenthierarchy.markdown#getchildren-zero-engine)|[ ChildCount](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidgetcomponenthierarchy.markdown#childcount-zero-engine-d)|[component](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/component.markdown)|[uiwidget](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidget.markdown)|
|[ IsAncestorOf](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidgetcomponenthierarchy.markdown#isancestorof-zero-engine)|[ LastDeepestChild](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidgetcomponenthierarchy.markdown#lastdeepestchild-zero-en)| | |
|[ IsDescendantOf](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidgetcomponenthierarchy.markdown#isdescendantof-zero-engi)|[ LastDirectChild](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidgetcomponenthierarchy.markdown#lastdirectchild-zero-eng)| | |
| |[ NextInHierarchyOrder](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidgetcomponenthierarchy.markdown#nextinhierarchyorder-zer)| | |
| |[ NextSibling](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidgetcomponenthierarchy.markdown#nextsibling-zero-engine)| | |
| |[ Parent](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidgetcomponenthierarchy.markdown#parent-zero-engine-docum)| | |
| |[ PreviousInHierarchyOrder](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidgetcomponenthierarchy.markdown#previousinhierarchyorder)| | |
| |[ PreviousSibling](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidgetcomponenthierarchy.markdown#previoussibling-zero-eng)| | |
| |[ Root](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidgetcomponenthierarchy.markdown#root-zero-engine-documen)| | |


 #  Properties


---  
 #  ChildCount : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var ChildCount : Integer


---  
 #  LastDeepestChild : [uiwidget](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidget.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var LastDeepestChild : UiWidget


---  
 #  LastDirectChild : [uiwidget](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidget.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var LastDirectChild : UiWidget


---  
 #  NextInHierarchyOrder : [uiwidget](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidget.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var NextInHierarchyOrder : UiWidget


---  
 #  NextSibling : [uiwidget](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidget.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var NextSibling : UiWidget


---  
 #  Parent : [uiwidget](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidget.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Parent : UiWidget


---  
 #  PreviousInHierarchyOrder : [uiwidget](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidget.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var PreviousInHierarchyOrder : UiWidget


---  
 #  PreviousSibling : [uiwidget](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidget.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var PreviousSibling : UiWidget


---  
 #  Root : [uiwidget](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidget.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Root : UiWidget


---  
 #  Methods


---  
 #  GetChildren : [uiwidgetrange](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidgetrange.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function GetChildren() : UiWidgetRange
> ``` 


---  
 #  IsAncestorOf : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> ||[uiwidget](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidget.markdown)| |
> ``` lang=cpp, name=Nada
> function IsAncestorOf( : UiWidget) : Boolean
> ``` 


---  
 #  IsDescendantOf : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> ||[uiwidget](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/uiwidget.markdown)| |
> ``` lang=cpp, name=Nada
> function IsDescendantOf( : UiWidget) : Boolean
> ``` 


---  
 

 