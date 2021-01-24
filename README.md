# IPS Threat List

This is my personal Threat List/Block List.
This can be used as a Firewall deny rule upon matching selectors.

Be aware that this Threat List has been crafted according to personal criterias and the addon triggers of that list are the followings:

- Any IPS triggering off premises IP has been added.
- Any Web Services visitor that requested a direcet IP address as its destination within the HTTP/HTTPS protocols has been added.
- Any Application Control violating visitor has been added (ex: initiating an RDP session on port TCP:443 etc..)
- Any Implicit Deny offending inbound IP has been added (Denied GEO on services etc...)

Hence the membership criterias of beeing part of this list are pretty harsh, so use it with care.
This list is updated once per hour in the occurence of any additions.

Cheers,
Obuno
