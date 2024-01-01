 `Engine`

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ BeginBatch](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#beginbatch-void)|[ ActiveBatchName](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#activebatchname-zero-eng)|[referencecountedeventobject](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/referencecountedeventobject.markdown)| |
|[ ClearAll](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#clearall-void)|[ Commands](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#commands-zero-engine-doc)| | |
|[ ClearRedo](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#clearredo-void)|[ RedoCommands](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#redocommands-zero-engine)| | |
|[ ClearUndo](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#clearundo-void)| | | |
|[ DestroyObject](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#destroyobject-void)| | | |
|[ EndBatch](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#endbatch-void)| | | |
|[ IsListeningForSideEffects](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#islisteningforsideeffect)| | | |
|[ MarkPropertyAsModified](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#markpropertyasmodified-v)| | | |
|[ ObjectCreated](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#objectcreated-void)| | | |
|[ Constructor](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#operationqueue-void)| | | |
|[ PopSubPropertyContext](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#popsubpropertycontext-vo)| | | |
|[ QueueRegisteredSideEffects](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#queueregisteredsideeffec)| | | |
|[ Redo](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#redo-void)| | | |
|[ RegisterSideEffect](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#registersideeffect-void)| | | |
|[ SaveObjectState](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#saveobjectstate-void)| | | |
|[ StartListeningForSideEffects](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#startlisteningforsideeff)| | | |
|[ Undo](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationqueue.markdown#undo-void)| | | |


 #  Properties


---  
 #  ActiveBatchName : [string](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/string.markdown)

> 
> ``` lang=cpp, name=Nada
> var ActiveBatchName : String


---  
 #  Commands : [operationlistrange](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationlistrange.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var Commands : OperationListRange


---  
 #  RedoCommands : [operationlistrange](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operationlistrange.markdown)

 `read-only`

> 
> ``` lang=cpp, name=Nada
> var RedoCommands : OperationListRange


---  
 #  Methods


---  
 #  BeginBatch : Void

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function BeginBatch()
> ``` 


---  
 #  BeginBatch : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[string](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> ``` lang=cpp, name=Nada
> function BeginBatch(p0 : String)
> ``` 


---  
 #  ClearAll : Void

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function ClearAll()
> ``` 


---  
 #  ClearRedo : Void

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function ClearRedo()
> ``` 


---  
 #  ClearUndo : Void

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function ClearUndo()
> ``` 


---  
 #  DestroyObject : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[cog](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/cog.markdown)| |
> ``` lang=cpp, name=Nada
> function DestroyObject(p0 : Cog)
> ``` 


---  
 #  EndBatch : Void

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function EndBatch()
> ``` 


---  
 #  IsListeningForSideEffects : [boolean](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `static`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function IsListeningForSideEffects() : Boolean
> ``` 


---  
 #  MarkPropertyAsModified : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[component](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/component.markdown)| |
> |p1|[string](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> ``` lang=cpp, name=Nada
> function MarkPropertyAsModified(p0 : Component, p1 : String)
> ``` 


---  
 #  ObjectCreated : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[cog](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/cog.markdown)| |
> ``` lang=cpp, name=Nada
> function ObjectCreated(p0 : Cog)
> ``` 


---  
 #  OperationQueue : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function OperationQueue()
> ``` 


---  
 #  PopSubPropertyContext : Void

 `static`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function PopSubPropertyContext()
> ``` 


---  
 #  QueueRegisteredSideEffects : Void

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function QueueRegisteredSideEffects()
> ``` 


---  
 #  Redo : Void

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Redo()
> ``` 


---  
 #  Redo : [boolean](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[operation](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operation.markdown)| |
> ``` lang=cpp, name=Nada
> function Redo(p0 : Operation) : Boolean
> ``` 


---  
 #  RegisterSideEffect : Void

 `static`

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[anyhandle](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/anyhandle.markdown)| |
> |p1|[string](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> |p2|T| |
> ``` lang=cpp, name=Nada
> function RegisterSideEffect(p0 : AnyHandle, p1 : String, p2 : T)
> ``` 


---  
 #  SaveObjectState : Void

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[cog](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/cog.markdown)| |
> ``` lang=cpp, name=Nada
> function SaveObjectState(p0 : Cog)
> ``` 


---  
 #  StartListeningForSideEffects : Void

 `static`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function StartListeningForSideEffects()
> ``` 


---  
 #  Undo : Void

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Undo()
> ``` 


---  
 #  Undo : [boolean](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> 
> |Name|Type|Description|
> |---|---|---|
> |p0|[operation](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/operation.markdown)| |
> ``` lang=cpp, name=Nada
> function Undo(p0 : Operation) : Boolean
> ``` 


---  
 

 