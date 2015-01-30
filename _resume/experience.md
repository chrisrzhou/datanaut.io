---
layout: default
title:  Experience
weight: 2
---
# Experience
This section summarizes my work experience, and the future career goals that I am working towards.

A big part of my work experience has been to master the industry/domain knowledge, so that I am able to use my general analytical strengths to identify chokepoints in business process inefficiencies, and engineer creative and unique solutions that simplify the original problems.

------

## Work

> Disclaimer: I love data, MVC design patterns, reducing process waste, and building stuff*.

<sub>*stuff = visualizations, reports, database, schemas, anything really :)

### Business Intelligence Analyst
- **[Reliant Energy / NRG Energy](http://www.nrg.com/):** *2010 - Present*
    - **Proactive proponent for modernizing reporting and business insights and visualizations.**
        - The business team employs the traditional workflow of Excel reporting and manual file exchanges between teams to gather information to make decisions every week.  To-date, I have built over five R [`shiny`](http://shiny.rstudio.com/gallery/) applications that require little maintainence, and provides business analysts with *self-serving and live* querying of data and visualization, as contrasted by waiting on various teams to deliver weekly reports.
        - Constantly exploring newer technologies that are agnostic to software implementation and business processes.  I am not against proprietary software, but I feel strongly that our design and use of software should be generic, in order to provide flexibility for the company to evolve and change.  As a result, I have built [`d3.js`](https://github.com/mbostock/d3/wiki/Gallery) applications that function in a standalone manner by simply taking in data inputs and producing reuseable visualizations.
        - For more details on examples of visualization projects, please refer to the [Projects Section](projects.md).  A public-facing *industry-specific* visualization can be found here: [PUC Powertochoose.org](http://ec2-54-183-164-175.us-west-1.compute.amazonaws.com:3838/PowerToChoose/)
    - **Focus on building scalable and general/industry solutions and apply them to specific business requirements.**
        - Worked on a big-impact *organizational change project* to help consolidate business logic and calculations across our company and multi-brands.  My major contribution was to help *abstract* commonalities of electricity pricing and margin calculations within the industry, and to build and design business logic (with Python classes and object inheritance) that applies across multiple teams and brands.
    - **Enhance business process efficiency and work with technical teams for implementation.**
        - Scaled storage and querying of supply cost transactions on a weekly basis to an *on-demand basis* through careful evaluation of IT tables and processes that are impacted.  Redesigned parts of the original ETL processes in Oracle and SQL to create a dynamic solution to cost querying, which now provides the business with close-to-live updates to the data.
        - Designed and implemeneted a lightweight database system for tracking transmission cost updates in the [ERCOT](http://www.ercot.com/) power grid.  This system is barely 1000 rows deep across 5 tables, but has the capability of generating *any combinations (over a million combinations)* of accurate transmission costs in the industry.  This reflects the true state of the market as opposed to the static downloads of unneccessarily huge datasets that we previously depended on.
    - **Other accomplishments**
        -  Built the foundation of pricing and supply cost calculations that our business operates with, serving over a million Residential customers every year.
        -  Worked with IT teams to interface with Excel report automation through the use of VBA calling Oracle API procedures (personally I'm not a fan of workflows using VBA, but this was not debatable).
        -  Ad-hoc automation and process-improvement projects across the business over many teams.  These usually require creative solutions and I am able to implement them across a variety of tools/technologies (R, Python, VBA, Oracle)

------

## Goals
I am a strong believer that mankind will work itself out of a job.  And I also believe that this is a *good* thing.  The world we live in is still largely *inefficient and wasteful*, and the next generation of improvements will be towards reducing inefficiencies.

In the data realm, I believe that the uprising of parallelized computing and gradual move to open-source tools and file formats is a good sign that best practices and conventions are merging into a *reuseable and implementation-agnostic platform* for companies and consumers to transact on.

My goals for myself towards this personal view of the world's future state is to:
- Learn and *apply* data science and machine learning to real world problems.  Currently I have only learned portions of the materials (via MOOCs), but I would love to be in a real setting to apply and rapidly scale up my skillset and interest with this exciting realm.
- Keep improving on the MVC design pattern, and focus on the *ironically* complex task of simplicity.
- Continue building on my growing interest of data visualizations and master future-proof libraries that are able to take simple data structures and render results into very specific but conventionalized visualizations i.e. `d3.js`! :)
- Find ways to impact the business and worldly community on moving towards data and technology agnostic conventions and practices in efforts to reduce system inefficiencies that are created due to specific requirements that often cloud a simpler solution to the problem.
