 `Component` `Networking`



(NOTE) Network Object. Manages the replication of a single object on the network.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ DispatchBroadcast](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#dispatchbroadcast-void)|[ AcceptIncomingChanges](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#acceptincomingchanges-ze)|[component](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/component.markdown)|[netpeer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netpeer.markdown)|
|[ DispatchLocal](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#dispatchlocal-void)|[ AccurateTimestampOnChange](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#accuratetimestamponchang)| |[netspace](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netspace.markdown)|
|[ DispatchLocalAndBroadcast](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#dispatchlocalandbroadcas)|[ AccurateTimestampOnOffline](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#accuratetimestamponoffli)| |[netuser](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netuser.markdown)|
|[ DispatchLocalAndRemote](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#dispatchlocalandremote-v)|[ AccurateTimestampOnOnline](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#accuratetimestampononlin)| | |
|[ DispatchRemote](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#dispatchremote-void)|[ AllowNapping](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#allownapping-zilch-engine)| | |
|[ Forget](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#forget-zilch-engine-docum)|[ AutomaticChannel](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#automaticchannel-zilch-en)| | |
|[ GetNetChannel](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#getnetchannel-zilch-engin)|[ DetectOutgoingChanges](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#detectoutgoingchanges-ze)| | |
|[ HasNetChannel](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#hasnetchannel-zilch-engin)|[ IsClient](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isclient-zilch-engine-doc)| | |
|[ IsOwnedByPeer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isownedbypeer-zilch-engin)|[ IsClientAndMine](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isclientandmine-zilch-eng)| | |
|[ IsOwnedByUser](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isownedbyuser-zilch-engin)|[ IsClientButNotMine](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isclientbutnotmine-zero)| | |
|[ Constructor](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#netobject-void)|[ IsClientOrOffline](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isclientoroffline-zilch-e)| | |
|[ ReplicateNow](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#replicatenow-zilch-engine)|[ IsClientOrServer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isclientorserver-zilch-en)| | |
|[ SelectRemote](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#selectremote-zilch-engine)|[ IsMine](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#ismine-zilch-engine-docum)| | |
|[ SetNetUserOwnerDown](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#setnetuserownerdown-void)|[ IsNapping](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isnapping-zilch-engine-do)| | |
|[ SetNetUserOwnerUp](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#setnetuserownerup-void)|[ IsNotMine](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isnotmine-zilch-engine-do)| | |
|[ TakeNap](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#takenap-void)|[ IsNotOwnedByAUser](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isnotownedbyauser-zilch-e)| | |
|[ WakeUp](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#wakeup-void)|[ IsOffline](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isoffline-zilch-engine-do)| | |
| |[ IsOfflineAndMine](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isofflineandmine-zilch-en)| | |
| |[ IsOfflineButNotMine](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isofflinebutnotmine-zero)| | |
| |[ IsOnline](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isonline-zilch-engine-doc)| | |
| |[ IsOwnedByAUser](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isownedbyauser-zilch-engi)| | |
| |[ IsServer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isserver-zilch-engine-doc)| | |
| |[ IsServerAndMine](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isserverandmine-zilch-eng)| | |
| |[ IsServerButNotMine](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isserverbutnotmine-zero)| | |
| |[ IsServerOrOffline](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#isserveroroffline-zilch-e)| | |
| |[ LastChangeTimePassed](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#lastchangetimepassed-zer)| | |
| |[ LastChangeTimestamp](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#lastchangetimestamp-zero)| | |
| |[ NetObjectId](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#netobjectid-zilch-engine)| | |
| |[ NetPropertyInfos](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#netpropertyinfos-zilch-en)| | |
| |[ NetUserOwner](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#netuserowner-zilch-engine)| | |
| |[ NetUserOwnerPath](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#netuserownerpath-zilch-en)| | |
| |[ NetUserOwnerPeerId](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#netuserownerpeerid-zero)| | |
| |[ NetUserOwnerUserId](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#netuserowneruserid-zero)| | |
| |[ OfflineTimePassed](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#offlinetimepassed-zilch-e)| | |
| |[ OfflineTimestamp](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#offlinetimestamp-zilch-en)| | |
| |[ OnlineTimePassed](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#onlinetimepassed-zilch-en)| | |
| |[ OnlineTimestamp](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#onlinetimestamp-zilch-eng)| | |
| |[ Role](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netobject.markdown#role-zilch-engine-documen)| | |


 #  Properties


---  
 #  AcceptIncomingChanges : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Controls whether or not net channels on this net object may accept incoming changes.
> ``` lang=cpp, name=Nada
> var AcceptIncomingChanges : Boolean


---  
 #  AccurateTimestampOnChange : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Controls whether or not the net object will serialize an accurate timestamp value when changed (on any net channel), or will instead accept an estimated timestamp value. (Enabling this will override the corresponding net channel type setting for all net channels added to this net object)
> ``` lang=cpp, name=Nada
> var AccurateTimestampOnChange : Boolean


---  
 #  AccurateTimestampOnOffline : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Controls whether or not the net object will serialize an accurate timestamp value when taken offline, or will instead accept an estimated timestamp value.
> ``` lang=cpp, name=Nada
> var AccurateTimestampOnOffline : Boolean


---  
 #  AccurateTimestampOnOnline : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Controls whether or not the net object will serialize an accurate timestamp value when brought online, or will instead accept an estimated timestamp value.
> ``` lang=cpp, name=Nada
> var AccurateTimestampOnOnline : Boolean


---  
 #  AllowNapping : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Controls whether or not net channels on this net object may nap (perform change detection on longer intervals) if they haven't changed in a while.
> ``` lang=cpp, name=Nada
> var AllowNapping : Boolean


---  
 #  AutomaticChannel : [netchannelconfig](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netchannelconfig.markdown)

> Returns the automatic net channel configuration resource (assigned to net properties unless another channel is specified).
> ``` lang=cpp, name=Nada
> var AutomaticChannel : NetChannelConfig


---  
 #  DetectOutgoingChanges : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Controls whether or not net channels on this net object may detect outgoing changes.
> ``` lang=cpp, name=Nada
> var DetectOutgoingChanges : Boolean


---  
 #  IsClient : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if our open peer's network role is client, else false.
> ``` lang=cpp, name=Nada
> var IsClient : Boolean


---  
 #  IsClientAndMine : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if our open peer's network role is client and the net object is conceptually owned by a user added by our local peer, else false.
> ``` lang=cpp, name=Nada
> var IsClientAndMine : Boolean


---  
 #  IsClientButNotMine : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if our open peer's network role is client and the net object is not conceptually owned by a user added by our local peer, else false.
> ``` lang=cpp, name=Nada
> var IsClientButNotMine : Boolean


---  
 #  IsClientOrOffline : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if our open peer's network role is client or offline, else false.
> ``` lang=cpp, name=Nada
> var IsClientOrOffline : Boolean


---  
 #  IsClientOrServer : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if our open peer's network role is client or server, else false.
> ``` lang=cpp, name=Nada
> var IsClientOrServer : Boolean


---  
 #  IsMine : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if the net object is conceptually owned by a user added by our local peer, else false.
> ``` lang=cpp, name=Nada
> var IsMine : Boolean


---  
 #  IsNapping : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if all net channels on this net object are napping (performing change detection on longer intervals), else false.
> ``` lang=cpp, name=Nada
> var IsNapping : Boolean


---  
 #  IsNotMine : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if the net object is not conceptually owned by a user added by our local peer, else false.
> ``` lang=cpp, name=Nada
> var IsNotMine : Boolean


---  
 #  IsNotOwnedByAUser : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if the net object is not conceptually owned by a user, else false.
> ``` lang=cpp, name=Nada
> var IsNotOwnedByAUser : Boolean


---  
 #  IsOffline : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if our open peer's network role is offline, else false.
> ``` lang=cpp, name=Nada
> var IsOffline : Boolean


---  
 #  IsOfflineAndMine : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if our open peer's network role is offline and the net object is conceptually owned by a user added by our local peer, else false.
> ``` lang=cpp, name=Nada
> var IsOfflineAndMine : Boolean


---  
 #  IsOfflineButNotMine : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if our open peer's network role is offline and the net object is not conceptually owned by a user added by our local peer, else false.
> ``` lang=cpp, name=Nada
> var IsOfflineButNotMine : Boolean


---  
 #  IsOnline : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if the net object is online, else false.
> ``` lang=cpp, name=Nada
> var IsOnline : Boolean


---  
 #  IsOwnedByAUser : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if the net object is conceptually owned by a user, else false.
> ``` lang=cpp, name=Nada
> var IsOwnedByAUser : Boolean


---  
 #  IsServer : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if our open peer's network role is server, else false.
> ``` lang=cpp, name=Nada
> var IsServer : Boolean


---  
 #  IsServerAndMine : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if our open peer's network role is server and the net object is conceptually owned by a user added by our local peer, else false.
> ``` lang=cpp, name=Nada
> var IsServerAndMine : Boolean


---  
 #  IsServerButNotMine : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if our open peer's network role is server and the net object is not conceptually owned by a user added by our local peer, else false.
> ``` lang=cpp, name=Nada
> var IsServerButNotMine : Boolean


---  
 #  IsServerOrOffline : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

 `read-only`

> Returns true if our open peer's network role is server or offline, else false.
> ``` lang=cpp, name=Nada
> var IsServerOrOffline : Boolean


---  
 #  LastChangeTimePassed : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only`

> Elapsed time passed since this net object was last changed, else 0.
> ``` lang=cpp, name=Nada
> var LastChangeTimePassed : Real


---  
 #  LastChangeTimestamp : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only`

> Timestamp indicating when this net object was last changed, else 0.
> ``` lang=cpp, name=Nada
> var LastChangeTimestamp : Real


---  
 #  NetObjectId : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> Returns the net object ID (set if the net object is live), else 0.
> ``` lang=cpp, name=Nada
> var NetObjectId : Integer


---  
 #  NetPropertyInfos : [netpropertyinfos](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netpropertyinfos.markdown)

> Net property infos added through the property grid.
> ``` lang=cpp, name=Nada
> var NetPropertyInfos : NetPropertyInfos


---  
 #  NetUserOwner : [cog](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/cog.markdown)

> Returns the network user this object conceptually belongs to, else nullptr.
> ``` lang=cpp, name=Nada
> var NetUserOwner : Cog


---  
 #  NetUserOwnerPath : [cogpath](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/cogpath.markdown)

 `read-only`

> Path to the network user this object conceptually belongs to, else empty cog path.
> ``` lang=cpp, name=Nada
> var NetUserOwnerPath : CogPath


---  
 #  NetUserOwnerPeerId : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> Returns the network peer identifier of the peer who added the user this object conceptually belongs to, else 0.
> ``` lang=cpp, name=Nada
> var NetUserOwnerPeerId : Integer


---  
 #  NetUserOwnerUserId : [integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)

 `read-only`

> Returns the network user identifier of the user this object conceptually belongs to, else 0.
> ``` lang=cpp, name=Nada
> var NetUserOwnerUserId : Integer


---  
 #  OfflineTimePassed : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only`

> Elapsed time passed since this net object was taken offline, else 0.
> ``` lang=cpp, name=Nada
> var OfflineTimePassed : Real


---  
 #  OfflineTimestamp : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only`

> Timestamp indicating when this net object was taken offline, else 0.
> ``` lang=cpp, name=Nada
> var OfflineTimestamp : Real


---  
 #  OnlineTimePassed : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only`

> Elapsed time passed since this net object was brought online, else 0.
> ``` lang=cpp, name=Nada
> var OnlineTimePassed : Real


---  
 #  OnlineTimestamp : [real](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/real.markdown)

 `read-only`

> Timestamp indicating when this net object was brought online, else 0.
> ``` lang=cpp, name=Nada
> var OnlineTimestamp : Real


---  
 #  Role : [NetRole](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/enum_reference.markdown#netrole)

 `read-only`

> Returns our open peer's network role (client, server, offline), else Role::Unspecified.
> ``` lang=cpp, name=Nada
> var Role : NetRole


---  
 #  Methods


---  
 #  DispatchBroadcast : Void

> Dispatches the net event on the net object for all remote peers. In Offline mode, this calls DispatchLocal only.
> |Name|Type|Description|
> |---|---|---|
> |eventId|[string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> |event|[event](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/event.markdown)| |
> ``` lang=cpp, name=Nada
> function DispatchBroadcast(eventId : String, event : Event)
> ``` 


---  
 #  DispatchLocal : Void

> Dispatches the net event on the net object for the local peer.
> |Name|Type|Description|
> |---|---|---|
> |eventId|[string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> |event|[event](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/event.markdown)| |
> ``` lang=cpp, name=Nada
> function DispatchLocal(eventId : String, event : Event)
> ``` 


---  
 #  DispatchLocalAndBroadcast : Void

> Dispatches the net event on the net object for the local peer and for all remote peers. In Offline mode, this calls DispatchLocal only.
> |Name|Type|Description|
> |---|---|---|
> |eventId|[string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> |event|[event](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/event.markdown)| |
> ``` lang=cpp, name=Nada
> function DispatchLocalAndBroadcast(eventId : String, event : Event)
> ``` 


---  
 #  DispatchLocalAndRemote : Void

> Dispatches the net event on the net object for the local peer and for the remote peer. In Offline mode, this calls DispatchLocal only.
> |Name|Type|Description|
> |---|---|---|
> |eventId|[string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> |event|[event](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/event.markdown)| |
> |netPeerId|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function DispatchLocalAndRemote(eventId : String, event : Event, netPeerId : Integer)
> ``` 


---  
 #  DispatchRemote : Void

> Dispatches the net event on the net object for the remote peer. In Offline mode, this calls DispatchLocal only.
> |Name|Type|Description|
> |---|---|---|
> |eventId|[string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> |event|[event](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/event.markdown)| |
> |netPeerId|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function DispatchRemote(eventId : String, event : Event, netPeerId : Integer)
> ``` 


---  
 #  Forget : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> [Client] Forgets the online net object locally. [Server] Forgets the online net object locally and remotely for all relevant peers. Effectively removes the net object from the network system without destroying it. Returns true if successful, else false.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function Forget() : Boolean
> ``` 


---  
 #  GetNetChannel : [netchannel](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/netchannel.markdown)

> [Client/Server] Returns the specified net channel, else nullptr.
> |Name|Type|Description|
> |---|---|---|
> |netChannelName|[string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> ``` lang=cpp, name=Nada
> function GetNetChannel(netChannelName : String) : NetChannel
> ``` 


---  
 #  HasNetChannel : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> [Client/Server] Returns true if the net object has the specified net channel, else false.
> |Name|Type|Description|
> |---|---|---|
> |netChannelName|[string](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/string.markdown)| |
> ``` lang=cpp, name=Nada
> function HasNetChannel(netChannelName : String) : Boolean
> ``` 


---  
 #  IsOwnedByPeer : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Returns true if the net object is conceptually owned by a user added by the specified peer, else false.
> |Name|Type|Description|
> |---|---|---|
> |netPeerId|[integer](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/integer.markdown)| |
> ``` lang=cpp, name=Nada
> function IsOwnedByPeer(netPeerId : Integer) : Boolean
> ``` 


---  
 #  IsOwnedByUser : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> Returns true if the net object is conceptually owned by the specified user, else false.
> |Name|Type|Description|
> |---|---|---|
> |cog|[cog](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/cog.markdown)| |
> ``` lang=cpp, name=Nada
> function IsOwnedByUser(cog : Cog) : Boolean
> ``` 


---  
 #  NetObject : Void

 `constructor`

> Constructor.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function NetObject()
> ``` 


---  
 #  ReplicateNow : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> [Client/Server] Replicates all net channels' property changes immediately (only where changes are detected). Will also update nap state as configured. Returns true if changes were replicated, else false.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function ReplicateNow() : Boolean
> ``` 


---  
 #  SelectRemote : [boolean](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/nada_base_types/boolean.markdown)

> [Client/Server] Selects the remote net object on the first opposite-role peer found running in another game session instance on the engine. Will fail if the net object is not online, or not found remotely. Returns true if successful, else false.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function SelectRemote() : Boolean
> ``` 


---  
 #  SetNetUserOwnerDown : Void

> [Server/Offline] Sets the owning network user on this object and down the tree on all children recursively (pre-order traversal).
> |Name|Type|Description|
> |---|---|---|
> |cog|[cog](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/cog.markdown)| |
> ``` lang=cpp, name=Nada
> function SetNetUserOwnerDown(cog : Cog)
> ``` 


---  
 #  SetNetUserOwnerUp : Void

> [Server/Offline] Sets the owning network user on this object and up the tree on each parent recursively (pre-order traversal).
> |Name|Type|Description|
> |---|---|---|
> |cog|[cog](https://github.com/ZilchEngine/ZilchDocs/blob/master/code_reference/class_reference/cog.markdown)| |
> ``` lang=cpp, name=Nada
> function SetNetUserOwnerUp(cog : Cog)
> ``` 


---  
 #  TakeNap : Void

> Forces all net channels on this net object to start napping immediately.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function TakeNap()
> ``` 


---  
 #  WakeUp : Void

> Forces all net channels on this net object to stop napping immediately.
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Nada
> function WakeUp()
> ``` 


---  
 

 