 `Resource` `Physics`



(NOTE) Base class of mesh type physics resources. Stores the actual mesh (no optimization structures) and information about the mesh such as mass and inertia.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ UpdateAndNotifyIfModified](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/genericphysicsmesh.markdown#updateandnotifyifmodifie)|[ Indices](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/genericphysicsmesh.markdown#indices-zero-engine-docu)|Resource|[convexmesh](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/convexmesh.markdown)|
|[ Validate](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/genericphysicsmesh.markdown#validate-zero-engine-doc)|[ Vertices](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/genericphysicsmesh.markdown#vertices-zero-engine-doc)| |[physicsmesh](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/physicsmesh.markdown)|


 #  Properties


---  
 #  Indices : [physicsmeshindexdata](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/physicsmeshindexdata.markdown)

 `read-only`

> The index buffer data of this mesh.
> ``` lang=cpp, name=Nada
> var Indices : PhysicsMeshIndexData


---  
 #  Vertices : [physicsmeshvertexdata](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/physicsmeshvertexdata.markdown)

 `read-only`

> The vertex buffer data of this mesh.
> ``` lang=cpp, name=Nada
> var Vertices : PhysicsMeshVertexData


---  
 #  Methods


---  
 #  UpdateAndNotifyIfModified : Void

> Rebuild all extra mesh information if it is currently modified. This includes things like the center of mass, volume, aabb, edge info and more (some derived types may have a mid-phase, etc...)
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function UpdateAndNotifyIfModified()
> ``` 


---  
 #  Validate : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Check if the mesh is valid. Optionally throw a script exception if it is invalid.
> |Name|Type|Description|
> |---|---|---|
> |throwExceptionIfInvalid|[boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)| |
> ``` lang=cpp, name=Nada
> function Validate(throwExceptionIfInvalid : Boolean) : Boolean
> ``` 


---  
 

 