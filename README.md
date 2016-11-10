# siteapi_custom
This drupal module configure API key field and provide URL to get page node data in JSON format

# Usage

Install and enable module 'siteapikey' from module list (http://yourserver/drupalinstance/admin/modules).
Go to Site Information setting page and add your Site API Key value. (http://yourserver/drupalinstance/admin/config/system/site-information )
Access node data in JSON format using below URL

http://yourserver/drupalinstance/page_json/siteapikey/nodeid

Example - http://yourserver/drupalinstance/page_json/abckey/1