# Introduction to Essbase

## Introduction

Oracle Essbase is a business analytics solution that uses a proven, flexible, best-in-class architecture for analysis, reporting, and collaboration. Essbase delivers instant value and greater productivity for your business users, analysts, modelers, and decision-makers, across all lines of business within your organization.

Oracle Essbase on cloud helps you to build your company’s cloud strategy efficiently by avoiding data and business process fragmentation. Oracle Essbase can be easily deployed on Oracle Cloud Infrastructure, which can then be widely used to solve simple to complex business analytics use cases across all industries. It is designed to help you model business performance levels and deliver what-if analyses for varying conditions. Using Oracle Identity Cloud Service, Essbase can utilize enterprise-wide user profiles to work and integrate with Oracle Cloud.

## Features of Oracle Essbase

• Oracle Essbase provides a complete set of tools and features for deriving and sharing data insights.

• Both large organizations and small teams can share data easily, without the need to manage or consolidate multiple versions of spreadsheets, and quickly perform ad hoc analysis of the spreadsheet data.

• Application developers can utilize interfaces that enable them to extend, customize, and embed rich analytic experiences in the application flow.

• Oracle Essbase, is a multi-dimensional engine that allows you to extract data from any source, handle real-time data and collaborate easily.

• With Essbase on cloud you can create and manage Essbase applications from Microsoft Excel by using Cube Designer.

• Create connections and data sources for drill-through, data loads, and dimension builds.

• We can use Essbase to collect collaborative data, create scenarios, and perform what-if analysis using Smart View.

## Essbase 19c VM Architecture 

![](Architecture.png)

## Working with Essbase

During our workshop we will help a fictitious company Dynamic Corporation to perform financial analysis. Dynamic Corp. is a high-tech manufacturer of hard disk drives. It is headquartered in California, Bay Area. Dynamic Corp., has its operations spread across multiple regions. Various departments within Dynamic Corp. performs financial analysis.

Financial analysis develop number of reports as follows:

*1. Sales department*

* Monthly sales revenues by product , by customer
* Current year actual, budget , forecast data
* Customer sales by region

*2. Finance department*
			
* Current year actual and budget data
* Monthly product development reports 
* Details of company cost structures

Dynamic Corp. extensively use Microsoft Excel application for Financial reporting. Financial analyst at Dynamic Corp. are well versed with use of Excel. But with growing business they find it difficult to manage reporting with excel. They found out Excel is a widely used tool for two dimensional data analysis, but presents enlisted limitations when used for multidimensional data analysis -

1. Disconnected
2. Data Security Risks
3. Error Prone
4. Scalability issues
5. Lack of audit trails/log mechanism
6. Tedious and multi-step calculations

To overcome these limitations and to proceed with an efficient and precise multi-dimensional data analysis, Essbase comes to the rescue. Essbase can be defined as a multidimensional database (comparable to Excel pivot table) offering following benefits -

• One single location for data – all analysts are using the same data, business drivers, and metrics for calculating departmental budgets.

• Standardization of Business Drivers – budget drivers can be loaded and calculated by the administrator so that all budgets are using the same methodology.

• Security – the administrator can apply security to certain dimensions and members, giving users access to only the data that they are responsible for. This allows more participation from the field in the budget process.

• Workflow - the administrator can completely control the workflow and approval process. Planning Units must be reviewed and approved before going up to the next approval level.

• Easy to consolidate – Hyperion Planning data is stored in a Hyperion Essbase OLAP database using hierarchies that make the consolidation process effortless.

With the above stated benefits, it’s certainly worthwhile to understand the nitty-gritty of Essbase, its benefits, features and applications. This lab intends towards providing a holistic view of Essbase, its features, and applications.


### Required Artifacts

This lab will require the following -

1. An Oracle public cloud tenancy where you have the resources available to provision an ADW instance with 2 OCPUs, an Essbase   instance with 2 OCPUs

2. [Smartview Plugin](https://docs.oracle.com/en/cloud/paas/analytics-cloud/essug/download-and-run-smart-view-installer.html) 

3. [Cube Designer Plugin](https://docs.oracle.com/en/cloud/paas/analytics-cloud/essug/install-smart-view-cube-designer-extension.html)

### Installing Smartview Plugin 

#### Smart View Prerequisites
1. The latest release of Smart View
2. On the Oracle Technology Network Downloads tab, the latest release for Smart View is always certified.
3. Microsoft Office 2010, 2013 or 2016
4. .NET Framework 4.0

*Note:* You must use .NET Framework 4.5 if you are installing Smart View from Essbase without saving the installer locally.

#### Installation Steps 
1. Navigate to link https://www.oracle.com/middleware/technologies/epm-smart-view-downloads.html to download latest Smart View for office.
2. On the Smart View download page on Oracle Technology Network, click Download Now, and then click Accept License Agreement. If the Oracle sign-in page is displayed, then sign in with your Oracle user name (usually your email address) and password.
3. Follow the steps for your browser to download the .zip file, and save it to a folder on your computer.
4. Go to the folder that you used in Step 5, and then double click smartview.exe to start the installation wizard.
5. Select a destination folder for Smart View, and then click OK. For new installations, Smart View is installed by default in: C:\Oracle\smartview.
9. If you are upgrading an installation of Smart View, then the installer defaults to the folder where you previously installed Smart View.
10. When the installation is complete, click OK.

### Installing Cube Designer

1. On the Smart View ribbon, select Options, and then Extensions.
2. Click the Check for updates link.
3. Smart View checks for all extensions that your administrator has made available to you.
4. Locate the extension named Oracle Cube Designer and click Install to start the installer.
5. Follow the prompts to install the extension.

![](image1.png)

## Register for Free Oracle Trial Account
* Bookmark this page for future reference.

* Please click on the URL to receive your [Free Account](https://myservices.us.oraclecloud.com/mycloud/signup?language=en&sourceType=:ex:tb:::RC_NAMK190227P00084:PredictDemandML_ADW_HOL&SC=:ex:tb:::RC_NAMK190227P00084:PredictDemandML_ADW_HOL&pcode=NAMK190227P00084) and complete all required steps. When you complete the registration process you'll receive a $300 credit that will enable you to complete the lab for free. Additionally, you'll have 1000s of hours left over to continue to explore the Oracle Cloud.

* Soon after requesting your trial you will receive an activation email. Once that email is received and you have logged in to your environment you can begind the lab.

Access the labs using our web-friendly interface [here](https://bangaloresolutionshub.github.io/essbaseworkshop/) 
