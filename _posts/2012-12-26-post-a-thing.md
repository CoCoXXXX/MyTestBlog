---
category: dogLin
path: '/dogLin'
title: 'DogLin是傻子'
type: 'POST'

layout: nil
---

DogLin不能做个傻子

### Request

* The headers must include a **valid authentication token**.
* **The body can't be empty** and must include at least the name attribute, a `string` that will be used as the name of the thing.

```Authentication: bearer TOKEN```
```{
    name: 'My new thing'
}```

### Response

**If succeeds**, returns the created thing.

```Status: 201 Created```
```{
    id: new_thing,
    name: 'My new thing'
}```

For errors responses, see the [response status codes documentation](#response-status-codes).
