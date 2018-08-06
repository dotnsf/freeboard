# Free Board

## Overview

HTML5 Canvas free-hand drawing with mouse and touch.


## Pre-requisites

- [IBM Cloud](http://bluemix.net/) Account

    -  You can use **Lite Account**, free & non-paid account with limit.

- [cf cli tool](https://github.com/cloudfoundry/cli/releases) need to be installed.


## Setup for IBM Cloud

- Download or Clone this repository.

- Login to [IBM Cloud](http://bluemix.net/) and create Node.js runtime and IBM Cloudant service instance.

    - Assume you had created your Node.js runtime in US-SOUTH region.

- Bind Node.js and [IBM Cloudant](https://www.ibm.com/jp-ja/marketplace/database-management). Or you can edit settings.js with IBM Cloudant's username and password manually.

- Login to IBM Cloud with cf cli tool:

    - $ cf login -a https://api.ng.bluemix.net/ -u (your IBM ID)

- Push your freeboard code into your Node.js runtime application:

    - $ cf push (yourappname)


## Run

- Access to https://(yourappname).mybluemix.net/ with your browser or smartphone.


## Licensing

This code is licensed under MIT.

https://github.com/dotnsf/freeboard/blob/master/LICENSE


## Copyright

2018 K.Kimura @ Juge.Me all rights reserved.
