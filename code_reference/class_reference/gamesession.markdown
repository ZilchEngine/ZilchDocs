 `Engine`

(NOTE) The GameSession manages all spaces and data for a a game.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ CreateNamedSpace](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gamesession.markdown#createnamedspace-zero-en)|[ AllSpaces](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gamesession.markdown#allspaces-zero-engine-do)|[cog](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/cog.markdown)| |
|[ CreateSpace](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gamesession.markdown#createspace-zero-engine)|[ Focused](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gamesession.markdown#focused-zero-engine-docu)| | |
|[ FindAllSpacesByName](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gamesession.markdown#findallspacesbyname-zero)|[ FullScreen](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gamesession.markdown#fullscreen-zero-engine-d)| | |
|[ FindSpaceByName](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gamesession.markdown#findspacebyname-zero-eng)|[ Paused](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gamesession.markdown#paused-zero-engine-docum)| | |
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gamesession.markdown#gamesession-void)|[ Resolution](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gamesession.markdown#resolution-zero-engine-d)| | |
|[ IsEditorMode](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gamesession.markdown#iseditormode-zero-engine)| | | |
|[ Pause](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gamesession.markdown#pause-void)| | | |
|[ Quit](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gamesession.markdown#quit-void)| | | |
|[ RequestQuit](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gamesession.markdown#requestquit-void)| | | |
|[ Start](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/gamesession.markdown#start-void)| | | |


 #  Properties


---  
 #  AllSpaces : [spacemapvaluerange](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/spacemapvaluerange.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var AllSpaces : SpaceMapValueRange


---  
 #  Focused : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Focused : Boolean


---  
 #  FullScreen : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var FullScreen : Boolean


---  
 #  Paused : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Controls if the game session is paused which prevents updates to all spaces owned by this game.
> ``` lang=cpp, name=Nada
> var Paused : Boolean


---  
 #  Resolution : [real2](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real2.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Resolution : Real2


---  
 #  Methods


---  
 #  CreateNamedSpace : [space](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/space.markdown)

> Create a space from an archetype with the given name.
> |Name|Type|Description|
> |---|---|---|
> |name|[string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> |archetype|[archetype](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/archetype.markdown)| |
> ``` lang=cpp, name=Nada
> function CreateNamedSpace(name : String, archetype : Archetype) : Space
> ``` 


---  
 #  CreateSpace : [space](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/space.markdown)

> Create a space in the game. Use the archetype's name.
> |Name|Type|Description|
> |---|---|---|
> |archetype|[archetype](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/archetype.markdown)| |
> ``` lang=cpp, name=Nada
> function CreateSpace(archetype : Archetype) : Space
> ``` 


---  
 #  FindAllSpacesByName : [spacemapvaluerange](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/spacemapvaluerange.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |name|[string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> ``` lang=cpp, name=Nada
> function FindAllSpacesByName(name : String) : SpaceMapValueRange
> ``` 


---  
 #  FindSpaceByName : [space](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/space.markdown)

> Find a named space.
> |Name|Type|Description|
> |---|---|---|
> |name|[string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> ``` lang=cpp, name=Nada
> function FindSpaceByName(name : String) : Space
> ``` 


---  
 #  GameSession : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function GameSession()
> ``` 


---  
 #  IsEditorMode : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function IsEditorMode() : Boolean
> ``` 


---  
 #  Pause : Void

> Pauses the game session which prevents updates to all spaces owned by this game.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Pause()
> ``` 


---  
 #  Quit : Void

> Quit the game and exit the engine if not in editor.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Quit()
> ``` 


---  
 #  RequestQuit : Void

> Request to quit sending out the GameRequestQuit event.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function RequestQuit()
> ``` 


---  
 #  Start : Void

> Start the game.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Start()
> ``` 


---  
 

 