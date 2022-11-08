# What is it like being a Data Engineer 😏

Hello everyone, In this article, I will elaborate the
 
1. Who is a Data Engineer and the existing types.
* Current State of Data Engineering.
* Plus the persisting issues in Data Engineering Domain.  
   
Okay a bit of introduction about me, I used to be a Cloud Data Engineer, with a special focus on the following stack.

* Snowflake
* AWS - (S3 For Data Lake)
* Matillion For Ingestion + Datawarehouse Building 
* Snowsight for Pipeline Monitoring
* Python for data Transformation While Loading

Anyways, let's get into the content.

** Section 1: Who is a Data Engineer? **


![dataengineer.jpg](https://cdn.hashnode.com/res/hashnode/image/upload/v1667879634049/5Zw76L4oc.jpg align="left")

If any organization ever had huge amounts of data sitting on its servers and wanted to extract useful insights, from it. You should definitely require a person with data skills that can manage the process of the entire transformation and build a data warehouse.

Being said that, one should also have decent skills in one of the major cloud platforms 
i.e (AWS, Azure, or GCP). Because most of the work nowadays is primarily based on the migration of data, and building scalable reports on the cloud. 

Ok, now let us classify the data engineers... 

** Section 2: 
     Classification of Data Engineers: ** 

![classification.jpg](https://cdn.hashnode.com/res/hashnode/image/upload/v1667880272177/dZCdH5S8J.jpg align="left")

Okay, let's not waste the time! There are total 2 classifications 

* Type - A: One who uses tools! 🙃 (i.e ELT like Matillion, Airflow, dbt, Talend, Hevo etc)
* Type - B: One who writes Code for Pipeline 😀... 

**1. Type - A: ** 

Few People say, using UI-based tools doesn't make them real engineers. Instead, they are called ELT/ ETL developers that specialize in one particular tool. Anyways, in my opinion, something which is easy to learn doesn't mean it is not valuable. Because  No Code or Low Code tools increases the productivity of a developer, where he can primarily focus on implementing the core logic, instead of worrying about memory leaks in a pipeline etc.
Moreover, using low code tools doesn't mean you are not writing any code, yet you are still required to code your business requirement, either in SQL or python.


![pros_cons.jpg](https://cdn.hashnode.com/res/hashnode/image/upload/v1667882083787/nWROfUcC6.jpg align="left")

**2. Type -B: **

These are the engineers, that write **code** in order to orchestrate the process, of data ingestion, data transformation, data pipeline monitoring etc. Also, they are called the  MAANG ones, where they have their internal tools that are developed by their engineering teams. And they make sure that, the existing ones don't break while adding new functionalities. Therefore, most of the effort of the programmer goes into understanding the technical boundaries of the system, and implementing a solution based on it.

So to differentiate, its quite simple, when an organization doesnt want to be vendor locked. They go with second type and will implement everything from the scratch. Which is ok. **But the problem is they are reinventing the wheel, by building everything in a bottomup manner.** 

The above section has been hugely inspired by the above awesome 
[article](https://medium.com/google-cloud/graduating-from-etl-developer-to-data-engineer-7663dfbdfd2d).

** Section 3: 
    What are the core differences between UI based / Code Based Implementation: **

* ✨Mostly, It becomes tool-dependent 🤐

**Example:**
If a project is using Matillion, it has everything inside it like
But when you are willing to move to other tools the features are pretty same but the issue is with learning and unlearning.

* ✨ And Due to component and UI based Engineering it has many drawbacks in the context of Software Engineering.
Example:
Code Versioning etc isnt possible via UI Based Tools Cause when the code inside it changes then the Git cant reflect what the internal code has changed. Because of the JSON based artifacts.

* ✨Also, deployment of Code in UI-based tools becomes so cumbersome when we have multi-model deployments.

*Takeaway: *
![perfect.jpg](https://cdn.hashnode.com/res/hashnode/image/upload/v1667889889123/7x5TXtjRb.jpg align="left")

** Few Alternative Solutions: **

* ✨ So finally, i can say [DBT](https://www.getdbt.com/product/what-is-dbt/) is a great tool that uses Software Engineering Principles, to Build and Deploy Data Models in any environment. (But the problem is it doesn't have data ingestion features).

* ✨ Also, no code/low-code tools may not solve all the problems because of their own limitations and a perfect tool isn't yet developed. 

* ✨Moreover, the fundamentals remain, very common just like in any domain. like performing CDC, maintaining audit and building data warehouses etc.


Anyways, if you have learnt anything from the following article please hit the like button.
So that it helps me improve my thinking and content-building skills. :) 











  











 


 