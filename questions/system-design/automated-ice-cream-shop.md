# Automated Ice Cream Shop

We're moving into the future with an entirely automated ice cream shop! Our all robot workforce makes ordering ice cream a breeze!

## Overview

![ICE_CREAM](./../diagrams/ICE_CREAM.drawio)

### Services

- `Ordering Service` - provides an interface for users to select their ice cream and toppings
- `Scooping Service` - reads the order and scopes the ice cream to a centralized location
- `Toppings Service` - reads the order and fetches the toppings to a centralized location
- `Mixing Service` - takes the ice cream and toppings, and mixes them
- `Cone Service` - reads the order and fetches a cone or a cup to a  centralized location
- `Delivery Service` - delivers the completed ice cream to the customer
- `...` - more services?

## Question

- How would you architect this system?
- http/rpc or some other communication methodology
- What Services are necessary? Which are not?
- Service Orchestration, Choreography?
- How do you deal with an ice cream failure?

## Pivot

Ice cream was great but our profit margins were too low. Let's pivot to pizzas?

- How would you retool our existing architecture to work for pizzas?
  - What Services do we still need?
  - What Services can we get rid of?

## Why This Question

A comparable system would be a lab or publishing flowing; where we'd need to have interchangeable components that could easily be swapped in a Direct Acyclic Graph or ["DAG"](https://en.wikipedia.org/wiki/Directed_acyclic_graph) or even a tree.
