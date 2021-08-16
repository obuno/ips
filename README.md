# IPS Threat List

This is my personal Threat List/Block List.
This can be used as a Firewall deny rule upon matching selectors.

Be aware that this Threat List has been crafted according to personal criterias and the addon triggers of being part of that list are the followings:

- Any IPS triggering off premises source IP has been added.
- Any protocols violating visitors have been added (ex: attempting an RDP session on port TCP:443 etc..).
- Any visitors requesting a direct IP destination in conjunction with HTTP/HTTPS protocols has been added.
- Any Implicit Deny offending source IP has been added (ex: Denied GEO on services etc...).
- Any Cyber Deception offending source IP has been added (08.2021)

Hence the membership criterias of beeing part of this list are somewhat strict, so use it with care.
This list is updated once per hour in the occurence of any additions.

Obuno
