# status-page-components-test

This repo's [issue tracker](https://github.com/handpoint/status-page-components-test/issues) is used to track the status of the components of the [status page](https://github.com/handpoint/status-page) in staging.

## Description

The status page is a SPA that shows the status of the components that make up the Handpoint system. The status page is available at [https://status.handpoint.io](https://status.handpoint.io).

## Manually updating the status page components

We use Github issues to track the status of our services. Each issue represents a service or an incident. Services are labeled as `component` and the incidents are labeled as `incident`. The status page uses the Github API to fetch the issues and display them on the status page.

The status of the components can be manually updated for example when there is a bug in the backend and the service status is not
in sync with the actual status of the service. In that case you can go to [Issues](https://github.com/handpoint/status-page-components-test/issues) and update the label of the issue to reflect the status (remove the old label and add the new label).

Supported labels are:

- `operational` - The service is up and running
- `partial outage` - The service is up but some functionality is not working
- `major outage` - The service is down