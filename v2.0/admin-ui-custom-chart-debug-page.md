---
title: Custom Chart Debug Page
toc: false
---

<span class="version-tag">New in v2.0:</span> The **Custom Chart** debug page of the Admin UI can be used to create a custom dashboard choosing from over 200 available metrics.

<div id="toc"></div>

## Overview

The definition of the customized dashboard is encoded in the URL.  To share the dashboard with a colleague, send them the the URL.  And just like any other URL it can be bookmarked, sit in a pinned tab on your browser, etc.

To view the **Custom Chart** debug page:

- In the **UI Debugging** section at the bottom of the node's Admin UI debug page, click on **Custom Time-Series Chart** .  For a locally running node this page will be at <http://localhost:8888/#/debug>.
- In your browser, go directly to <http://localhost:8888/#/debug/chart>.

## Query Options

The options table below the time series graph shows which metrics are being queried, and how they'll be displayed.  Options include:

{% include {{page.version.version}}/admin-ui-custom-chart-debug-page-00.html %}

## Examples

### Query User and System CPU Usage

