# Hangar Export for CHROME

## Download your RSI Pledge and Buyback data into JSON and CSV files

* Zero external libraries used.
* Vanilla Javascript.
* Simple code Easy to audit.
* Makes no calls to RSI directly from Javascript.
* Adds an Export button, but does not otherwise adjust the html of your hanger. future hanger changes will should not be impacted for example "Ship Naming".
* Includes all Pledge Data that can be found on each page
* Includes all Buyback Data that can be found on each page.
* Includes all Ships and Ship Names within each pledge.
* Does NOT include Coupon Codes themselves, but does include the pledge without the codes.
* Includes the handle.

**Always enbale Two Factor Authentication on your RSI account before using any chrome extensions.**

* Ensure this code is not compressed or zipped (unzip if required)
* Download and install chrome
* Double check you have 2FA enabled on your RSI account
* Type the following into the address bar: chrome://extensions
* Switch on developer mode (toggle on the right top called developer mode)
* Click the button Load unpacked
* Navigate to the folder containing the extracted code
* Open a new tab and browse to https://robertsspaceindustries.com/account/pledges
* Click the export button on the left hand sidebar menu
* Wait for chrome to work its way through your pledge and buybacks pages
* Allow chrome to download two files
* The CSV file can be loaded into spreadsheet software
* The JSON file can be further processed or uploaded to a location to be announced soon to assist with hanger management and ccu chain management.
