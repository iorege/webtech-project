# DaShop

Buy or buy super e-shop platform.

# Introduction

As e-platforms started overflowing on the internet, we try to create our own shape for an e-shop.

This example is intended for the fashion industry.

There are many solutions on the market.
examples :
-  https://www.zara.com/
-  https://www.fashiondays.ro/
-  https://www.hm.com/

Why? We practice our skills and also try to figure solutions for existing problems as user experience or performance.
Keeping things neat and smart.

# Interfaces

![alt text](https://github.com/iorege/webtech-project/blob/master/docu.png?raw=true)

# API REST

- GET /Categories
- GET /Categories/:ID/Products
- GET /Produts/?Search=
- POST /Orders
- PUT /Orders/:ID
- GET /Payment-Paypal
- POST /Checkout

# PayPal API 

You can find their documentation here : https://developer.paypal.com/docs/api/overview/#api-requests

Snap :

This sample request cancels a billing agreement:

curl -v -X POST https://api.sandbox.paypal.com/v1/payments/billing-agreements/I-1TJ3GAGG82Y9/cancel \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer Access-Token" \
  -d '{
  "note": "Canceling the profile."
}'
