# WPNinja24-DefenderSettings

As requested I have added the profiles presented to this Github Repository. 

Below you can once again find a summary of how you can streamline the deployment: 
## Android 
To streamline the deployment on Android you can deploy the following configs

### App Configuration 

Add the following permissions to your Defender App Config: 

* Post notifications (Auto grant)
* Location Access fine (Auto grant)
* Location Accesss coarse (Auto grant)

  To further streamline the deployment use an OEM Config App, if your OEM has one and check for functionalities like:
  * Removing an app from battery optimization
  * Granting All File Access and Appear on Top (Draw over other apps)
 
  I attached my Samsung OEM Config JSON file to the repository, feel free to import it by creating a OEM Config Policy for the Knox Service Plugin App.
  Scroll down and paste my JSON over yours.

  ## iOS

  For iOS I have created a Settings Catalog profile which combines the Control Filter profile and a profile to allow the Defender App to always send notifications.
  
