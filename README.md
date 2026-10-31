# shopping-helper-agent

Hosts the [UCP](https://ucp.dev) agent profile for `shopping-helper`, a personal tool that
compares prices across Portuguese online stores.

Shopify stores fetch `ucp-profile.json` to identify the tool when it calls their catalogue
search. The tool only searches catalogues; it does not use carts, checkout or orders.
