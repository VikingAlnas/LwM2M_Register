<p>
	<img src="https://pbs.twimg.com/profile_images/461906120211062784/bJ84SApS.jpeg" width="50">
</p>
### Re-usable Resource ID Assigned by OMNA

[Readme](/README.md) | [wiki](https://github.com/OpenMobileAlliance/LwM2M_Register/wiki) | [View Objects](https://github.com/OpenMobileAlliance/LwM2M_Register#objectid-classes) | [View Resources](/Reusable_Resources.md) | [Register](https://github.com/OpenMobileAlliance/LwM2M_Register#register) | [Editor](http://devtoolkit.openmobilealliance.org/OEditor) | [API](https://github.com/OpenMobileAlliance/LwM2M_Register/blob/master/RESTful_API.md) | [Help]()

This table contains the reusable Resources defined by Open Mobile Alliance, other SDO's, or private companies or individuals.  
```range: 2048 - 32,768)```

ResourceID  | Resource Name / DDF        | Owner / Technical Specs       | Description
:--------:  | :--------------------------| :--------------------------- | :------------------------------------------------:
4000        | ObjectInstanceHandle   | [IPSO Alliance]( "TS doc")            | ![alt Text](images/information.png "The object link is used to refer an Instance of a given Object. An Object link value is composed of two concatenated 16-bits unsigned integers following the Network Byte Order convention. The Most Significant Halfword is an ObjectID, the Least Significant Hafword is an ObjectInstance ID.An Object Link referencing no Object Instance will contain the concatenation of 2 MAX-ID values (null link).") 
4001       | ObjectVersion         | [IPSO Alliance]( "TS doc")               | ![alt Text](images/information.png "LWM2M Object versioning label.")
