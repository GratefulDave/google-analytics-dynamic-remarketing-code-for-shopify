# google-analytics-shopify-remarketing-code
Google Analytics Shopify Remarketing Code

For account set-up follow the directions here: https://support.google.com/analytics/answer/2444872?hl=en.

You will have to set up a Google Merchant Account 

To add retail audiences you can use the link on this page: https://support.google.com/analytics/answer/3457161?hl=en

Please note: When I had Google automatically import the Retail audiences for some reason the wrong variables were passed to my account. The variables should be:
  
  Custom Dimension 1: ecomm_prodid
  
  Custom Dimension 2: ecomm_pagetype
  
  Custom Dimension 3: ecomm_totalvalue
  
The two errors I encountered were as follows:

  Custom Dimensions 2 & 3 were reversed meaning that the wrong variables would have been passed to the wrong dimensions. 
  
  The dimensions were formatted improperly ecomme_totalvalue appeared as ecomm_totalValue and the other variables had the same capitalization error.
  
