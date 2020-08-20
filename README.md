# ergast-f1-openapi-doc
An OpenAPI Schema for the Ergast Formula 1 API

## About

This is a *partial* definition of the [Ergast F1 API](https://ergast.com/mrd/) in the OpenAPI 3.0 specification. Of the the endpoints that are implemented here, the url paths and return data schemas are structured to match the structure currently used on the live Ergast API.

You should be able to use the as a starting point for [generating your client libraries](https://github.com/OpenAPITools/openapi-generator) for use with Ergast, or setting up your own API to use with a copy of the Ergast DB.

Some notes:

- This only defines the JSON data schema, not the XML version of the API return data
- Outside of the year, most of the inline parameters used by the Ergast API are not defined here.
- The placeholder values for year are not currently implemented.