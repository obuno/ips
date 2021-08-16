# IPS Threat List

This is my personal Threat List/Block List.
This can be used as a Firewall deny rule upon matching selectors.

Be aware that this Threat List has been crafted according to personal criterias and the addon triggers of being part of that list are the followings:

- Any IPS triggering off premises IP has been added.
- Any protocols violating visitors have been added (ex: initiating an RDP session on port TCP:443 etc..).
- Any Web Services visitor requesting a direct IP as its destination in conjunction with HTTP/HTTPS protocols has been added.
- Any Implicit Deny offending inbound IP has been added (ex: Denied GEO on services etc...).
- Cyber Deception source IP of events tagged as either medium/high/crtical have been added (08.2021)

Hence the membership criterias of beeing part of this list are somewhat strict, so use it with care.
This list is updated once per hour in the occurence of any additions.

Obuno
