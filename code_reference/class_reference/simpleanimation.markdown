 `Component` `Engine`



(NOTE) Plays a single animation on Initialize.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ ChainAnimation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/simpleanimation.markdown#chainanimation-zilch-engi)|[ Animation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/simpleanimation.markdown#animation-zilch-engine-do)|[component](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/component.markdown)| |
|[ CrossBlend](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/simpleanimation.markdown#crossblend-zilch-engine-d)|[ PlayMode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/simpleanimation.markdown#playmode-zilch-engine-doc)| | |
|[ DirectBlend](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/simpleanimation.markdown#directblend-zilch-engine)| | | |
|[ PlayIsolatedAnimation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/simpleanimation.markdown#playisolatedanimation-ze)| | | |
|[ PlaySingle](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/simpleanimation.markdown#playsingle-zilch-engine-d)| | | |
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/simpleanimation.markdown#simpleanimation-void)| | | |


 #  Properties


---  
 #  Animation : [animation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/animation.markdown)

> Animation getter/setter.
> ``` lang=cpp, name=Nada
> var Animation : Animation


---  
 #  PlayMode : [AnimationPlayMode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/enum_reference.markdown#animationplaymode)

> Play mode getter/setter.
> ``` lang=cpp, name=Nada
> var PlayMode : AnimationPlayMode


---  
 #  Methods


---  
 #  ChainAnimation : [animationnode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/animationnode.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |animation|[animation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/animation.markdown)| |
> |playMode|[AnimationPlayMode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/enum_reference.markdown#animationplaymode)| |
> ``` lang=cpp, name=Nada
> function ChainAnimation(animation : Animation, playMode : AnimationPlayMode) : AnimationNode
> ``` 


---  
 #  CrossBlend : [animationnode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/animationnode.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |animation|[animation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/animation.markdown)| |
> |transitionTime|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |playMode|[AnimationPlayMode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/enum_reference.markdown#animationplaymode)| |
> ``` lang=cpp, name=Nada
> function CrossBlend(animation : Animation, transitionTime : Real, playMode : AnimationPlayMode) : AnimationNode
> ``` 


---  
 #  DirectBlend : [animationnode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/animationnode.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |animation|[animation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/animation.markdown)| |
> |transitionTime|[real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)| |
> |playMode|[AnimationPlayMode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/enum_reference.markdown#animationplaymode)| |
> ``` lang=cpp, name=Nada
> function DirectBlend(animation : Animation, transitionTime : Real, playMode : AnimationPlayMode) : AnimationNode
> ``` 


---  
 #  PlayIsolatedAnimation : [animationnode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/animationnode.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |animation|[animation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/animation.markdown)| |
> |rootBone|[cog](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/cog.markdown)| |
> |playMode|[AnimationPlayMode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/enum_reference.markdown#animationplaymode)| |
> ``` lang=cpp, name=Nada
> function PlayIsolatedAnimation(animation : Animation, rootBone : Cog, playMode : AnimationPlayMode) : AnimationNode
> ``` 


---  
 #  PlaySingle : [animationnode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/animationnode.markdown)

> Play animations directly.
> |Name|Type|Description|
> |---|---|---|
> |animation|[animation](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/animation.markdown)| |
> |playMode|[AnimationPlayMode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/enum_reference.markdown#animationplaymode)| |
> ``` lang=cpp, name=Nada
> function PlaySingle(animation : Animation, playMode : AnimationPlayMode) : AnimationNode
> ``` 


---  
 #  SimpleAnimation : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function SimpleAnimation()
> ``` 


---  
 

 