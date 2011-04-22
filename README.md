A basic HipChat publisher for CruiseControl.NET.

Thanks to [alexscordellis](https://github.com/alexscordellis/) and his [ccnet.campfire.plugin](https://github.com/alexscordellis/ccnet.campfire.plugin) project which I used to figure out how to create a CruiseControl.NET publisher.

How to install
==============

Once compiled, copy ccnet.hipchat.plugin.dll to C:\Program Files (x86)\CruiseControl.NET\server, or to where CruiseControl.NET is installed if not the default path.

Add the following to your ccnet.config publishers block:

```xml
<hipchat
	https="true or false"
	room-id="integer room id or string room name"
	from="who the message is from, usually Robot Llama"
	auth-token="your auth token"
/>

```
