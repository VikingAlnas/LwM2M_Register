<p align="right">
	<img src="http://openmobilealliance.org/wp-content/uploads/2012/11/LOGO_OMA_Large.jpg" width="250">
</p>
## OMNA LwM2M Register
This Register is administrated by **Open Mobile Alliance Name Authority** for the registration of LightweightM2M Objects and Resources.

### ObjectID Classes

The LightweightM2M Objects are registered according to the following ObjectsID classes:

Category          | Object ID Range      |Description 
:-----------------| :--------------------| :-----------------------------------------------------
[oma-label](#oma-label)         | 0 – 1023             | Objects defined by the Open Mobile Alliance 
reserved I        | 1024 – 2047          | Reserved for future use 
[ext-label](#ext-label---objects-produced-by-3rd-party-sdos)         | 2048 – 10240         | Objects defined by a 3rd party SDO, Standard Development Organizations. 
[x-label](#x-label---objects-defined-by-vendors-or-individuals)           | 10241 – 32768        | Objects defined by a vendor or individual such an object may be either private (no DDF or Specification made available) or public. These objects are optionally private, this is indicated at the time of submission. 

### ResourceID Classes

The LightweightM2M Resources are registered according to the following ResourcesID classes:

Category          | Resource ID Range      |Description 
:-----------------| :----------------------| :-----------------------------------------------------
No allocated      | 0 - 2047               | Resources defined by the Object specification
[Reusable](#re-usable-resource-id-assigned-by-omna)| 2048 - 32768           | Registered by an Object Specification, with the Resource ID assigned by OMNA. Defined in any Object specification. Resources from thisResource ID range can be re-used in any Object
Reserved          | 32769 -                | Range or Resource IDs reserved for future use

***
***
## oma-label
[LightWeightM2M v1.0 Specifications](http://member.openmobilealliance.org/ftp/public_documents/dm/LightweightM2M/)

URN : ```urn:oma:lwm2m:oma:ObjectID```

ObjectID  | Object Name                                  | Description
:--------:| :------------------------------------------- | :------------------------------------------------:
0         | [LWM2M Security](http://www.openmobilealliance.org/tech/profiles/LWM2M_Security-v1_0.xml "xml file") | ![alt Text](images/information.png "It provides the keying material of a LWM2M Client appropriate to access a specified LWM2M Server. One Object Instance SHOULD address a LWM2M Bootstrap Server. These LWM2M Object Resources MUST only be changed by a LWM2M Bootstrap Server or Bootstrap from Smartcardand MUST NOT be accessible by any other LWM2M Server.")
1         | [LWM2M Server](http://www.openmobilealliance.org/tech/profiles/LWM2M_Server-v1_0.xml "xml file") | ![alt Text](images/information.png "It provides the data related to a LWM2M Server. A Bootstrap Server has no such an Object Instance associated to it.")

***

###Ext label - Objects Produced by 3rd Party SDOs
URN : ```urn:oma:lwm2m:ext:ObjectID```

ObjectID  | Object Name                             | Owner /Technical Specs                 | Description
:--------:| :---------------------------------------| :------------------------------------- | :----------------------:
2048      | [CmdhPolicy]( "xml file")               | [OneM2M](http://www.onem2m.org/images/files/deliverables/TS-0005-Management_Enablement_(OMA)-V1_0_1.pdf "TS doc") | ![alt Text](images/information.png " ")
2049      | [ActiveCmdhPolicy]( "xml file")         |                                                 [OneM2M](http://www.onem2m.org/images/files/deliverables/TS-0005-Management_Enablement_(OMA)-V1_0_1.pdf "TS doc") | ![alt Text](images/information.png " ")

***

### x-label - Objects Defined by Vendors or Individuals

URN : ```urn:oma:lwm2m:x:ObjectID```

ObjectID  | Object Name                         | Company / TS           | Description
:---------| :-----------------------------------| :----------------------| :-----------------------------------------:
10241     | HostDeviceInfo                      | AT&T                   |  ![alt Text](images/information.png "This LWM2M Object provides a range of host device related information which can be queried by the LWM2M Server. The host device is any integrated device with an embedded cellular radio module")
10242     | [3-PhasePM](http://technical.openmobilealliance.org/tech/profiles/3-PhasePM.xml "xml file")                           | Odins                  | ![alt Text](images/information.png "This Object provides the information to represent a generic 3-Phase Power Meter")

***
***

### Re-usable Resource ID Assigned by OMNA

ResourceID  | Resource Name / DDF        | Owner / Technical Specs       | Description
:--------:  | :--------------------------| :--------------------------- | :------------------------------------------------:
4000        | [ObjectInstanceHandle]( "xml file")   | [IPSO Alliance]( "TS doc")            | ![alt Text](images/information.png "The object link is used to refer an Instance of a given Object. An Object link value is composed of two concatenated 16-bits unsigned integers following the Network Byte Order convention. The Most Significant Halfword is an ObjectID, the Least Significant Hafword is an ObjectInstance ID.An Object Link referencing no Object Instance will contain the concatenation of 2 MAX-ID values (null link).") 
4001        | [ObjectVersion]( "xml file")          | [IPSO Alliance]( "TS doc")               | ![alt Text](images/information.png "LWM2M Object versioning label.")
