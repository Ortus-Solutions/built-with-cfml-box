# Built with ColdFusion (CFML) & Ortus Products

![Built With CFML & Ortus](https://github.com/Ortus-Solutions/built-with-cfml-box/blob/master/images/built-with-cfml-ortus-square-small.png?raw=true)

This repo is a community repo to list and showcase companies, sites and technologies powered by ColdFusion (CFML) and several Ortus Products.

## Contributing

To contribute, fork and star the project.  Then add your own organization file in the `orgs` directory and then append the name of that file ( excluding the extension ), in to the `cfml-rocks.json` array of orgs. You may use the schema below for reference. Send us your pull request and once validated, we will add it to the repo and site.

### Organization/Company Schema - Add in the `orgs` directory

```js
{
    "version" : "0.0.1",
    "orgs" : [
        "ortussolutions",
	"myorg"
    ]
}
```

Then your organization can look like this: `orgs/myorg.json`

```js
{
	"name"       : string, // Required
	"patreon"    : boolean, // Optional (false)
	"description": string, // Optional
	"url"        : URL, // Optional
    	"logo"       : URL, // Optional
	"sites"      : array of Sites // Optional
}
```

### Site Schema

Each of the sites can have the following schema

```js
{
    "title" : string, //required
    "url" : URL, // required
    "logo" : URL, // optional
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
