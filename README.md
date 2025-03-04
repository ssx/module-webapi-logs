# Description

This module allows you to log and analyze all webapi REST calls to your Magento/Adobe Commerce store.

It was forked from [ghostunicorns/module-webapi-logs](https://github.com/ghostunicorns/module-webapi-logs).

# Install

`composer require ssx/module-webapi-logs`

# Configure

1. Log-in your Magento backend

2. Go to `Stores > Configuration > System > Webapi Logs` and enable it
<img src="https://github.com/ssx/module-webapi-logs/blob/main/screenshots/screen1.png" />

# Use

Go to `Reports > Webapi Logs > Show Logs`
<img src="https://github.com/ssx/module-webapi-logs/blob/main/screenshots/screen2.png" />

You can select an entry to see more details about the request and the response
<img src="https://github.com/ssx/module-webapi-logs/blob/main/screenshots/screen3.png" />

# Attention!
If you disable the Secret Mode this module will log everything passes in the webapi calls (tokens and passwords too!), 
then remember to clean logs by clicking the `Delete All Logs` button:

<img src="https://github.com/ssx/module-webapi-logs/blob/main/screenshots/screen4.png" />

# Contribution
Yes, of course you can contribute sending a pull request to propose improvements and fixes.

