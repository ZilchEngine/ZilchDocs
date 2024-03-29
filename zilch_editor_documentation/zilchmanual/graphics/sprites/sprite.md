The [Sprite](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/code_reference/class_reference/sprite.md) component is used to add and control two-dimensional artwork on a `Cog`. A Sprite can be used for many things from a simple poster on a three-dimensional wall to all the visual elements of a 2D game. The Sprite Component can be added to any game object with a `Transform` component.

(NOTE)**Recommended Reading** This section only covers the properties that are specific to Sprites, and doesn't cover the properties shared by the [BaseSprite](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/code_reference/class_reference/basesprite.md).
 # Common Uses

 - Characters and other artwork in a two dimensional project
 - Placing 2D pictures into a 3D landscape
 - 2D animations 

 # Using Sprites
 ## Creating Sprites
Sprites can be made in one of two ways. Typically they will be made by using [Command](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/zilchmanual/editor/editorcommands/commands.md) : CreateSprite ; however, the `Sprite` component can also be added to any game object.  The actual image is defined by the SpriteSource resource property, and all other properties control how the sprite is displayed:



![SpriteProperties](https://raw.githubusercontent.com/ZilchEngine/ZilchFiles/master/doc_files/47784.png) *Sprite Component UI*


 ## Adding a SpriteSource
NOTE: Zilch Engine only allows the importing of .PNG type images.

It is possible to add SpriteSources of your own as well. By simply grabbing the file on your computer and dragging it into the Editor window, Zilch Engine will import the chosen asset. Alternatively, one can invoke the [Command](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/zilchmanual/editor/editorcommands/commands.md) : Add  and select `SpriteSource  > IMPORT SPRITESOURCE`:



![image](https://raw.githubusercontent.com/ZilchEngine/ZilchFiles/master/doc_files/45986.png) *Adding a `SpriteSource`*


A window will open where the user may select the image or images to import, keeping the saved Resolution and Size. Once imported, these files can then be used to create single frame images or multi-frame animations using the [Sprite Importer](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/zilchmanual/graphics/sprites/spriteimporter.md).

 ## Changing SpriteSources
After importing one's images, the next step is to change the SpriteSource resource Property on the Sprite Component to the resource created by the imported image. This is done by clicking on the current `SpriteSource` and finding the imported image in the drop-down menu that opens.



![ChangeSpriteSource](https://raw.githubusercontent.com/ZilchEngine/ZilchFiles/master/doc_files/47786.png) *Changing `SpriteSources`*


 ## Flipping Sprite Orientation
A quick and efficient way to change the sprite orientation is to use some combination of FlipX checkBox and FlipY checkBox variables.



![Flip](https://raw.githubusercontent.com/ZilchEngine/ZilchFiles/master/doc_files/47789.gif) *Flipping Sprite Orientation*


 ## Sprites As Animations
To use Sprites as animations rather than still images, please refer to [Sprite Source Editor](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/zilchmanual/graphics/sprites/spritesourceeditor.md).

 # Related Materials
 ## Manual Pages
- [Base Sprite](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/zilchmanual/graphics/sprites/basesprite.md)
- [SpriteLayers and SpriteLayerOrder](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/zilchmanual/graphics/sprites/spritelayer.md)
- [Sprite Source Editor](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/zilchmanual/graphics/sprites/spritesourceeditor.md)


 ## Reference Pages
- [SpriteSource](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/code_reference/class_reference/spritesource.md) 
- [Sprite](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/code_reference/class_reference/sprite.md) 
- [Event](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/code_reference/class_reference/event.md) 
- [BaseSprite](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/code_reference/class_reference/basesprite.md)  

 