# Urbana Public Works

## Organization Name
City of Urbana - Public Works Department
https://www.urbanaillinois.us/departments/public-works

## Local Sponsor
Sanford Hess, IT Director of Urbana 

## Overview
Urbana Public Works supports the City’s infrastructure and its residents – so it has many responsibilities!  From streets to trees, parking meters to bike racks, and facility maintenance to tornado cleanup – Public Works does it all. 

## Problem Statement
 In July 2018, Public Works rolled out a unified Work Order system to support its Divisions.  The system routes “requests” for work, tracks “work order” assignments, captures information about the use of “resources” (workers and equipment), and monitors incomplete work.  These are normal functions of a Work Order system.  Before this system was in place, statuses were not managed in a single database – or may have tracked by whiteboard. 
 
That’s the good news.

The bad news is that after more than 12 months of use, the system is NOT realizing its potential.  Collected data is no being used for decision-making, partly because the data has holes – with missing fields.  In October, the City will begin effort to improve the data entry screens to streamline and improve them.  We know that data entry is not consistent, and that entry can be redundant.  They can be better.

So, our question is: “In what ways is our data bad?”

Your answers will tell us how to improve our capture.  Some examples:

-  Some information should cluster, and we can use those relationships to set coding defaults.  For example, the “Problem” entered in the data can populate a suggested “Task” – but very few of our codes are set up that way.

- Useful information may be blank on some records – which corrupts any analysis by that attribute.  These fields can be made required (and hopefully can be defaulted, too).

- Redundant information may exist – which would be in fields that have the same value frequently.  In some cases, redundant information can be combined and one entry field can be eliminated.

By the way, our data is also interesting on its own!

More than 3,400 Work Orders and 1,300 Requests show an impressive amount of work over 14 months.   The data is well structured, easily queryable, and meaningfully titled.  We welcome projects that find meaningful insights into the work.

## Evaluation criteria

We are looking for suggestions here, not conclusive answers.  Real-world application is appreciated, although creativity is also encouraged.  

## Data Details

Three data sets are provided, with the same data in .csv and .xlsx forms:

- Work_Request_Detail - contains all Requests.  Requests can be generated internally or externally.  Requests are routed to the appropriate Divisions.  Some Requests will result in Work Orders, while others may be closed with no further action.

- Work_Order_Summary_Information - contains all Work Orders.  Overall information to classify the Work Order, plus summary cost information if Resources were charged to the work.  There is one row per Work Order.

- Work_Order_Resource_Detail - contains details about the resources charged to the Work Order.  There could be many rows for a Work Order, as they are recorded with details about the task, date, resource, etc.
