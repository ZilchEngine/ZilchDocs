[TextBlock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/textblock.md) resources are used to organize and format the visual style of SpriteText in a project. They are a very helpful resource any time more than a single sentence of text needs to be used.

NOTE: **Recommended Reading**  This section covers topics that may not have been addressed yet. To learn or review those topics, please see: [Area component](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/zilchmanual/graphics/sprites/area.md), [Sprites](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/zilchmanual/graphics/sprites.md), & [SpriteText](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/zilchmanual/graphics/sprites/spritetext.md)

 # Common Uses

 - Organizing on screen text
 - High volume text data entry
 - Easier text swapping

 # Using a TextBlock
Adding Text using the TextBlock requires two elements: a TextBlock resource and a [SpriteText](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/spritetext.md) component. To get the text from the TextBlock into the SpriteText you will need a component like this

```lang=csharp
[RunInEditor]
class SpriteTextBlock : NadaComponent
{
  [Dependency]
  var SpriteText : SpriteText;
  
  [Editable]
  var TextBlock : TextBlock
  {
    get { return this.Block; }
    set
    {
      this.Block = value;
      this.SpriteText.Text = this.Text;
    }
  }
  
  var Block : TextBlock = null;
  
  var Text : String
  {
    get
    {
      if(this.TextBlock != null)
        return this.TextBlock.Text;
      else
        return "";
    }
  }
  
  function Initialize(init : CogInitializer)
  {
  }
}

```

The `SpriteTextBlock` component is added to the object whose SpriteText needs to be changed. These two work in tandem to change the `Text` property of the SpriteText component. To create a new TextBlock, use TextBlock requires two elements: a TextBlock resource and and a `SpriteTextBlock` component. The `SpriteTextBlock` component is added to the object whose SpriteText needs to be changed. These two work in tandem to change the `Text` property of the SpriteText component. To create a new TextBlock, use [commands](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/zilchmanual/editor/editorcommands/commands.md) : [Add](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/command_reference.md#add) and select TextBlock from the resource list. This will open a new TextBlock in a new Tab where text may be written. After entering the desired text, simply add the `SpriteTextBlock` component to the Game Object and set the TextBlock property to the new TextBlock. 


![image](https://raw.githubusercontent.com/ZilchEngine/ZilchFiles/master/doc_files/47035.png)




![TextBlock](https://raw.githubusercontent.com/ZilchEngine/ZilchFiles/master/doc_files/47039.gif)


As can be seen in the example above, one feature of TextBlock is that when applied to a SpriteTextBlock, the formatting in regards to line breaks is kept. One problem that remains, however, is that changing the `Align` property of the SpriteText component will change the Transform of the of the text itself, instead of adjusting the alignment.
The `Area` component can help solve this problem. While SpriteTextBlock keeps the formatting of the TextBlock, it has no alignment options of its own. Adding the Area Component allows the user to define the area the text is displayed in, changing the alignment of the text inside that area. It will also use word wrapping to make sure no text spills outside of the defined area.

---

 # Related Materials
 ## Manual Pages
- [Area component](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation.md)
- [Sprites](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation.md)
- [SpriteText](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation.md)
- [commands](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/zilchmanual/editor/editorcommands/commands.md)

 ## Reference Pages
- [textblock](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/textblock.md)
- [SpriteText](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/spritetext.md)  

 