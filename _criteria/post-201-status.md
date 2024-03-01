---
title: 'POST 201 Status'
image: /images/post-201-status.png
tags:
- Responses
- Status Codes
- POST
---
<p><img src="{{ page.image }}" width="35%" align="left" style="padding: 15px;"></p>
When you provide a successful response for your POST operations, we recommend returning a 201 HTTP status code. 201 signals that your resource has been created, following well known RESTful approaches to using POST to create resources.

We also recommend you return a payload with your 201 responses, at a minimum return the unique identifier for the resource that was create, or also returning the full detail of the newly created API resources.