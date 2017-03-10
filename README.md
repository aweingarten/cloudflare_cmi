#CloudFlare CMI
Drupal Module for importing and exporting CloudFlare config like so:
````
CloudFlare Api -> Drupal -> CMI -> Drupal -> CloudFlare API
````

This tool would allow us to develop cloudflare config, version control it, stage it, and deploy it using automated tools.  It will also let us create baseline configs and deploy them.   

## Dependencies
- [CloudFlare Module](https://www.drupal.org/project/cloudflare) Provides API credentials and rate limit checking in Drupal.
- [CloudFlare Php SDK](https://github.com/d8-contrib-modules/cloudflarephpsdk) Contains all API calls abstracted away from Drupal. 

