# alfresco-defaultquota-policy

Alfresco Default Quota Policy

Author: Jared Ottley (jared.ottley@alfresco.com)
Author: Salvatore De Paolis (sdepaolis@sinusia.org)
Date: 11/06/2015
Version: 0.3

Summary
This extension adds the ability to define and apply a default quota when a new user is created.

Alfresco's default quota is unlimited. This extension sets the default to 50 MB, unless a value 
is provided at user creation time, which then overrides the default.
It's also possible to override the value of the property defaultQuota from within the alfresco-global.properties
Possible values can be expressed in KB, MB, GB

In order to enable this addon, you have to make sure the usage control of Alfresco is enabled.
You can enable it including the property bellow into the alfresco-global.properties:

system.usages.enabled=true

Currently tested with 5.0.d