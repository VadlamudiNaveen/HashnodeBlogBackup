## How to Perform Huge Data Loads

Hello, folks today we are going to discuss one of the Major, technical challenge, that every data engineer Will face while performing Huge data loads.

** Le Every Data Engineer: **

<a href="https://imgflip.com/i/6al780"><img src="https://i.imgflip.com/6al780.jpg" title="made at imgflip.com"/></a>

# Part - 1

**Data Transfer is Not Simple: ** 

Setting Up Data Pipelines is not all about, establishing a connection to the Source System, it actually involves core CS.


![data-pipeline.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1648578865402/RNIuaAc1A.png)

%[https://datacater.io/blog/2020-06-30/what-is-a-data-pipeline.html]


** The Core CS Part: **

a) Firstly it involves, Configuring a Bug Free, Optimized Data Pipelines. (If You are Writing your own connectors or Custom Built Tool)

b) Secondly, Using any Tool Like Matillion helps us, allieviate reinventing the wheel.

c) Also, implementing a custom CDC pipeline. (Any SCD Technique)

d) Handling Load on Source Network Infrastructure (Onprem Systems).

e) Fetching data from Source Database, by setting the Optimal Concurrency.

f) Calculating the daily Data Transferred from System 1 to System 2.

g) Finally, Validating the Data, which should exactly Look Like source system.


> Remember the steps,  described above purely follows the state diagram of the data transfer from one system to another system.


# Part -2 

** Huge Data Loads: **

a) Let us assume you have a table of size ``100 GB``, in a source system, where you need to send the data to a cloud DW and also should build a Datalake on the way.

b) Firstly, no tool in the world will ingest data continuously for about 12-15 hrs, because everything has its own limitations, as``S3`` cant have a connection for around, 12 + hrs.

<a href="https://imgflip.com/i/6albp8"><img src="https://i.imgflip.com/6albp8.jpg" title="made at imgflip.com"/></a><div><a href="https://imgflip.com/memegenerator"> The Real Feeling of DE</a></div>

c) Inorder to Overcome the limitations, and reduce the probability of failures, which makes you feel frustrated, its always better to split the data into multiple chunks and load it accordingly.
 
** Solution: **

![5x2jdk.jpg](https://cdn.hashnode.com/res/hashnode/image/upload/v1638953342080/G_Nt0WXRA.jpeg)


d) Because we had, a nightmare in loading huge data, so we splitted the data, on the basis of years,
 i.e (Beginning -2010) 
      (2010- 2015)
      (2015- present).


** If you found, this article useful please hit the like button.
     As it sparks my interest in writing my real world experiences. **

Finally, feel proud, that you have learnt something, through my experience.
Thanks For Reading. Keep Spreading Love and also Keep Spreading Knowledge.



    


