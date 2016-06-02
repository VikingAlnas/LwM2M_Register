<p align="right">
	<img src="http://openmobilealliance.org/wp-content/uploads/2012/11/LOGO_OMA_Large.jpg" width="250">
</p>
[Readme](/README.md) | [wiki](https://github.com/OpenMobileAlliance/LwM2M_Register/wiki) | [OMA Objects](OMA_Objects.md) | [Other SDO Objects](/Other_SDO_Objects.md) | [Private Objects](/Private_Objects.md) | [Reusable Resources](/Reusable_Resources.md) | [Register](https://github.com/OpenMobileAlliance/LwM2M_Register#register) | [Editor](http://devtoolkit.openmobilealliance.org/OEditor)

## OMNA LwM2M Register
This Register is administrated by **Open Mobile Alliance Name Authority**, (OMNA) for the registration of LightweightM2M Objects and Resources.

### ObjectID Classes

The LightweightM2M Objects are registered according to the following ObjectsID classes:

Category          | Object ID Range      |Description 
:-----------------| :--------------------| :-----------------------------------------------------
[oma-label](/OMA_Objects.md)         | 0 – 1023             | Objects defined by the Open Mobile Alliance 
reserved I        | 1024 – 2047          | Reserved for future use 
[ext-label](/Other_SDO_Objects.md)         | 2048 – 10240         | Objects defined by a 3rd party SDO, Standard Development Organizations. 
[x-label](/Private_Objects.md)           | 10241 – 32768        | Objects defined by a vendor or individual such an object may be either private (no DDF or Specification made available) or public. These objects are optionally private, this is indicated at the time of submission. 

### ResourceID Classes

The LightweightM2M Resources are registered according to the following ResourcesID classes:

Category          | Resource ID Range      |Description 
:-----------------| :----------------------| :-----------------------------------------------------
No allocated      | 0 - 2047               | Resources defined by the Object specification
[Reusable](/Reusable_Resources.md)| 2048 - 32768           | Registered by an Object Specification, with the Resource ID assigned by OMNA. Defined in any Object specification. Resources from thisResource ID range can be re-used in any Object
Reserved          | 32769 -                | Range or Resource IDs reserved for future use

***

## Register
