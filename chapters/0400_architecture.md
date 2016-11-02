Architecture
============


What is this data service look like? Which parts and tasks does it cover?


+   hard-connection backend and mobile device? (for continuously collection data e.g. 
    geo-location) --> internal aggregation;
    or soft-connection between them --> just exposing api to store certain types of arbitrary data,
    collected and stored/cached on external sources
    
+   automated backup mechanisms, e.g. distribute encrypted container, maybe on a regular basis,
    to dropbox (or the like) or git repository or maybe scp
    
+   2-factor auth? How?

+   an inclusion of a mobile device (as the actual data vault/container) could make using 
    2-factor-auth more obvious and easier to implement - we might get in for free depending on
    we model the interaction processes

+   data backup?

+   explicitly no ecosystem approach: no interoperability between each each individuals PDS,
    thus no market/appstore as business model

+   either cloud-based (not in the near of the user) and/or local (users device) storage
