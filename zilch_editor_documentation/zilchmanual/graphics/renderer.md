A Renderer in Zilch is simply any Nada Script Component that connects to the RenderTasksUpdate event. Renderer scripts receive this event from a CameraViewport that CogPaths to it (could be the same object) and the tasks added during this event are used during rendering. While active, the RenderTasksUpdate event is sent every frame and the Renderer script can contain any logic desired to dynamically alter the effective rendering pipeline.

 # [Deferred and Forward Renderer](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/zilchmanual/graphics/renderer/deferred_renderer.md)
The default renderers in the core library.

 # [Screen Space Ambient Occlusion](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/zilchmanual/graphics/renderer/ssao.md)
An extension of the `DeferredRenderer` that applies Ambient Occlusion.

 # [Bloom](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/zilchmanual/graphics/renderer/bloom.md)
An extension of the `DeferredRenderer` that applies a bloom effect.

 # Custom Renderers

IMPORTANT:
Zilch allows the user to create their own renderer, but this is only recommended for advanced users and graphics developers. 

 