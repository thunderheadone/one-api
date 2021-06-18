# Thunderhead ONE OpenAPI Specification
[![Build Status](https://travis-ci.com/thunderheadone/one-api.svg?branch=master)](https://travis-ci.com/thunderheadone/one-api)

## Links

- Documentation(ReDoc): https://thunderheadone.github.io/one-api/
- SwaggerUI: https://thunderheadone.github.io/one-api/swagger-ui/
- Look full spec:
    + JSON https://thunderheadone.github.io/one-api/swagger.json
    + YAML https://thunderheadone.github.io/one-api/swagger.yaml
- Preview spec version for branch `[branch]`: https://thunderheadone.github.io/one-api/preview/[branch]

**Warning:** All above links are updated only after Travis CI finishes deployment

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and `cd`
    + Run `npm install`

### Usage

1. Run `npm start`
2. Checkout console output to see where local server is started. You can use all [links](#links) (except `preview`) by replacing https://thunderheadone.github.io/one-api/ with url from the message: `Server started <url>`
3. Make changes using your favorite editor or `swagger-editor` (look for URL in console output)
4. All changes are immediately propagated to your local server, moreover all documentation pages will be automagically refreshed in a browser after each change
**TIP:** you can open `swagger-editor`, documentation and `swagger-ui` in parallel
5. Once you finish with the changes you can run tests using: `npm test`
6. Share your changes with the rest of the world by pushing to GitHub :smile:

## Questions or need help

_The Thunderhead ONE team is available 24/7 to answer any questions you have. Just email onesupport@thunderhead.com or visit our docs page for more detailed installation and usage information._
