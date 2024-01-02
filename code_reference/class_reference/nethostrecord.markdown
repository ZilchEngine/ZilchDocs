 `Networking`

(NOTE) NetHostRecord. A record that contains the basic information of a game server. After a certain lifetime records expire on the master server.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
| |[ BasicHostInfo](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/nethostrecord.markdown#basichostinfo-zilch-engin)|[safeid32](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/safeid32.markdown)| |
| |[ IpAddress](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/nethostrecord.markdown#ipaddress-zilch-engine-do)| | |
| |[ Lifetime](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/nethostrecord.markdown#lifetime-zilch-engine-doc)| | |


 #  Properties


---  
 #  BasicHostInfo : [eventbundle](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/eventbundle.markdown)

 `read-only`

> The info published along with their record. Contains game server specific data.
> ``` lang=cpp, name=Nada
> var BasicHostInfo : EventBundle


---  
 #  IpAddress : [ipaddress](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ipaddress.markdown)

 `read-only`

> The IpAddress associated with this record. This is who published it.
> ``` lang=cpp, name=Nada
> var IpAddress : IpAddress


---  
 #  Lifetime : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only`

> How long has this record been alive in seconds?
> ``` lang=cpp, name=Nada
> var Lifetime : Real


---  
 #  Methods


---  
 

 