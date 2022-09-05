---
layout: post
title: "Which data specialist do I need?"
author: "Carmine Gnolo"
usemathjax: true
hidden: true
---

# Which data specialist do I need?

Identity crises are a surprisingly common challenge in data teams. Are we data engineers? Are we analytics engineers? Who knows. 
The responsibilities of a team grow organically with the Data Platform they work on, and they often end up not perfectly aligned with any industry standard. 

Picking the wrong label for your team has many negative consequences:
* Trying to recruit a new member, both you and the recruiter will receive many job applications that don't fit your needs and will struggle to find anyone to fill the position
  * *This wastes time from both sides and deteriorates the relationship between the hiring manager and the recruiter*
* If you don't know what is the rarest skill for that job description, you will not give it the right weight while picking a new recruit
  * *If you need and manage to find a Data Engineer who knows Kubernetes, maybe you should think twice before letting them know*
* The probability to hire the wrong person will be higher
  * *They may find out the job was not what they expected and leave after an expensive recruiting and onboarding process. Or they may stay and opt for silent quitting.*
* Other teams will not understand clearly what are the responsibilities of your team and what they can expect from them
  * *Your team will not be added to the right meetings, decisions will be taken without involving them*
* It will be harder for the team members to understand what are the skills that they should improve to grow further

Now that you can see why and how this can go very, very wrong, let's discuss what to do to fix it. 

## The role comparison table
With this post, we want to offer you a simple tool to help you understand better your team and your data needs. 

The problems we want to solve here are three: 
1. What is the **best description** of what my team currently does?
2. What are the **skills** that are available in my team but are **uncommon** among professionals with the same job description?
3. If I hire someone with a specific job description, what can I expect them to be familiar with, and in what measure?

The skills table will help you with this. We list the most common skills in the data sector, and for each most

Please note: we assume that Python and Git knowledge is needed by everyone involved.  

| **Skills** / **Roles**                              | Data engineer | Analytics Engineer | Data Analyst | Data Scientist | ML Engineer | Cloud/DevOps Engineer | **Your team** |
| --------------------------------------------------- | ------------- | ------------------ | ------------ | -------------- | ----------- | --------------------- | ------------- |
| AWS/Azure/GCP (General platform knowledge)          | ++            |                    | +            |                | +           | ++                    |               |
| Bash                                                | +             |                    |              | +              | +           | +                     |               |
| Business knowledge                                  |               | +                  | ++           | +              | +           |                       |               |
| CI/CD pipelines                                     | +             |                    |              | +              | +           | ++                    |               |
| Cloud data storage and infrastructure               | ++            |                    |              |                |             | +                     |               |
| Dashboarding (Tableau/PowerBI)                      |               |                    | ++           | ++             | +           |                       |               |
| Data modeling                                       | +             | +                  |              |                | +           |                       |               |
| Data visualization                                  |               | +                  | ++           | ++             | +           |                       |               |
| Dbt                                                 | +             | ++                 |              |                | +           |                       |               |
| Deployment of ML models as webapps (R-Shiny, Flask) | +             |                    |              | +              | ++          |                       |               |
| Docker                                              | +             |                    |              | +              | +           | +                     |               |
| ELT/ETL pipelines                                   | ++            | +                  |              | +              | +           |                       |               |
| Explorative data analysis                           |               | +                  |              | ++             | +           |                       |               |
| Git (administration)                                | +             |                    |              |                |             | ++                    |               |
| Golang*                                             |               |                    |              |                |             | +                     |               |
| Hadoop*                                             | ++            |                    |              | +              | +           |                       |               |
| Implementation of business rules in SQL             |               | ++                 | ++           | +              | +           |                       |               |
| Infrastructure as code (Terraform/Ansible/Chef)     | +             |                    |              |                |             | ++                    |               |
| Kafka/Data Streaming*                               | ++            |                    |              | +              | +           |                       |               |
| Kubernetes                                          |               |                    |              |                |             | ++                    |               |
| Machine Learning Models                             |               |                    |              | ++             | ++          |                       |               |
| Pandas/Numpy                                        | +             | +                  | ++           | ++             | ++          |                       |               |
| Reporting                                           |               |                    | ++           | +              | +           |                       |               |
| SQL                                                 | +             | ++                 | ++           | +              | +           |                       |               |
| Scala*                                              | ++            |                    |              | +              | +           |                       |               |
| Snowflake/DWH                                       | +             | ++                 | +            | +              | +           |                       |               |
| Spark*                                              | +             |                    | +            | ++             | ++          |                       |               |


# References
* [DP-203 study guide](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE4MbYT)
* [AZ-400 study guide](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE3VP8d)
* [dbt's definition of analytics engineer](https://www.getdbt.com/what-is-analytics-engineering/)
* [KDnuggets definitions of data scientist and data engineer](https://www.kdnuggets.com/2021/05/data-scientist-data-engineer-data-careers-explained.html)