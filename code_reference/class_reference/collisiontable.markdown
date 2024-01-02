 `Resource` `Physics`



(NOTE) Defines filter pairs between CollisionGroups. These filters are used to control if collision detection and resolution happens between Colliders. Additionally, CollisionFilterBlocks can be defined on filters to send out extra events.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ CreateRuntime](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/collisiontable.markdown#createruntime-zilch-engin)| |[dataresource](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/dataresource.markdown)| |
|[ FindFilter](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/collisiontable.markdown#findfilter-zilch-engine-d)| | | |
|[ RuntimeClone](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/collisiontable.markdown#runtimeclone-zilch-engine)| | | |


 #  Properties


---  
 #  Methods


---  
 #  CreateRuntime : [collisiontable](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/collisiontable.markdown)

 `static`

> Creates a CollisionTable for run-time modifications.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function CreateRuntime() : CollisionTable
> ``` 


---  
 #  FindFilter : [collisionfilter](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/collisionfilter.markdown)

> Finds the filter between the pair of collision groups.
> |Name|Type|Description|
> |---|---|---|
> |groupA|[collisiongroup](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/collisiongroup.markdown)| |
> |groupB|[collisiongroup](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/collisiongroup.markdown)| |
> ``` lang=cpp, name=Nada
> function FindFilter(groupA : CollisionGroup, groupB : CollisionGroup) : CollisionFilter
> ``` 


---  
 #  RuntimeClone : [collisiontable](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/collisiontable.markdown)

> Creates a clone of this CollisionTable for run-time modifications.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function RuntimeClone() : CollisionTable
> ``` 


---  
 

 