<p align="right">
	<img src="http://openmobilealliance.org/wp-content/uploads/2012/11/LOGO_OMA_Large.jpg" width="250">
</p>
## OMNA LwM2M Register
This Register is administrated by **Open Mobile Alliance Name Authority**, (OMNA) for the registration of LightweightM2M Objects and Resources.

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

## Register
