 `Resource` `Graphics`



(NOTE) How Materials are categorized, determines which graphicals are drawn in a render pass.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ IsSubRenderGroup](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/rendergroup.markdown#issubrendergroup-zero-en)|[ ChildRenderGroups](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/rendergroup.markdown#childrendergroups-zero-e)|[dataresource](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/dataresource.markdown)| |
|[ IsSubRenderGroupOf](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/rendergroup.markdown#issubrendergroupof-zero)|[ GraphicalSortMethod](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/rendergroup.markdown#graphicalsortmethod-zero)| | |
| |[ Materials](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/rendergroup.markdown#materials-zero-engine-do)| | |
| |[ ParentRenderGroup](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/rendergroup.markdown#parentrendergroup-zero-e)| | |
| |[ ReferencedByList](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/rendergroup.markdown#referencedbylist-zero-en)| | |


 #  Properties


---  
 #  ChildRenderGroups : [childrendergrouplist](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/childrendergrouplist.markdown)

 `read-only`

> For assigning child RenderGroups, making this a parent group of everything in the list.
> ``` lang=cpp, name=Nada
> var ChildRenderGroups : ChildRenderGroupList


---  
 #  GraphicalSortMethod : [GraphicalSortMethod](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/enum_reference.markdown#graphicalsortmethod)

> Determines the order that graphicals will be drawn when processed as this RenderGroup.
> ``` lang=cpp, name=Nada
> var GraphicalSortMethod : GraphicalSortMethod


---  
 #  Materials : [materiallist](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/materiallist.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Materials : MaterialList


---  
 #  ParentRenderGroup : [rendergroup](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/rendergroup.markdown)

> RenderGroup that this is a sub group of. Also a sub group of all of its parents.
> ``` lang=cpp, name=Nada
> var ParentRenderGroup : RenderGroup


---  
 #  ReferencedByList : [materiallist](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/materiallist.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var ReferencedByList : MaterialList


---  
 #  Methods


---  
 #  IsSubRenderGroup : [boolean](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Returns whether or not the given RenderGroup is a sub group of this.
> |Name|Type|Description|
> |---|---|---|
> |renderGroup|[rendergroup](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/rendergroup.markdown)| |
> ``` lang=cpp, name=Nada
> function IsSubRenderGroup(renderGroup : RenderGroup) : Boolean
> ``` 


---  
 #  IsSubRenderGroupOf : [boolean](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Returns whether or not this is a sub group of the given RenderGroup.
> |Name|Type|Description|
> |---|---|---|
> |renderGroup|[rendergroup](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/rendergroup.markdown)| |
> ``` lang=cpp, name=Nada
> function IsSubRenderGroupOf(renderGroup : RenderGroup) : Boolean
> ``` 


---  
 

 