# API for Skygraph communities

Preview communities: https://skygraph.art

## Before using this API
For collaboration, contact @witch.monster. Ethical, non-commercial projects only.

### API Version 3.0
https://v3.api.skygraph.art/version.json

### All communities:
https://v3.api.skygraph.art/communities.json

### Community to dids:
https://v3.api.skygraph.art/community/[`community`].json

Example: https://v3.api.skygraph.art/community/c10.json

### Did to Community:

Finding user did `did:plc:z72i7hdynmk6r22z27h6tvur` (bsky.app):

1) search by 3-symbol prefix after `did:plc:` (in the case above: `z72`) using the following endpoint:
https://v3.api.skygraph.art/user/did_plc_prefixes.json

2) if prefix `z72` is found, search for specific did using the following endpoint:
https://v3.api.skygraph.art/user/byDidPlcPrefix/did_plc_z72.json