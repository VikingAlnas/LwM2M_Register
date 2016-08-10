<p>
	<img src="https://pbs.twimg.com/profile_images/461906120211062784/bJ84SApS.jpeg" width="50">
</p>
# How a SDO can register LwM2M Objects with OMA.

[Readme](/README.md) | [wiki](https://github.com/OpenMobileAlliance/LwM2M_Register/wiki) | View: [Objects ](https://openmobilealliance.github.io/OMNA/LwM2M/LwM2MRegistry.html#lwm2mregistry-table) / [Resources](https://openmobilealliance.github.io/OMNA/LwM2M/LwM2MRegistry.html#resources) | Register: [Objects](https://github.com/OpenMobileAlliance/LwM2M_Register/blob/master/Register_Other_SDO_Objects.md) [/ Resources](https://github.com/OpenMobileAlliance/LwM2M_Register/blob/master/Register_Reusable_Resources.md) | [Editor](http://devtoolkit.openmobilealliance.org/OEditor) | [API](https://github.com/OpenMobileAlliance/LwM2M_Register/blob/master/RESTful_API.md) | [Help](mailto:helpdesk@omaorg.org) 

This page should be used by Standard Development Organizations (SDO) that would like to submit new LwM2M Objects to the OMA Registry (OMNA). The steps to follow up are: 

* Create your LwM2M Object using the [LwM2M Editor Tool](http://devtoolkit.openmobilealliance.org/OEditor "Editor").
* Create a Pull Request which contains: <br/> ``` Copy, past and complete the following markdown table in your pull request ```

````
Field Name              | Your Input
:-----------------------| :----------------
Your Name:              |
Your DSO (Organization) |
Your email address      | 
Object Name             |
Objet File Name         |
Short Object Description|
```

* Attached the XML output of the [LwM2M Editor Tool](http://devtoolkit.openmobilealliance.org/OEditor "Editor"). <br/>
**Note**: ```At the time of submitting the Pull Request the xml portion that describes the Object will be validated. If the validation fails, you will not be able to submit your pull request. Make sure that your Object has been created with the``` [LwM2M Editor Tool](http://devtoolkit.openmobilealliance.org/OEditor "Editor").

* Upon successfull submission of your Object, OMNA (Open Mobile Name Authority) will: <br/> ```Please allow 3 weeks to process your request.```
  * Check if your Object has already been registered.
  * Allocate the ObjectID and update the URN field.
  * Let you know the outcome of your registration.

If you have any problem during the registration process, please submitt your comments via [Issues](https://github.com/OpenMobileAlliance/LwM2M_Register/issues), or send an email to our ```helpdesk @ omaorg.org```.
  
