---
title: API Analytics Architecture - API Manager Documentation 4.0.0
---

# API Analytics Architecture

The following diagram illustrates the basic architecture of the Analytics solution.

<a href="{{base_path}}/assets/img/analytics/apim-analytics-simplified.jpg"><img src="{{base_path}}/assets/img/analytics/apim-analytics-simplified.jpg" width="70%" alt="APIM Analytics Simplified Design"></a>

As depicted above, the Gateways will publish analytics statistics directly to the Analytics Cloud over the internet. The Analytics Cloud will have regional deployments to reduce publishing latencies and honor data privacy. The Analytics Portal is deployed as a separate web application that will query the query API to visualize API statistics.