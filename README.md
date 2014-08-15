bcc
===

Payment processing for the 2014 Bike Commute Challenge via Click&amp;Pledge FaaS API

This HTML form was created in order to process payment for BCC registration incentive packages, using the Click&Pledge FaaS API.

It contains PHP to insert values into the form that were sent via a RESTful service between the registration site, and the payment form.

A 256-bit SSL certificate is required to use Click&Pledge's FaaS API.


Known issues;
- No checkout preview
- No validation
- No dymanicly required fields
- No dynamic "deductible" amount on "Ride Your Way"
- Does not ask for residential or commercial address
