# NodeBB OAuth SSO NextCloud
### Forked and based on @julianlam code

NodeBB Plugin that allows users to login/register via any NextCloud OAuth2 provider.

## How to Adapt

* Change **NC_URL** with your NextCloud URL (lines 60, 61 and 65 of `library.js`)
* Edit your NodeBB `config.json` file and add the ID/Secret pair:

```
  "oauth": {
    "id": "someoauthid",
    "secret": "youroauthsecret"
  },
```

* Activate this plugin from the plugins page
* Restart your NodeBB
* Let NodeBB take care of the rest

## Trouble?

The NodeBB team builds out SSO plugins for a nominal fee. [Reach out to us for a quote.](mailto:sales@nodebb.org)

Find us on [the community forums](http://community.nodebb.org)!
