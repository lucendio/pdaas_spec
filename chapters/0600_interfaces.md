Interfaces
==========


How third parties can interact with such data sources?

+   when requesting time series data, which concepts should been supported:
    A)  collection data within the service and only after a period of time handing over the data
        (after filtering them)
    B)  providing some sort of real time feed through the service (filtering upfront)?
     
+   after introducing the system and because it is likely that vendors will support this way of
    exchanging/acquiring data only if its feasible and enough user are already using it. So to 
    increase adoption rate of users, it might be supportive to provide a browser extension to
    mimic the role of the vendor somehow (like *Personal* did before 
    [https://techcrunch.com/2011/11/17/personal-is-a-secure-vault-for-all-of-your-private-digital-data/]); 
    also it would be great to have some client-plugins for several platforms, languages and 
    frameworks right from the start (e.g. nodejs, shopify, rails, wordpress etc.)
    
+   spam protection? if we have a general URI (endpoint) for incoming requests, which had to 
    get submitted upfront, that identifier (URI) might get known commonly, thus unintended mass
    requests might occur. possible solution: generate URI+token (token = cert fingerprint?) 
    within the software? (how do we get it from there to the third-party?) OR let the user 
    create a human readable slug on the fly during the external interaction - therefor on the
    mobile notification we have at least sth to validate, but with no tech. assistance, and
    it is still not spam-safe? 
