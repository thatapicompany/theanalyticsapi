# TheAnalyticsApi
Node / NPM client library for TheAnalyticsAPI.com

Easy to integrate Analytics, 

- Easily track events from your Node application
- Download the Aggregate totals & Insights
- Have the results pushed into your Datalake or anywhere else via Zapier or Slack with Webhooks

Currently in closed Alpha.

# Track an Event from your App

Basic example:
```javascript
const Analytics = require('@thatapicompany/theanalyticsapi');

const client = new Analytics('writeApiKey');

client.track({
  event: 'Signup'
});
```
n.b. Timestamp would be automatically added on the server.

# For early access contact

Aden@ThatApiCompany.com