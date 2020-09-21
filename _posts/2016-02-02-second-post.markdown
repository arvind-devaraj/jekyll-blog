---
layout: post
title:  "MongoDB - NoSQL database"
date:   2016-02-02
categories: technology computer news
tags: holiday

# Author.
author: Arvind
---
![picture](https://placehold.it/250x150)
MongoDB is an open source, cross-platform, and the most popular NoSQL database program.

Database,collections and documents are terminology in mongodb.

Each database has collections which in turn has documents.
The data stored is in the form of JSON style documents (rows).
It is useful in building scalable websites with millions of users.
Mongodb – Relational databases were not designed to cope with the scale and agility challenges that face modern applications.But they built to take advantage of the commodity storage and processing power available today. NoSQL is the term used to define the new database architecture that scales well in a distributed environment.

Mongodb supplies a javascript environment with BSON object storage(a binary adaption of JSON).So reading and writing data from the node is extremely efficent.It stores incoming records in memory,so it is ideal in high write situations.

Since incoming records are stored in memory,inserrting data into mongo is non-blocking,making it ideal for logging operations and telemetry data.

It also supports javascript functions inside queries,making it very powerful in read situations,including Mapreduce queries.