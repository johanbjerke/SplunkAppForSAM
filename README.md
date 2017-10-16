# SplunkAppForSAM
version = 1.0
author = Johan Bjerke
description = Splunk App for Software Asset Management

Install this by either copying the whole folder into SPLUNK_HOME/etc/apps or by installing the file SplunkAppForSAM.spl through the Splunk UI. The app creates an index called "sam". The eventtypes in the app refer to this index (sam) and should be modified in order for it to work in a production environment.

The app requires the Add-on for Windows and the Add-on for Nix to be installed.
https://splunkbase.splunk.com/app/742/
https://splunkbase.splunk.com/app/833/

Reach out to me if you need help.

johan@splunk.com
