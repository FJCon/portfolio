---
layout: ../../layouts/post.astro
title: Interface for laser cutting tracking application
description: Dive into the zen world of a developer's morning, where vinyl beats meet artisanal brews, setting the tone for a day of inspired coding and design.
dateFormatted: July 19th, 2024
---
![Fronted](/portfolio/assets/images/api-tav/05.png)
## Introduction


On the [previous post](http://fjcon.github.io/portfolio/post/api-rest-cutting) I wrote about an API Rest development using Java with Spring boot Framework which provides information from and SQL Server database created by a laser cutting software.

As you know, I've been working hard on this app for a while, and I'm happy to announce that I now have a considerable portion of the API finished.

## Frontend development
![Fronted](/portfolio/assets/images/api-tav/animacion-recorrido.gif)

I have developed some screens that display crucial information for the cutting process, such as:

* Customers: View a complete list of customers for whom outages are being made and a filter bar.
* Sheet thicknesses: Shows the sheet thicknesses scheduled to be cut by the equipment, broken down by client.
* Nests: Presents the pieces contained in a metal sheet.
* Pieces per nest: Provides specific information about each piece within a nest.

The next step involves developing menus to manage the status of nests. These functionalities will allow users to:

* Update the status of a nest from "programmed" to "cut" (for machine operators)
* Assign a storage location and update the status to "stored" (for storage personnel)

## Future features

The application will soon implement a robust user management system with different user roles and permissions. This will ensure:

* **Machine Operator Control:** Only machine operators can update the status of a nest from "programmed" to "cut". They will not be able to revert the status.
* **Storage Management:** Storage personnel can assign a location where the pieces are stored and update the status to "stored."

Implementing these features will involve developing new menus and screens on the frontend, authentication and logic on the backend, and adding new tables to the database to manage user roles, permissions, and related information.