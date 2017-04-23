# google-analytics-shopify-remarketing-code
Google Analytics Shopify Remarketing Code

First, you will have to enable Google Analytics in Online Store->Preferences by pasting your tracking code & enabling enhanced e-commerce.

Second, for account set-up follow the directions here: https://support.google.com/analytics/answer/2444872?hl=en.

Third, you will have to set up a Google Merchant Account & can use Shopify's Google Shopping App. If you are dropshipping and your item does not have a GTIN ot product identifier there is a checkbox you can mark to indicate the products do not have product identifiers. If you do not do this your feed will have errors and not work.

To add retail audiences you can use the link on this page: https://support.google.com/analytics/answer/3457161?hl=en

Please note: When I had Google automatically import the Retail audiences for some reason the wrong variables were passed to my account. The variables should be:
  
  Custom Dimension 1: ecomm_prodid
  
  Custom Dimension 2: ecomm_pagetype
  
  Custom Dimension 3: ecomm_totalvalue
  
The two errors I encountered were as follows:

  Custom Dimensions 2 & 3 were reversed meaning that the wrong variables would have been passed to the wrong dimensions. 
  
  The dimensions were formatted improperly ecomm_totalvalue appeared as ecomm_totalValue and the other variables had the same capitalization error. The variables much match the code.
  
