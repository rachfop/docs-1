---
title: Introduction to the dashboard
--- 

import useBaseUrl from '@docusaurus/useBaseUrl';

Plausible Analytics is built with simplicity and speed in mind. There is no navigational menu. There are no additional sub-menus. There is no need to create custom reports. You get one simple and useful web analytics dashboard out of the box.

Rather than tracking every metric imaginable, many of them that you will never find a use for, Plausible Analytics focuses on the essential website stats only. It's easy to use and understand with no training or prior experience.

Here’s what you can discover on your Plausible dashboard. You can also explore our [live demo](https://plausible.io/plausible.io) where you can see the actual traffic of our website.

## Top Graph

<img alt="Top Graph" src={useBaseUrl('img/top-graph.png')} />

See the number of unique visitors, total page views, the bounce rate (the percentage of sessions that had one page view only) and the visit duration. These metrics include a percentage comparison to the previous time period, so you understand if the trends are going up or down. You can click on a particular metric to display it in the top graph.

Choose the time range that you want to analyze in the date picker in the top right. The visitor numbers are automatically presented on an hourly, daily, or monthly graph. The default time frame is set at the last 30 days.

By clicking on the number of "**current visitors**" (defined as those that visited the site in the last 5 minutes) or by selecting "**Realtime**" in the date picker in the top right, you can see the realtime dashboard that tells you what's happening on your site live in that moment. 

The realtime dashboard also includes a pageview graph for the last 30 minutes. It's updated every 30 seconds so you don’t have to refresh it to stay up to date.

:::note
Click on your site name in the top left side of your dashboard. It allows you to select "[Site Settings](website-settings.md)" in the dropdown menu but also switch to a different site you have added to your Plausible account.
:::

We get all the favicons (your site favicon and the favicons of all the referral sources) directly from the DuckDuckGo API. We display the same icon that DuckDuckGo shows in their search results.

## Filtering

You can go granular and click on any of the metrics in your Plausible dashboard to filter the dashboard by it. You can mix and match filters too. This is an easy way for you to segment your audience. For instance you can drill down to see traffic coming from a specific marketing campaign to a specific landing page over time.

You can also use the "**Filter**" button on the top of your dashboard which gives you extra functionality such as the ability to search for any metric, exclude segments of your audience and group pages. [Learn more about filtering here](filters-segments.md).

## Top Sources

<img alt="Top Sources" src={useBaseUrl('img/top-sources.png')} />

See all the top referral sources of traffic ranked by the number of unique visitors. You can click on the "**details**" button to see the full list which also includes the "**Direct/None**" traffic. Additional metrics such as bounce rates and visit duration of the individual referral are included too.
 
You can click into the "**Campaign**" tabs of the Top Sources report to see your campaigns isolated from other traffic sources. These are visitors coming from UTM tagged links such as those in your emails, social media or in your paid advertising campaigns. Click on "**Medium**", "**Source**", "**Campaign**", "**Term**" and "**Content**" to explore these. You can learn more about [link tagging here](manual-link-tagging.md).

Note that the referral sources including UTM and other query parameters are counted only when they start a new session on your site.

## Top Pages

<img alt="Top Pages" src={useBaseUrl('img/top-pages.png')} />

See all the most visited pages on your site ranked by the number of unique visitors. You can click on the "**details**" button to see the full list with additional metrics. The number of pageviews, bounce rate, and time on page for the individual pages are included too.

You can also get insights into the visitor flow by looking at the "**Entry pages**" and "**Exit pages**". Click on the "**details**" button to see the full list with additional metrics. For "**Entry pages**" details include visit duration for visits that started on a specific page and for "**Exit pages**" details include the exit rate percentage.

:::note
Looking for the definitions of the metrics you have access to? [See this list](metrics-definitions.md).
:::

## Locations

<img alt="Countries" src={useBaseUrl('img/countries.png')} />

See the list of countries, regions and cities your traffic is coming from. You can click on the "**details**" button to see the full list ranked by the number of visitors.

:::note
Want a quicker way to navigate the dashboard? You can use the keyboard shortcuts to do so. Here's [the full list of shortcuts we support](keyboard-shortcuts.md).
:::

## Devices

<img alt="Devices" src={useBaseUrl('img/devices-size.png')} />

You can see the device, browser and operating system your visitors are using. Click on the individual browser or operating system to drill down and see browser versions and OS versions too.

## Goal Conversions

<img alt="Goal Conversions" src={useBaseUrl('img/dashboard-goal-conversions.png')} />

Track events and goals to identify the number of unique converted visitors, the total number of conversions, the conversion rate, and the referral sites that send the traffic that converts the best. We have a very flexible support for goals which allows you to create your own metrics to collect and analyze data that Plausible doesn’t automatically track. We also have an automated way to track 404 error pages, external link clicks and file downloads. [Read more here](goal-conversions.md).
