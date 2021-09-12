---
title: "Webhooks (continued)"
date: 2021-09-12T14:54:58+07:00
draft: false
---

For example, say you run an online business and want to create an invoice each time a customer completes an order. You would need to first set up everything in your invoice app, and copy its webhook URL.
Then you can tell the originating app — your online store — the webhook URL of your invoice app.
Now whenever your online store receives an order, it will encode all the necessary data (your payload) and ping the webhook URL, sending the order details to your invoice app to create a new invoice.