=== Time-based Revision Cleanup ===

Donate link: https://www.paypal.com/donate/?hosted_button_id=EUHE8NXYEXJJ6  
Contributors: michaelsablone  
Tags: revisions, cleanup, optimize, performance, history  
Requires at least: 4.9  
Tested up to: 6.4.3  
Requires PHP: 7.4  
Stable tag: 1.0.11  
License: GPLv2 or later  
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Maximize WordPress efficiency with Time-based Revision Cleanup: manage post histories by age, not count, with optional auto-cleanups.

== Description ==

Optimize your website's performance and streamline your editing workflow with the Time-based Revision Cleanup plugin for WordPress. Our plugin offers a sophisticated solution to the limitations of the default number-based revision system, which can quickly become inadequate for active sites. Instead of restricting revisions to a set count, our plugin allows you to specify a timeframe for keeping revisions, such as 30, 60, or 365 days, ensuring that your database retains only what's necessary without losing the essential edit history of your posts.

In addition, our plugin enhances the admin dashboard with an analytics feature that relies on Google's Chart API to generate visual representations of revision history data.

Please note: The dashboard analytics feature of this plugin relies on a third-party service (Google's Chart API). For more information about this service, please visit the [Google Chart Tools](https://developers.google.com/chart/) documentation. You can review the terms of service [here](https://developers.google.com/chart/terms).

### Key Features:

- **Intelligent Age-Based Management**: Preserve your site's history by automatically deleting revisions past a certain age, keeping only the recent and relevant changes.
- **Seamless On-Save Cleanup**: The plugin intuitively removes outdated revisions upon saving posts, based on the age criteria you've set, without disrupting the creative process.
- **Optional Automated Cleanup**: Enable the optional CRON job to perform regular, site-wide revision cleanups at intervals you control, maintaining optimal database health with no manual effort.
- **Dashboard Analytics**: Visualize your site's revision cleanup activity with an integrated chart, powered by Google's Chart API.
- **Fully Customizable**: Configure the plugin's settings to fit the unique demands of your site, including save timeout, CRON frequency, and the maximum number of revisions to process.

By focusing on time rather than revision count, our plugin addresses the core flaw in the default system, ensuring that a busy day of editing won't result in the loss of important historical data. With the optional CRON job for hands-free maintenance, adjustable settings for precision control, and insightful analytics, the Time-based Revision Cleanup plugin is an essential tool for maintaining a healthy, efficient WordPress site.

== Screenshots ==

1. The Stats tab showing you 24 hours / 30 days / 60 days / YTD statistics for the cleanup.
2. The Settings tab showing all general settings for the plugin.
3. The CRON setting tab for running the cleanup on schedule.

== Changelog ==

= 1.0.11 =  
Add static logging.

= 1.0.10 =  
Update readme to add info about google charts.

= 1.0.8 =  
Code cleanup.

= 1.0.0 =  
Initial release.