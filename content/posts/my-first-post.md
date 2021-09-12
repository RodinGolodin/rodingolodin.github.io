---
title: "My First Post"
date: 2021-09-12T13:17:58+07:00
draft: false
---

Webhooks are one of the ways applications can communicate with each other. They are a useful, resource-light way to implement event reactions, which means a specific action will be triggered when an event occurs.
Webhooks usually contain JSON payloads — your data — which is sent to a unique URL.

The URL acts like a phone number for the originating application to call the target application. When that call comes through, the two apps communicate what data should be sent, and the target application gets to work.

For example, say you run an online business and want to create an invoice each time a customer completes an order. You would need to first set up everything in your invoice app, and copy its webhook URL.
Then you can tell the originating app — your online store — the webhook URL of your invoice app.
Now whenever your online store receives an order, it will encode all the necessary data (your payload) and ping the webhook URL, sending the order details to your invoice app to create a new invoice.