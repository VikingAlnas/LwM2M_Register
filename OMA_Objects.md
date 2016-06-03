## OMA Objects
<p>
	<img src="https://pbs.twimg.com/profile_images/461906120211062784/bJ84SApS.jpeg" width="50">
</p>
[Readme](/README.md) | [wiki](https://github.com/OpenMobileAlliance/LwM2M_Register/wiki) | [OMA Objects](OMA_Objects.md) | [Other SDO Objects](/Other_SDO_Objects.md) | [Private Objects](/Private_Objects.md) | [Reusable Resources](/Reusable_Resources.md) | [Register](https://github.com/OpenMobileAlliance/LwM2M_Register#register) | [Editor](http://devtoolkit.openmobilealliance.org/OEditor) | [API]() | [Help]()

This table contains the objects defined by Open Mobile Alliance as part of its specifications development. 

URN : ```urn:oma:lwm2m:oma:ObjectID``` | ```range (0 - 1,023)```

ObjectID  | Object Name                                  | Description
:--------:| :------------------------------------------- | :------------------------------------------------:
0         | [LWM2M Security](http://www.openmobilealliance.org/tech/profiles/LWM2M_Security-v1_0.xml "xml file") | ![alt Text](images/information.png "It provides the keying material of a LWM2M Client appropriate to access a specified LWM2M Server. One Object Instance SHOULD address a LWM2M Bootstrap Server. These LWM2M Object Resources MUST only be changed by a LWM2M Bootstrap Server or Bootstrap from Smartcardand MUST NOT be accessible by any other LWM2M Server.")
1         | [LWM2M Server](http://www.openmobilealliance.org/tech/profiles/LWM2M_Server-v1_0.xml "xml file") | ![alt Text](images/information.png "It provides the data related to a LWM2M Server. A Bootstrap Server has no such an Object Instance associated to it.")

***
