# Team: artkatats2020
Oreilly Architectural Katas Project 2020

# Project: Farmacy Food Information System

## Owner requirements
> We, given all of these locations and given our setup, we had to create a system that allows our customers have visibility 
into what items are available to purchase,
where they are, and be able to pick up items at any one of our distribution centers. 
And essentially, our customers are dispersed. 
And right now, we're focused in Detroit, city of Detroit. But sooner rather than later, 
we'll be expanding to other geographies. 

>to browse meals that are available at a specific location without unnecessary personalization like that. 
we will be replenishing the smart fridges as well as the coffee shops and such. 

## Owner context

- The company is startup with low customer base and very restricted budget. Big ambition to expand the business quickly and enrich  provided services.


## Requirements

- The solution should quickly address the current actual need.
- The solution should be easy to modify and expand as all business processes are not stable and can be evolve quickly.
- The solution should be envolable to the more sophisticated solution to address initial startup idea of personalized healthy food.

## Definitions

Inventory point  - a physical place where meals are stored for sales (smart fridge, cafe), or being cooked (Kitchen). It might have POS terminal and it has physical or virtual inventory database.

## Decisions

[Solution architecture style](adr/solution_architecture_styel.md)

[Asynchronous communication between inventory points](adr/async_comm_inventory_points.md)

[Progressive Web App](adr/progressive_web_app)

## Diagram

1. [Farmacy Food Landscape diagram](diagrams/landscape.png)
2. [Farmacy Food Information system diagram](diagrams/system.png)
3. [Inventory service diagram](diagrams/inventory_point.png)
4. [Customer web application diagram](diagrams/customer.png)
