 `Event` `Networking`



(NOTE) Dispatched after receiving a net user add request.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
| |[ ReturnOurAddResponse](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netpeerreceiveduseraddrequest.markdown#returnouraddresponse-zer)|[event](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/event.markdown)| |
| |[ ReturnOurResponseBundle](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netpeerreceiveduseraddrequest.markdown#returnourresponsebundle)| | |
| |[ ReturnTheirNetUser](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netpeerreceiveduseraddrequest.markdown#returntheirnetuser-zero)| | |
| |[ TheirIpAddress](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netpeerreceiveduseraddrequest.markdown#theiripaddress-zero-engi)| | |
| |[ TheirNetPeerId](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netpeerreceiveduseraddrequest.markdown#theirnetpeerid-zero-engi)| | |
| |[ TheirNetUserId](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netpeerreceiveduseraddrequest.markdown#theirnetuserid-zero-engi)| | |
| |[ TheirRequestBundle](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netpeerreceiveduseraddrequest.markdown#theirrequestbundle-zero)| | |


 #  Properties


---  
 #  ReturnOurAddResponse : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Return: Our add response (accept the add request?).
> ``` lang=cpp, name=Nada
> var ReturnOurAddResponse : Boolean


---  
 #  ReturnOurResponseBundle : [eventbundle](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/eventbundle.markdown)

> Return: Our bundled response event data.
> ``` lang=cpp, name=Nada
> var ReturnOurResponseBundle : EventBundle


---  
 #  ReturnTheirNetUser : [cog](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/cog.markdown)

> Return: Their network user object (must have a NetUser component).
> ``` lang=cpp, name=Nada
> var ReturnTheirNetUser : Cog


---  
 #  TheirIpAddress : [ipaddress](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/ipaddress.markdown)

 `read-only`

> Their IP address (as seen from our perspective).
> ``` lang=cpp, name=Nada
> var TheirIpAddress : IpAddress


---  
 #  TheirNetPeerId : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> Their net peer ID.
> ``` lang=cpp, name=Nada
> var TheirNetPeerId : Integer


---  
 #  TheirNetUserId : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> Their net user ID (released back to the store if not accepted).
> ``` lang=cpp, name=Nada
> var TheirNetUserId : Integer


---  
 #  TheirRequestBundle : [eventbundle](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/eventbundle.markdown)

 `read-only`

> Their bundled request event data.
> ``` lang=cpp, name=Nada
> var TheirRequestBundle : EventBundle


---  
 #  Methods


---  
 

 