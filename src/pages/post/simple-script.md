---
layout: ../../layouts/post.astro
title: Simple script to save several time
description: This is a post about how creating a simple script to filter data in a frontend interface can save a lot of time. 
dateFormatted: July 7th, 2023
---

![Photo of the script](/portfolio/assets/images/filter-script/01.png)

## **Introduction**

While my primary work lies in the field of mechanical engineering as a designer, I am always looking for opportunities to apply my computer science skills to improve efficiency in my work.

In this case, the web application that we use to manage material orders for equipment manufacturing has some limitations, such as the lack of tools to efficiently filter results.

## **Some mistakes ordering materials**

The problem I faced directly affected the calculation of the kilograms of sheet metal needed for purchase. This was because the table contained rows with a thickness value of zero, which generated errors in the calculation of the volume and, therefore, in the amount of material required.


![Photo of the script](/portfolio/assets/images/filter-script/03.png)

In this situation and not having access to the server, I wrote a small script (which I pasted into the browser console) with which I managed to select the table that is rendered with information from the backend and filter the zero-thickness elements. This allowed me to identify that the table contained more than 6,400 rows, of which 191 presented the error.

Compared to manually reviewing each row of the table, the script automated the task, reducing the time invested by more than 90%. This translates into savings in working hours that can be allocated to other more productive activities.

This experience reaffirms the importance of thinking outside the box and taking advantage of the tools at our disposal to solve problems efficiently.

You can watch how I used the scrip in [this video](/portfolio/assets/images/filter-script/video.mp4) 📽