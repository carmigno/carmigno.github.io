---
layout: post
title: "Which data specialist do I need?"
author: "Carmine Gnolo"
usemathjax: true
hidden: true
---
# Which data specialist do I need?

Identity crises are a surprisingly common challenge in data teams. **Are we data engineers? Are we analytics engineers? Who knows.** The responsibilities of a team grow organically with the Data Platform they work on, and they often end up not perfectly aligned with any industry standard. 

Existential angst though, while it gave us quite a few masterpieces in art and literature, is not going to help you implement the data intelligence strategy of your dreams.

I know it sounds dark, but hey, great news, **we are here to help**! I will explain in this article the method we came up with to cope with those issues and **find your data-self**, in a cheaper and less time-consuming way than spending three months backpack-traveling!

<img src="https://images.pexels.com/photos/4458420/pexels-photo-4458420.jpeg?cs=srgb&dl=pexels-yan-krukov-4458420.jpg&fm=jpg" style="zoom:8%;" />

​												 	*A recruiter being asked for a Data Analyst with Kubernetes knowledge.*

As a first step, we need to understand well the challenge we are approaching, and the motivations that would justify putting any effort into a better understanding of the team and calling it by the right name.

Let's have a look at the **negative consequences** that picking the **wrong label** can have for your team:

* Trying to recruit a new member, both you and the recruiter will receive many job **applications that don't fit your needs** and will struggle to find anyone to fill the position
    *This wastes time from both sides and deteriorates the relationship between the hiring manager and the recruiter*
* If you don't know what is the **rarest skill** for that job description, you will not give it the right weight when picking a new recruit
    *If you need, and manage to find, a Data Engineer who knows Kubernetes, maybe you should think twice before letting them go*
* The probability to **hire the wrong person** will be higher
    *They may find out the job was not what they expected and leave after an expensive recruiting and onboarding process. Or they may stay and opt for silent quitting.*
* Other **teams will not understand** clearly what are the responsibilities of your team and what they can expect from them
    *Your team will not be added to the right meetings, decisions will be taken without involving them*
* It will be harder for the team members to understand **in which direction they should improve**

Now that you can see why and how this can go very, very wrong, we can move on to fixing it.

## The role comparison table
How are we going to address this issue? Using one of the oldest tricks from the engineering book, older even than a slide rule, a **reference table**. 

The problems we want to solve here are three: 
1. What is the **best description** of what my team currently does?
2. What are the **tech skills** that are available in my team but are **uncommon** among professionals with the same job description?
3. If I hire someone with a specific job description, what can I expect them to be **familiar with**, and in what measure?

The tech skills table is designed to help you with those pitfalls. In the first column, we present a list of **typical data-related technical skills**, and in the other columns, we show the level of the skill typically associated with a specific job title: `++` for deep knowledge or daily involvement, `+` basic knowledge or occasional involvement, and an empty spot for skills that are not related to that job title. We decided on purpose to go for symbols instead of more detailed descriptions, to minimize the complexity of the method.  

We leave an empty column for you to fill with the level of skill of your team. 

The table is thought to be used as below: 
1. Copy the table in a text editor (with no wrapping)
2. Fill the column with the level of knowledge or involvement of your team with a specific technology
3. Delete the rows you did not fill in, to consider only the tech in your stack
4. Compare your team's column with the other ones: pick the data role that is closest to your team
     * If you notice that you cannot decide between multiple roles, then your team is between those
5. Find which skills are creating issues

     * The tech skills that are available in your team but are not listed in the role you picked, are the ones that are going to be difficult. So now you know.

     * The tech skills that are marked with a `*` symbol are in general uncommon

     * The tech skills that are not on the list, are in general uncommon in the data market.

**Assumptions for the table**

* We consider an environment in which the teams **are big enough to have the roles as clearly separated as possible** (e.g. a big corporate environment). In smaller companies, the roles overlap, but having them divided in the table will help you understand how they combine;
* We assume that the basic knowledge of **Python** and **Git** is fundamental for everyone involved, so we don't include them in the table.

| **Tech skills** / **Roles**                         | Data engineer | Analytics Engineer | Data Analyst | Data Scientist | ML Engineer | Cloud/DevOps Engineer | **Your team** |
| --------------------------------------------------- | :-----------: | :----------------: | :----------: | :------------: | :---------: | :-------------------: | :-----------: |
| AWS/Azure/GCP (General platform knowledge)          |      ++       |         +          |      +       |       +        |      +      |          ++           |               |
| Bash                                                |       +       |                    |              |       +        |      +      |          ++           |               |
| Business knowledge                                  |               |         +          |      ++      |       +        |      +      |                       |               |
| CI/CD pipelines (GitHub, Gitlab, Concourse, ArgoCD) |       +       |                    |              |       +        |      +      |          ++           |               |
| Cloud storage solutions                             |      ++       |                    |              |                |             |           +           |               |
| Cloud infrastructure                                |       +       |                    |              |                |             |          ++           |               |
| Dashboarding (Tableau/PowerBI) / Data Visualization |               |                    |      ++      |       ++       |      +      |                       |               |
| Data modeling                                       |       +       |         ++         |              |                |      +      |                       |               |
| Dbt                                                 |       +       |         ++         |              |                |      +      |                       |               |
| Deployment of ML models as webapps (R-Shiny, Flask) |       +       |                    |              |       +        |     ++      |                       |               |
| Docker                                              |       +       |                    |              |       +        |      +      |          ++           |               |
| ELT/ETL pipelines                                   |      ++       |         +          |              |       +        |      +      |                       |               |
| Exploratory data analysis                           |               |         +          |              |       ++       |      +      |                       |               |
| Git (administration)                                |       +       |                    |              |                |             |          ++           |               |
| Golang*                                             |               |                    |              |                |             |           +           |               |
| Hadoop*                                             |      ++       |                    |              |       +        |      +      |                       |               |
| Implementation of business rules in SQL             |       +       |         ++         |      ++      |       +        |      +      |                       |               |
| Infrastructure as code (Terraform/Ansible/Chef)     |       +       |                    |              |                |             |          ++           |               |
| Kafka/Data Streaming*                               |      ++       |                    |              |       +        |      +      |                       |               |
| Kubernetes                                          |               |                    |              |                |             |          ++           |               |
| Machine Learning Models                             |       +       |                    |              |       ++       |     ++      |                       |               |
| Pandas/Numpy                                        |       +       |         +          |      ++      |       ++       |     ++      |                       |               |
| Reporting                                           |               |                    |      ++      |       +        |      +      |                       |               |
| SQL                                                 |      ++       |         ++         |      ++      |       +        |      +      |                       |               |
| Scala*                                              |      ++       |                    |              |       +        |      +      |                       |               |
| Snowflake/DWH                                       |       +       |         ++         |      +       |       +        |      +      |                       |               |
| Spark                                               |      ++       |                    |      +       |       ++       |     ++      |                       |               |

## Example
With all those rules and those tables, this method **looks more complicated than it actually is**. Let's make a practical example to give you a feel of what you can do with this. 

At our company X, we have a Data Engineering team. We want to increase capacity, so we decide to hire a new unit. 
We want to use the skills table to help us have a better perspective on the hiring process.
To do so, we copy the whole table, fill the column for our team, turn to bold the values in the columns that match, 
then sort the rows by the team column's content, descending:

| **Skills** / **Roles**                              | Data Engineer | Analytics Engineer | Data Analyst | Data Scientist | ML Engineer | Cloud/DevOps Engineer | **Your Team** |
| --------------------------------------------------- | :-----------: | :----------------: | :----------: | :------------: | :---------: | :-------------------: | :-----------: |
| CI/CD pipelines (GitHub, Gitlab, Concourse, ArgoCD) |       +       |                    |              |       +        |      +      |        **++**         |      ++       |
| Infrastructure as code (Terraform/Ansible/Chef)     |       +       |                    |              |                |             |        **++**         |      ++       |
| AWS/Azure/GCP (General platform knowledge)          |    **++**     |                    |      +       |                |      +      |        **++**         |      ++       |
| Cloud storage solutions                             |    **++**     |                    |              |                |             |           +           |      ++       |
| Cloud infrastructure                                |     **+**     |                    |              |                |             |          ++           |       +       |
| Kafka/Data Streaming*                               |    **++**     |                    |              |       +        |      +      |                       |      ++       |
| Kubernetes                                          |               |                    |              |                |             |        **++**         |      ++       |
| ELT/ETL pipelines                                   |      ++       |       **+**        |              |     **+**      |    **+**    |                       |       +       |
| Bash                                                |     **+**     |                    |              |     **+**      |    **+**    |         **+**         |       +       |
| Dbt                                                 |     **+**     |         ++         |              |                |    **+**    |                       |       +       |
| Docker                                              |     **+**     |                    |              |     **+**      |    **+**    |         **+**         |       +       |
| Git (administration)                                |     **+**     |                    |              |                |             |          ++           |       +       |
| SQL                                                 |     **+**     |         ++         |      ++      |     **+**      |    **+**    |                       |       +       |
| Snowflake/DWH                                       |     **+**     |         ++         |    **+**     |     **+**      |    **+**    |                       |       +       |
| Spark                                               |     **+**     |                    |    **+**     |       ++       |     ++      |                       |       +       |
| Golang*                                             |               |                    |              |                |             |         **+**         |       +       |

You can immediately see a problem here: our team shares competencies with both Data Engineering and Cloud/DevOps Engineering. Which one should we pick? 

We deliberately don't establish a numeric rule to decide: this is a tool to give a clearer perspective on the situation, and it cannot substitute the hiring manager in making this decision.

In our case, we know that the team is already established as a Data Engineering team, the members are happy with that title, and the `+` skills do match the ones we would expect from a Data Engineering team. 

We can also see, though, that our team skills include several that are uncommon among Data Engineers: 
* Deep knowledge of Kubernetes
* Deep knowledge of CI/CD
* Deep knowledge of Infrastructure as code
* Familiarity with Golang (already uncommon by itself)

Among the data engineering skills, Kafka (marked with ++) is considered rare. 

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/26/Franz_Kafka%2C_1923.jpg/1920px-Franz_Kafka%2C_1923.jpg" style="zoom:15%;" />

​																  *Kafka judging you for the state of your technical debt*

This means that: 
* I should look for a Data Engineer
* The knowledge of Kafka is less available, but if someone has this knowledge it will be a Data Engineer, who will have a higher probability of also matching the other required skills
* The knowledge of Kubernetes, CI/CD, and Golang will be rare to find combined with the other Data Engineering skills, and this makes it pretty hard to fill the position
* I may have to either compromise and pick someone who only partially fits the profile or who is less skilled, or reorganize the team - for instance adding a Cloud/DevOps Engineer to it

There you are. Things look more clear now, don't they?

## What's next?

I hope this article will make it a bit easier to hire your next team member and to explain to others what you do. Please understand that this is on purpose a simplification of a very complex scenario. In case you would like to go deeper in detail, I would suggest [following Andreas Kretz on LinkedIn](https://www.linkedin.com/in/andreas-kretz/): for a funny turn of events, I found out he was working on something similar in the same week I started writing this. If you have opinions or suggestions, please [reach out on my LinkedIn page](https://www.linkedin.com/in/gnolo/). 

Good luck with your search!

# References
* [DP-203 study guide](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE4MbYT)
* [AZ-400 study guide](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE3VP8d)
* [dbt's definition of analytics engineer](https://www.getdbt.com/what-is-analytics-engineering/)
* [KDnuggets definitions of data scientist and data engineer](https://www.kdnuggets.com/2021/05/data-scientist-data-engineer-data-careers-explained.html)
