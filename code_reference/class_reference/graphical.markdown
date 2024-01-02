 `Component` `Graphics`



(NOTE) Base interface for components that require rendering.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
| |[ GroupSortValue](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/graphical.markdown#groupsortvalue-zero-engi)|[component](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/component.markdown)|[basesprite](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/basesprite.markdown)|
| |[ LocalAabbCenter](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/graphical.markdown#localaabbcenter-zero-eng)| |[debuggraphical](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/debuggraphical.markdown)|
| |[ LocalAabbHalfExtents](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/graphical.markdown#localaabbhalfextents-zer)| |[heightmapmodel](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/heightmapmodel.markdown)|
| |[ Material](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/graphical.markdown#material-zero-engine-doc)| |[model](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/model.markdown)|
| |[ OverrideBoundingBox](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/graphical.markdown#overrideboundingbox-zero)| |[particlesystem](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/particlesystem.markdown)|
| |[ ShaderInputs](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/graphical.markdown#shaderinputs-zero-engine)| |[skinnedmodel](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/skinnedmodel.markdown)|
| |[ ViewCulling](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/graphical.markdown#viewculling-zero-engine)| | |
| |[ VisibilityEvents](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/graphical.markdown#visibilityevents-zero-en)| | |
| |[ Visible](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/graphical.markdown#visible-zero-engine-docu)| | |
| |[ WorldAabb](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/graphical.markdown#worldaabb-zero-engine-do)| | |


 #  Properties


---  
 #  GroupSortValue : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

> Can be used by a RenderGroup to define draw order, from lowest to highest.
> ``` lang=cpp, name=Nada
> var GroupSortValue : Integer


---  
 #  LocalAabbCenter : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Center of the bounding box defined in local space, world transform will be applied.
> ``` lang=cpp, name=Nada
> var LocalAabbCenter : Real3


---  
 #  LocalAabbHalfExtents : [real3](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> Half extents of the bounding box defined in local space, world transform will be applied.
> ``` lang=cpp, name=Nada
> var LocalAabbHalfExtents : Real3


---  
 #  Material : [material](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/material.markdown)

> The composition of shader fragments that determines how the graphical is rendered.
> ``` lang=cpp, name=Nada
> var Material : Material


---  
 #  OverrideBoundingBox : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Manually set the bounding box that is used for frustum culling.
> ``` lang=cpp, name=Nada
> var OverrideBoundingBox : Boolean


---  
 #  ShaderInputs : [shaderinputs](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/shaderinputs.markdown)

> List of shader inputs to be manually overridden only on this object.
> ``` lang=cpp, name=Nada
> var ShaderInputs : ShaderInputs


---  
 #  ViewCulling : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> If the graphical should not be drawn when its bounding volume is outside of the view frustum.
> ``` lang=cpp, name=Nada
> var ViewCulling : Boolean


---  
 #  VisibilityEvents : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> If object receives events when entering/exiting the view of an active camera.
> ``` lang=cpp, name=Nada
> var VisibilityEvents : Boolean


---  
 #  Visible : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> If the graphical should be drawn.
> ``` lang=cpp, name=Nada
> var Visible : Boolean


---  
 #  WorldAabb : [aabb](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/aabb.markdown)

 `read-only`

> The world space axis aligned bounding volume that is used for frustum culling.
> ``` lang=cpp, name=Nada
> var WorldAabb : Aabb


---  
 #  Methods


---  
 

 