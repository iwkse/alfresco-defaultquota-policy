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
~~It's also possible to override the value from within the alfresco-global.properties
Possible values can be expressed in KB, MB, GB~~

The default value is set in a context file and must be defined in bytes.

Currently tested with 5.0.d
