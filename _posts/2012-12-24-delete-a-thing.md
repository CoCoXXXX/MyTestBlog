---
category: dogLin
path: '/dogLin/:id'
title: 'dogLin加油'
type: 'DELETE'

layout: nil
---

DogLin加油，你一定可以学会Unity！

### Request

* **`:id`** is the id the thing to delete.
* The headers must include a **valid authentication token**.
* **The body is omitted**.

### Response

Sends back a collection of things.

```Status: 200 Deleted```
```{
    code: 200,
    message: 'Your thing (id: 736) was deleted'
}```

For errors responses, see the [response status codes documentation](#response-status-codes).