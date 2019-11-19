# NodeBB OAuth SSO NextCloud
### Forked and based on @julianlam code

NodeBB Plugin that allows users to login/register via any NextCloud OAuth provider.

## How to Adapt

1. Change **NC_URL** with your NextCloud URL (lines 60, 61 and 65 of `library.js`)
1. Edit your NodeBB **config.json** file and add the ID/Secret pair:

...
  "oauth": {
    "id": "someoauthid",
    "secret": "youroauthsecret"
  }
...

1. Activate this plugin from the plugins page
1. Restart your NodeBB
1. Let NodeBB take care of the rest

## Trouble?

The NodeBB team builds out SSO plugins for a nominal fee. [Reach out to us for a quote.](mailto:sales@nodebb.org)

Find us on [the community forums](http://community.nodebb.org)!
