 `Networking`



(NOTE) Network Property. Manages the replication of a single property on the network.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
| |[ LastChangeTimePassed](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netproperty.markdown#lastchangetimepassed-zer)|[safeid32object](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/safeid32object.markdown)| |
| |[ LastChangeTimestamp](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netproperty.markdown#lastchangetimestamp-zero)| | |
| |[ Name](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netproperty.markdown#name-zilch-engine-documen)| | |
| |[ NetChannel](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netproperty.markdown#netchannel-zilch-engine-d)| | |
| |[ NetPropertyType](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netproperty.markdown#netpropertytype-zilch-eng)| | |


 #  Properties


---  
 #  LastChangeTimePassed : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only`

> Elapsed time passed since this net property was last changed, else 0.
> ``` lang=cpp, name=Nada
> var LastChangeTimePassed : Real


---  
 #  LastChangeTimestamp : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only`

> Timestamp indicating when this net property was last changed, else 0.
> ``` lang=cpp, name=Nada
> var LastChangeTimestamp : Real


---  
 #  Name : [string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)

 `read-only`

> Net property name.
> ``` lang=cpp, name=Nada
> var Name : String


---  
 #  NetChannel : [netchannel](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netchannel.markdown)

 `read-only`

> Operating net channel.
> ``` lang=cpp, name=Nada
> var NetChannel : NetChannel


---  
 #  NetPropertyType : [netpropertytype](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netpropertytype.markdown)

 `read-only`

> Operating net property type.
> ``` lang=cpp, name=Nada
> var NetPropertyType : NetPropertyType


---  
 #  Methods


---  
 

 