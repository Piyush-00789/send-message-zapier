# Tellephant Zapier app

<br/>

## Overview
Zapier app is mostly based on the webhooks and APIs where "Tellephant Zapier App" communicate </br> "Tellephant" using APIs and webhooks.It **validates** the zapier user,**fetch the templates** and **sends<br/> the text template message using a webhook**.

<br/>

## How to setup?
* ES6 (functions and API call)
* Please see the documenation to understand better (https://platform.zapier.com/docs/zapier-intro)
* You will be required to add *trigger* and *action*  and those triggers and actions work from 
apis and<br/>  webhooks what developer will provide.
* Trigger defines that they are the initial resource which means if we are making trigger we are <br/> the starting point of any Zap.
* Action defines that they are the one who takes the data from trigger and **do something with it.**
 
<br/>

## Trigger and actions
* Zapier users need to authenticate themselves using the **Tellephant API key**.
* Create contact - This trigger will create WhatsApp contact in any app using WhatsApp name and <br/> phone number 
* 2 actions are there currently.
 <br/>i.Send Template Message
 <br/>Zapier would be giving us the values which *zapier user* will map to the template variables
    
    ii. Send Session Message
 <br/>Currently we would be taking as a phone number a text message from the *zapier user*


## Deployment
* We can test directly from the Zapier platform.
* Publishing required the app icon,homepage url,category and description of the app.
 