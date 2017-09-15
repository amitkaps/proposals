# REST, GraphQL, gRPC ... navigating the server communication landscape in serverless architectures

**Abstract**
Serverless architectures use third-party services and is run in short-lived containers. You might have come across the term: Function-as-a-service. They have two major advantages:
1. Reduce operational costs
2. Reduce technical debt

This leads to a situation of applications sitting inside many containers communicating with each other and also communicating with the front-end/client. In other words:
1. client-server communication
2. server-server communication

How to achieve the communication and what are the advantages and tradeoffs are important to understand, as one embarks on architecting such a system.

A typical data science project will have a lot of microservices. (Eg: microservices for various data ingestion pieces, microservices for model training, etc)

This talk will give an overview of the most common methods and advantages and use cases for them, with specific focus on data science projects. 

**Technical Level**
Beginner

**Outline**
The broad outline of the talk is as follows:

1. What is serverless architecture?
2. Thinking cloud for data science
3. A brief overview on how containers help scale up and down the data science workflow
4. server-server communication (Examples and ways to achieve them)
5. Client-server communication (Examples and ways to achieve them)
6. Closing thoughts

This will be more of a "how-to" talk. While the concepts are introduced, the focus will be more on how these are achieved using Python and on cloud.

**Requirements**
Some knowledge of cloud computing helps. Going through Martin Fowler's blog will definitely be helpful: https://martinfowler.com/articles/serverless.html

