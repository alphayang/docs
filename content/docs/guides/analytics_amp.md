---
$title: Configure Analytics
$order: 1
$category: 2
---

## Decide before you start

All analytics solutions are built upon knowing what data you need,
and how you intend to analyze that data. Decide before you start:

* Will you use third-party analytics tools to analyze user engagement,
or your own in-house solution?
* What user behaviors will you measure to understand user engagement?

### Send data to vendor or self?

If you have your own in-house solution for measuring user engagement,
the only thing you will need to integrate AMP analytics with that solution is a URL.
This is where you will send the data.
You can also send data to various URLs.
For example, you can send page view data to one URL,
and social engagement data to another URL.

AMP analytics is specifically designed to measure once and report to many.
If you are already working with one or more analytics vendors,
check the
[amp-analytics specification](/docs/reference/extended/amp-analytics.html)
to see if they’ve integrated their solution with AMP.
If they have, simply link to their docs from the specification
and start following the instructions.

If the analytics vendor hasn’t integrated with AMP,
reach out to the vendor to ask for their support.
We also encourage you to [create an issue in the AMP project](https://github.com/ampproject/amphtml/issues/new)
requesting that the vendor be added.
See also
[Integrating your analytics tools in AMP HTML](https://github.com/ampproject/amphtml/blob/master/extensions/amp-analytics/integrating-analytics.md).

### What data do you need?

What data about your users will you capture in order to measure engagement?
You must identify this data before you can configure it.

Key data points to consider:

* Will you track only page views, or additional user engagement patterns
(see also [amp-pixel or amp-analytics](/docs/guides/analytics/analytics_basics.html#use-amp-pixel-or-amp-analytics))?
* What kinds of data will you capture about your users, your content,
the device or browser (see also [Variable substitution](/docs/guides/analytics/analytics_basics.html#variable-substitution))?
* How will you identify your users (see also [User identification](/docs/guides/analytics/analytics_basics.html#user-identification))?
