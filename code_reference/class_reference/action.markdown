 `Engine`

(NOTE) Base action class.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Cancel](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/action.markdown#cancel-void)|[ Active](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/action.markdown#active-zilch-engine-docum)|[referencecountedeventobject](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/referencecountedeventobject.markdown)|[actiondelay](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/actiondelay.markdown)|
| |[ Completed](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/action.markdown#completed-zilch-engine-do)| |[actionset](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/actionset.markdown)|
| |[ Started](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/action.markdown#started-zilch-engine-docu)| | |


 #  Properties


---  
 #  Active : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> The action is queued and not stared or running.
> ``` lang=cpp, name=Nada
> var Active : Boolean


---  
 #  Completed : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> The action ran until it completed.
> ``` lang=cpp, name=Nada
> var Completed : Boolean


---  
 #  Started : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Has the action started?
> ``` lang=cpp, name=Nada
> var Started : Boolean


---  
 #  Methods


---  
 #  Cancel : Void

> Cancel the action and all child actions.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Cancel()
> ``` 


---  
 

 