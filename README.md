# Experience Cloud Donation Flows for NPSP

## Description

This repository contains Flow templates to help you get started with building digital payment experiences using Experience Cloud and FinDock Payment Experiences. The three flows included are designed for Salesforce orgs with [Nonprofit Success Pack](https://help.salesforce.com/s/articleView?id=sfdo.nonprofit_success_pack.htm&type=5) (NPSP):

* **One\_Screen\_Dontation\_Flow**: Screen flow with a single donation step
* **Contact\_Assignment**: helper Flow for the single screen donation flow
* **Multi\_Screen\_Donation\_Flow**: Screen flow with two donation steps

These templates are meant to be customized and extended to fit specific use cases and requirements. For other options, see [Templates for FinDock Payment Experiences](https://github.com/FinDockLabs/experience-cloud-templates). 

**Key features**

* Collect one-time and recurring donations  
* Supports multiple currencies

## Prerequisites

* FinDock is installed and configured.  
* FinDock for NPSP is installed and configured.  
* At least one payment extension is installed and configured.  
* Digital Experiences is enabled in the org.

## Installation

8. Press the button below to deploy the templates to your org.  
9. Follow [these instructions](https://help.salesforce.com/s/articleView?id=experience.rss_flow_guestuser.htm&type=5) to set up guest user access for the flows.  
10. Open the single or multi-screen flow in your Flow editor and configure [payment method selection](https://docs.findock.com/docs/july-26/payments/payment-method-selector).  
11. Configure the [payment intent](https://docs.findock.com/docs/july-26/payments/pay-button) (add at least a success and failure URLs and verify the mapping matches your use case).  
12. Activate your flow.  
13. Go to the Experience Cloud Administration \-\> Preferences and enable "Allow guest users to access public APIs.”  
14. Add the flow to your Experience Cloud site.

## Deploy
[![Deploy to Salesforce](https://app.jdeploy.cloud/images/flat.svg)](https://app.jdeploy.cloud/github/FinDockLabs/experience-cloud-flow-templates-npsp/main)
