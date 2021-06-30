# NoSQL Research Lab

## Explainer

Up until now in the cohort we have stored data only in what are known as relational databases (SQL is the most well known type of relational DB querying language). Relational databases structure our data into tables. Today we will learn about a different type of database: a non-relational one.

## Lab

In this lab you will be researching, either individually or in groups, answer to the following questions about noSQL databases. The intention is for you to spend some time learning about the fundamental differences between the type of databases we have seen before and the new type we will be learning about today. Even more importantly, you will learn about why two types of databases are used, and what situations fit each type of db.

## Setup

Fork and clone this repository and answer questions as you research directly in the README. You do not have to submit this lab, but you will want to have it on hand for reference in the future.

# Questions:

1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL?

NoSQL is not a relational database. Also known as 'not only SQL'. Approach to database design that provides flexible schemas for the storage and retrieval of data beyond the traditional table structures found in relational databases.

2. What are some of the common arguments for using a non-relational versus a relational db?

NoSQL database looks like a folder with files rather than a table.

Advantage of a non-relational database is the ability to store and process large amounts of unstructured data.

3. In this class we will be using the document style of non-relational databases. What are the charecteristics of a document based db?

Built around JSON-like documents, document databases are both natural and flexible for developers to work with.

Documents map to the objects in your code, so they are much more natural to work with.

A document’s schema is dynamic and self-describing, so you don’t need to first pre-define it in the database.

Lightweight, language-independent, and human readable, JSON has become an established standard for data interchange and storage.

Documents are independent units which makes it easier to distribute them across multiple servers while preserving data locality.

4. In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the priamry difference between how Mongo is maintained vrs SQL?

SQL databases are used to store structured data while NoSQL databases like MongoDB are used to save unstructured data.

MongoDB is used to save unstructured data in JSON format.

MongoDB does not support advanced analytics and joins like SQL databases support.

5. Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo.

SQL stores data in tables, where columns are the attributes and rows are the value/property of the table. all these tables live inside databases.

In MongoDB, data is stored in a collection, thats similar to MySQL tables. a collectiong consists of many documents in which data is stored in JSON format of key-value

6. What is an example situation where a Mongo database makes sense versus a non-relational db?

Any type of database looking for flexibility on how the database will grow.

reference: https://www.simform.com/mongodb-vs-mysql-databases/
