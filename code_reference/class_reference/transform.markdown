 `Component` `Engine`



(NOTE) Transform component class. The transform component provides the position, rotation and scale of an object.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ RotateAnglesLocal](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#rotateangleslocal-void)|[ EulerAngles](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#eulerangles-zero-engine)|[component](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/component.markdown)| |
|[ RotateAnglesWorld](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#rotateanglesworld-void)|[ LocalRotation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#localrotation-zero-engin)| | |
|[ RotateAround](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#rotatearound-void)|[ LocalScale](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#localscale-zero-engine-d)| | |
|[ RotateLocal](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#rotatelocal-void)|[ LocalTranslation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#localtranslation-zero-en)| | |
|[ RotateWorld](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#rotateworld-void)|[ Parent](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#parent-zero-engine-docum)| | |
|[ SetEulerAnglesXYZ](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#seteuleranglesxyz-void)|[ Rotation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#rotation-zero-engine-doc)| | |
|[ SetRotationBases](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#setrotationbases-void)|[ Scale](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#scale-zero-engine-docume)| | |
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#transform-void)|[ Translation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#translation-zero-engine)| | |
|[ TransformNormal](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#transformnormal-zero-eng)|[ WorldMatrix](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#worldmatrix-zero-engine)| | |
|[ TransformNormalInverse](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#transformnormalinverse-z)|[ WorldRotation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#worldrotation-zero-engin)| | |
|[ TransformNormalLocal](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#transformnormallocal-zer)|[ WorldScale](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#worldscale-zero-engine-d)| | |
|[ TransformPoint](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#transformpoint-zero-engi)|[ WorldTranslation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#worldtranslation-zero-en)| | |
|[ TransformPointInverse](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#transformpointinverse-ze)| | | |
|[ TransformPointLocal](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown#transformpointlocal-zero)| | | |


 #  Properties


---  
 #  EulerAngles : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> The rotation of the transform as an Euler angle vector in radians.
> ``` lang=cpp, name=Nada
> var EulerAngles : Real3


---  
 #  LocalRotation : [quaternion](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/quaternion.markdown)

> Local rotation relative to parent.
> ``` lang=cpp, name=Nada
> var LocalRotation : Quaternion


---  
 #  LocalScale : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Local Scale relative to parent.
> ``` lang=cpp, name=Nada
> var LocalScale : Real3


---  
 #  LocalTranslation : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Local Translation relative to parent.
> ``` lang=cpp, name=Nada
> var LocalTranslation : Real3


---  
 #  Parent : [transform](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/transform.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Parent : Transform


---  
 #  Rotation : [quaternion](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/quaternion.markdown)

> Local rotation relative to parent.
> ``` lang=cpp, name=Nada
> var Rotation : Quaternion


---  
 #  Scale : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Local Scale relative to parent.
> ``` lang=cpp, name=Nada
> var Scale : Real3


---  
 #  Translation : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Local Translation relative to parent.
> ``` lang=cpp, name=Nada
> var Translation : Real3


---  
 #  WorldMatrix : [real4x4](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real4x4.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var WorldMatrix : Real4x4


---  
 #  WorldRotation : [quaternion](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/quaternion.markdown)

> Rotation in World Space.
> ``` lang=cpp, name=Nada
> var WorldRotation : Quaternion


---  
 #  WorldScale : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Scale in World Space.
> ``` lang=cpp, name=Nada
> var WorldScale : Real3


---  
 #  WorldTranslation : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Translation in World Space.
> ``` lang=cpp, name=Nada
> var WorldTranslation : Real3


---  
 #  Methods


---  
 #  RotateAnglesLocal : Void

> Rotate object in local space by the given Euler angle vector (in radians).
> |Name|Type|Description|
> |---|---|---|
> |angles|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> ``` lang=cpp, name=Nada
> function RotateAnglesLocal(angles : Real3)
> ``` 


---  
 #  RotateAnglesWorld : Void

> Rotate object in world space by the given Euler angle vector (in radians).
> |Name|Type|Description|
> |---|---|---|
> |angles|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> ``` lang=cpp, name=Nada
> function RotateAnglesWorld(angles : Real3)
> ``` 


---  
 #  RotateAround : Void

> Rotate around a given point with the given rotation.
> |Name|Type|Description|
> |---|---|---|
> |point|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> |rotation|[quaternion](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/quaternion.markdown)| |
> ``` lang=cpp, name=Nada
> function RotateAround(point : Real3, rotation : Quaternion)
> ``` 


---  
 #  RotateLocal : Void

> Rotate object in local space.
> |Name|Type|Description|
> |---|---|---|
> |rotation|[quaternion](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/quaternion.markdown)| |
> ``` lang=cpp, name=Nada
> function RotateLocal(rotation : Quaternion)
> ``` 


---  
 #  RotateWorld : Void

> Rotate object in world space.
> |Name|Type|Description|
> |---|---|---|
> |rotation|[quaternion](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/quaternion.markdown)| |
> ``` lang=cpp, name=Nada
> function RotateWorld(rotation : Quaternion)
> ``` 


---  
 #  SetEulerAnglesXYZ : Void

> Sets the rotation of the transform by the given Euler angles in radians.
> |Name|Type|Description|
> |---|---|---|
> |xRadians|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |yRadians|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |zRadians|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function SetEulerAnglesXYZ(xRadians : Real, yRadians : Real, zRadians : Real)
> ``` 


---  
 #  SetRotationBases : Void

> Generates a rotation matrix from the given bases.
> |Name|Type|Description|
> |---|---|---|
> |facing|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> |up|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> |right|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> ``` lang=cpp, name=Nada
> function SetRotationBases(facing : Real3, up : Real3, right : Real3)
> ``` 


---  
 #  Transform : Void

 `constructor`

> Constructor / Destructor.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Transform()
> ``` 


---  
 #  TransformNormal : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Transforms a local normal (direction) into world space.
> |Name|Type|Description|
> |---|---|---|
> |normal|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> ``` lang=cpp, name=Nada
> function TransformNormal(normal : Real3) : Real3
> ``` 


---  
 #  TransformNormalInverse : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Transforms a world normal (direction) into local space.
> |Name|Type|Description|
> |---|---|---|
> |normal|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> ``` lang=cpp, name=Nada
> function TransformNormalInverse(normal : Real3) : Real3
> ``` 


---  
 #  TransformNormalLocal : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Transforms a normal by the local matrix (ignores parent's transform) Needed now because there is no quaternion times vector in script.
> |Name|Type|Description|
> |---|---|---|
> |normal|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> ``` lang=cpp, name=Nada
> function TransformNormalLocal(normal : Real3) : Real3
> ``` 


---  
 #  TransformPoint : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Transforms a local point into world space.
> |Name|Type|Description|
> |---|---|---|
> |point|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> ``` lang=cpp, name=Nada
> function TransformPoint(point : Real3) : Real3
> ``` 


---  
 #  TransformPointInverse : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Transforms a world point into local space.
> |Name|Type|Description|
> |---|---|---|
> |point|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> ``` lang=cpp, name=Nada
> function TransformPointInverse(point : Real3) : Real3
> ``` 


---  
 #  TransformPointLocal : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Transforms a point by the local matrix (ignores parent's transform)
> |Name|Type|Description|
> |---|---|---|
> |point|[real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> ``` lang=cpp, name=Nada
> function TransformPointLocal(point : Real3) : Real3
> ``` 


---  
 

 