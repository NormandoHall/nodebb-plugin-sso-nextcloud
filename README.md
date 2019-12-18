# NodeBB OAuth SSO NextCloud
### Forked and based on @julianlam code

NodeBB Plugin that allows users to login/register via any NextCloud OAuth2 provider.

## How to Adapt

* Go to your NextCloud and go to Settings - > Security, scroll down to OAuth 2.0 Clients.
* Add new client with a name **nextcloud** , and the callback URL, like this:
`https://NODEBB_URL/auth/nextcloud/callback`
* The copy the generated ID and SECRET
* Edit your NodeBB `config.json` file and add the ID/Secret pair:

```
  "oauth": {
    "id": "someoauthid",
    "secret": "youroauthsecret"
  },
```
* Change **NC_URL** with your NextCloud URL (lines 60, 61 and 65 of `library.js` of this plugin)
* Activate this plugin from the plugins page
* Restart your NodeBB
* Let NodeBB take care of the rest

## Trouble?

The NodeBB team builds out SSO plugins for a nominal fee. [Reach out to us for a quote.](mailto:sales@nodebb.org)

Find us on [the community forums](http://community.nodebb.org)!
