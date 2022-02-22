# Built with ColdFusion (CFML) & Ortus Products

This repo is a community repo to list and showcase companies, sites and technologies powered by ColdFusion (CFML) and several Ortus Products.

## Contributing

To contribute, fork and star the project.  Then add your own contributions to the `cfml-rocks.json` file according to our schema below. Send us your pull request and once validated, we will add it to the repo and site.

### Company Schema

```js
{
	"company"    : string, // Required
	"patreon"    : boolean, // Optional (false)
	"description": string, // Optional
	"companyURL" : URL, // Optional
	"sites"      : array of Site // Optional
}
```

### Site Schema

Each of the sites can have the following schema

```js
{
    "url" : URL, // required
    "adobe" : boolean // optional (false),
    "lucee" : boolean // optional (false),
    "coldbox" : boolean // optional (false),
    "contentbox" : boolean // optional (false),
    "quick" : boolean // optional (false),
    "cborm" : boolean // optional (false),
    "commandbox" : boolean // optional (false),
}
```

Ciao!  Thank you!
