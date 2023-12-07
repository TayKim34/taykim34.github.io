---
layout: post
title: 2022 Case Study Healthy Eating
subtitle: A responsive website and app to help users find and save recipes
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
# gh-repo: daattali/beautiful-jekyll
# gh-badge: [star, fork, follow]
# tags: [test]
comments: false
---


## Project Overview

### The Problem

Users find it challenging to find recipes that fit their diet restrictions promptly.

### The Goal

The goal is to create a website/app that allows users to filter out recipes that do not suit their needs when browsing.

## Research and Define the Problem

### Hypothesis

If users have an easy way to search for recipes that meet their needs and are able to save them, then they will be able to maintain a healthy diet more easily.

### Personas

In order to understand the user better, I developed personas based on my user research. One user is a working mother who needs to find “kid-friendly” meals in a timely manner. The other is an elderly man who has been recommended a better diet by his doctor.

### Journey Mapping

To further expand on these personas and to make them feel more like real people, I developed user journey maps. This process allowed me to identify the importance of saving recipes and a grocery list. In order to make the project more manageable, I decided to focus on the importance of saving recipes for the time being.

<html>
<head>
<style>
table {
    border-collapse: collapse;
    width: 100%;
}
table{
    text-align: left;
    padding: 8px;
}

tr:nth-child(even){background-color: #f2f2f2}

th{
background-color: #D162A4;
color: white
}
</style>
</head>
<body>

<h3>Competitive Audit</h3>

<table>
  <tr>
    <th>Competitor Strengths</th>
    <th>Competitor Weaknesses</th>
  </tr>
  <tr>
    <td>Strong use of navigation system using categories</td>
    <td>Most sites did not label food allergies</td>
  </tr>
  <tr>
    <td>Saving features being available on most websites</td>
    <td>Sites were often full of blogs that made navigating more challenging<td>
  </tr>
  <tr>
    <td>Saving feature being available when viewing full recipe</td>
    <td>Many sites had too much information on the page</td>
  </tr>
</table>
</body>
</html>


## Exploring the Design

### User Flow

In order to get a sense of what screens I may need I created a user flow chart. This chart helped me understand that I needed a home page, some sort of navigation page, and a full recipe page.

### Wireframing

Now that I knew what screens I needed and had competition to reference, I drafted some paper wireframes. I used these paper wireframes to put together digital wireframes. While putting these screens together, I found that it would possibly be helpful to give users access to the lists they are saving their recipes to.

### Prototyping

Since mobile screens are so small, I needed to minimize the information on the main page. To do this, I added a hamburger menu that gives the user access to their profile, their lists, a search page, and a way back to the home page.

The main challenge I experience was the navigation and search bar. Since I wanted to keep the homepage clutter-free, I elected to make a separate navigation page.

In terms of allowing the user to save recipes, I decided to use the widely used + symbol with a pop-up for the user to interact with and then receive a confirmation.

Feel free to check out the [Lofi Mobile App Prototype](https://www.figma.com/proto/qwc4SbThKsxZS2YmGiqXuV/Health-Food?node-id=1-3&page-id=0%3A1&scaling=scale-down&starting-point-node-id=1%3A3&viewport=433%2C126%2C0.17) to see experience the user flow.

## Refining the Design

### Usability Testing

To get feedback on my low-fidelity prototype, I conducted a remote moderated usability study with 5 users. My general findings were as follows:
* Information needs to be prioritized
* The search engine needs to be more easily accessible
* Users need a clear way to go back and forth between screens
* Icons need to be more readable
* Screen transitions were inconsistent
* Some interactions weren’t clear to users

### Mock Ups

To make the app feel more like it was being viewed on a phone, I added a status bar to all the screens. This helped me notice that I had more space in my top bar to include the search bar. This allowed me to remove the search page from the side menu, and instead had the filters be accessible after users type something into the search bar.

To determine my color palette, I used a random palette generator and focused on colors that would read as “fresh” to users, so my main colors were greens and a light yellow, like that of vegetables.

### High Fidelity Prototype

Besides the search engine, much of the design stayed true to the low-fidelity prototype. The inclusion of the search bar in the header gives the users more freedom to browse. I did keep the idea of only having the filters accessible after something has been input into the search bar.

The other big change was how the lists were displayed. I initially wanted the list images to be stacked in a diagonal to give the look of stacked cards, but after colors and images were added, it looked too busy. In order to differentiate between the listed recipes versus the lists of lists, I kept the stacked card look but had them stacked horizontally instead.

Check out the [High Fidelity Prototype](https://www.figma.com/proto/qwc4SbThKsxZS2YmGiqXuV/Health-Food?node-id=215-52&page-id=215%3A51&scaling=scale-down&starting-point-node-id=215%3A52&viewport=-343%2C371%2C0.71) to experience the final user experience for the mobile app.

### Responsive Website

After creating the app, I needed to create a responsive website as well in order to accommodate more users.

There is currently only a tablet and desktop website design.

My process to translate this mobile app to a website for a larger screen was a bit of a challenge initially, as the recipe cards did not look right on a larger screen and in multiple columns. This is why I decided to create something similar to the cards, but in more of a grid layout without borders.

Will the extra space, I was able to include some more information as well. This allowed me to include the website logo, name, and a way to access filters without typing into the search bar.

Experience how this website works on [Tablet](https://www.figma.com/proto/0l6ep0JM4RmVudx2TM3vyr/Arcade-Support?node-id=162-1808&page-id=162%3A1807&scaling=scale-down&starting-point-node-id=162%3A1808&viewport=577%2C591%2C0.16) or [Desktop](https://www.figma.com/proto/0l6ep0JM4RmVudx2TM3vyr/Arcade-Support?node-id=667-4981&page-id=667%3A4980&scaling=contain&starting-point-node-id=667%3A4981&viewport=838%2C550%2C0.15).

## Final Thoughts

### What insights have I gained from this project?

I developed a greater understanding of how mobile websites translate to both tablet and desktop screens. I had a lot of information to organize for this website/app, so I had to find creative ways to prioritize information.

### How would I continue this project?

Before this website/app should be launched in any way, the current prototypes should be tested once more in order to refine the concept. As is the case with any site, there is always room for innovation.
