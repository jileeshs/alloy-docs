---
description: >-
  Learn how to get Adobe Experience Cloud Id. 
---

# Getting Experience Cloud Id

Adobe Experience Cloud uses a unique id for every consumer. If any customer wants to use this unique id they can use the `getEcid` command. 

```javascript
alloy("getEcid")
  .then(function(ecid) {
    // This function will get called with Adobe Experience Cloud Id when the command promise is resolved
  })
  .catch(function(error) {
    // The command failed.
    // "error" will be an error object with additional information
  })
```
