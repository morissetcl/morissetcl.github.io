---
layout: post
title: Rails + RabbitMQ + ActionCable. How to build realtime microservice. (Part 1)
date:   2020-05-05 18:00:47 +0100
medium_url: https://medium.com/@clementrollon/rails-rabbitmq-actioncable-how-to-build-realtime-microservice-part-1-c25bf00c5187
lang: en
---

For few month I am building a crawler to collect restaurant informations and their dishes. The aims is to have as much restaurants as possible in my DB. Have a huge quantity of data is cool but display them is better.
So I decided to build an other app dedicated to display data in real time, and only that. In the context of this article we will name this app Dashboard.
The initial spec is to display charts and datas up to date (means don’t refresh data only once a week/day/hours. We want data updated in real time)
