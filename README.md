# snapshot-images

## Introduction
The JSON templates in this repository are pre-configured for modern day web applications and API servivces. 

These templates are useful when building new applications as they include optimized components and settings to allow for a smooth out-of-box experience. 

## Introduction
#Barracuda WAF-a-a-Service Portal (or API)
1. Deploy a new application using the admin portal or API call
2. Add the Snapshots component

#Prepare your Snapshot
1. Download the applicable JSON file specific to your deployment.
2. Open the JSON file and navigate to "Domains" key and modify the value to reflect the HOSTNAME of your application.
3. Navigate to the "Servers" key and modify the value to your ORIGIN server IP or hostname.
4. Save the JSON File

#Barracuda WAF-a-a-Service Portal (or API)
1. Navigate to the Snapshots component for your application
2. Click the Import button
3. Delete/Overwrite the existing configuration and Save.

#Verify/Change
1. Endpoints - Deployment Location - Please set this to the applicable locations Primary/Backup
2. Modify any additional options like Dedicated IP per your app discretion.
3. Test
4. Done!
