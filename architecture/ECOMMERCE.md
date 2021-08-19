# Architecture Questions

Clothing Shop E-Commerce Event-Based System

> [insert diagram]

- We have a Frontend that serves as the interface to our customers
- We want to keep an active list of recently viewed items and we want that list to feed into a recommendation system
- We also have a pricing system that will dynamically move the price based on demand
- We have an inventory system that needs to keep an active eye every users cart and their purchasing

- A customer submits and order and we need to make sure several teams are notified:
  - purchasing
  - our marketing team
  - our warehouse team
  - our product engineering teams
  - our CC integration team
- All of these teams fan out to do their respective duties/services

## Questions

- How would you design this Architecture?
- How would you select the various languages and frameworks?
- How would you construct the software teams?
- How would you start the design?
- How would you roll out changes?
- How are you measuring performance of the platform?
- How are you measuring overall success?
- What are the bottlenecks in your design?
- What "completely breaks everything"?
- How are you factoring in failure?
- How are you keeping track of upstream/downstream changes and service compatibility?
- 3am and the site is not working, what is your process for reconciliation?
