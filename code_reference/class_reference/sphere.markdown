 `Geometry`

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Expand](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/sphere.markdown#expand-void)|[ Center](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/sphere.markdown#center-zero-engine-docum)| | |
|[ Overlap](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/sphere.markdown#overlap-zero-engine-docu)|[ Radius](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/sphere.markdown#radius-zero-engine-docum)| | |
|[ Overlaps](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/sphere.markdown#overlaps-zero-engine-doc)|[ SurfaceArea](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/sphere.markdown#surfacearea-zero-engine)| | |
|[ Constructor](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/sphere.markdown#sphere-void)|[ Volume](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/sphere.markdown#volume-zero-engine-docum)| | |


 #  Properties


---  
 #  Center : [real3](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real3.markdown)

> 
> ``` lang=cpp, name=Nada
> var Center : Real3


---  
 #  Radius : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

> 
> ``` lang=cpp, name=Nada
> var Radius : Real


---  
 #  SurfaceArea : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var SurfaceArea : Real


---  
 #  Volume : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Volume : Real


---  
 #  Methods


---  
 #  Expand : Void

> Expand this sphere to contain the given point.
> |Name|Type|Description|
> |---|---|---|
> |p0|[real3](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> ``` lang=cpp, name=Nada
> function Expand(p0 : Real3)
> ``` 


---  
 #  Expand : [sphere](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/sphere.markdown)

 `static`

> Creates a sphere that contains the given sphere and point.
> |Name|Type|Description|
> |---|---|---|
> |p0|[sphere](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/sphere.markdown)| |
> |p1|[real3](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> ``` lang=cpp, name=Nada
> function Expand(p0 : Sphere, p1 : Real3) : Sphere
> ``` 


---  
 #  Overlap : [boolean](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> This function is deprecated. Use Overlaps instead
> |Name|Type|Description|
> |---|---|---|
> |p0|[sphere](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/sphere.markdown)| |
> ``` lang=cpp, name=Nada
> function Overlap(p0 : Sphere) : Boolean
> ``` 


---  
 #  Overlaps : [boolean](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Does this sphere overlap/intersect the given sphere?
> |Name|Type|Description|
> |---|---|---|
> |p0|[sphere](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/sphere.markdown)| |
> ``` lang=cpp, name=Nada
> function Overlaps(p0 : Sphere) : Boolean
> ``` 


---  
 #  Sphere : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Sphere()
> ``` 


---  
 #  Sphere : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |center|[real3](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real3.markdown)| |
> |radius|[real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> ``` lang=cpp, name=Nada
> function Sphere(center : Real3, radius : Real)
> ``` 


---  
 #  Sphere : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[sphere](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/sphere.markdown)| |
> ``` lang=cpp, name=Nada
> function Sphere(p0 : Sphere)
> ``` 


---  
 

 