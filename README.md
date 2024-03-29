# Time Tracking Essentials

## Keboola Blocks Intro (Scaffold Prerequisite)
Looker Blocks powered by Keboola are designed to work in tandem with corresponding Keboola Scaffolds in the Keboola Connection platform. Similar to Blocks in nature, Keboola Scaffolds are templatized use-cases that can be instantly deployed into the Keboola platform, providing the whole data management and processing chain required to populate the Looker dashboards.

## Block Overview
This Block connects to data from Keboola “Time Tracking" Scaffold into Looker. Its purpose is to provide quick out-of-the-box end-to-end integration and functionality to be used either stand-alone or to be combined with other data, into scorecards, etc. In order to set up the Keboola data feed, please contact us: here.

## Data and Block Structure
The Block contains two LookML dashboards:

 - Overview for checking KPIs and overall performance of your team
 - Employee Detail for checking performance and workload of particular users


The underlying model contains two explores:

 - Project Management - contains all of the important tables and data from Time Tracking tool processed by Keboola Connection.
 - Workdays - simple one table explore used in merged queries to be able to work more easily with calculating number of working days in time periods etc.

As a standard, the data gets provided as a connection to Keboola-provided Snowflake, but it can be easily changed to your own DWH of choice during the setup.

## Customization
The LookML contents of this block can also be modified/extended to best fit all use cases.
This block utilizes Refinement files for customization. For more information on using refinements to customize marketplace blocks, please see [this documentation](https://docs.looker.com/data-modeling/marketplace/customize-blocks).
