---
layout: post
title: Case Study Healthy Eating
subtitle: A responsive website and app to help users find and save recipes
cover-img: 
thumbnail-img:
share-img: 
# gh-repo: daattali/beautiful-jekyll
# gh-badge: [star, fork, follow]
# tags: [test]
comments: false
---

  <html>
    <head>
      <style>
        table {
        width: 100%;
        }
      table {
        text-align: left;
        padding: 8px;
      }
      tr:nth-child(odd){background-color: #f2f2f2}
      th{
        background-color: #F55E61;
        color: white
      }
      </style>
    </head>
  </html>

## Project Overview
<br>

### The Problem
Users find it challenging to find recipes that fit their diet restrictions promptly.

### The Goal
The goal is to create a website/app that allows users to filter out recipes that do not suit their needs when browsing.

<br>

## Research and Define the Problem
<br>

### Hypothesis
If users have an easy way to search for recipes that meet their needs and are able to save them, then they will be able to maintain a healthy diet more easily.

<br>

### Personas
In order to understand the user better, I developed personas based on my user research. 

<img src="/assets/img/h-e-persona1.png" alt="Mother Persona Example" style="box-shadow: 5px 5px 10px grey;">
<span class="caption">One user is a working mother who needs to find “kid-friendly” meals in a timely manner.</span>
<br>

<img src="/assets/img/h-e-persona2.png" alt="Elderly Persona Example" style="box-shadow: 5px 5px 10px grey;">
<span class="caption">The other is an elderly man who has been recommended a better diet by his doctor.</span>
<br>

### Journey Mapping
To further expand on these personas and to make them feel more like real people, I developed user journey maps. This process allowed me to identify the importance of saving recipes and a grocery list. In order to make the project more manageable, I decided to focus on the importance of saving recipes for the time being.

<b>Name: Sai</b>
<br>Goal: Collect healthy, kid-friendly recipes
  <table class="table2">
      <tr>
        <th> ACTION </th>
        <td><b>Use a search engine trying to find healthy recipes</b></td>
        <td><b>Pick recipes</b></td>
        <td><b>Save links</b></td>
        <td><b>Return to links</b></td>
        <td><b>Make a grocery list</b></td>
      </tr>
      <tr>
        <th>TASK LIST</th>
        <td><u>Tasks</u>
        <br>A. Type in keywords
        <br>B. Click first website
        <br>C. Scroll through and read recipes</td>
        <td><u>Tasks</u>
        <br>A. Scour recipe page to find ingredients, time to make, etc 
        <br>B. Click on other recipes and repeat</td>
        <td><u>Tasks</u>
        <br>A. Copy links to recipes 
        <br>B. Paste links to notes app</td>
        <td><u>Tasks</u>
        <br>A. Open notes app
        <br>B. Struggle to determine which note has the recipes
        <br>C. Browse and find them</td>
        <td><u>Tasks</u>
        <br>A. Open each recipe
        <br>B. Copy and paste ingredient list to notes app
        <br>C.Consolidate same ingredients </td>
      </tr>
      <tr>
        <th>FEELING ADJECTIVE</th>
        <td>Frustration</td>
        <td>Impatient, Dejected</td>
        <td>Impatient</td>
        <td>Flustered</td>
        <td>Impatient</td>
      </tr>  
      <tr>
        <th>IMPROVEMENT OPPORTUNITIES</th>
        <td>Create an easy way to browse recipes </td>
        <td>Create a consistent card with necessary information</td>
        <td>Allow recipes to be saved in a list</td>
        <td>Allow lists to be clearly labeled or grouped</td>
        <td>Attach ingredient lists to cards and will consolidate groups of recipes</td>
      </tr>
  </table>
  <br>
<b>Name: Fernando</b>
<br>Goal: Collect recipes that follow doctor's recommendation
  <table class="table2">
      <tr>
        <th> ACTION </th>
        <td><b>Search for recipes that using doctor’s words</b></td>
        <td><b>Find website</b></td>
        <td><b>Bookmark recipes</b></td>
        <td><b>Locate recipes prior to making grocery list</b></td>
        <td><b>Grocery list</b></td>
      </tr>
      <tr>
        <th>TASK LIST</th>
        <td><u>Tasks</u>
        <br>A. Use search engine to find recipe lists
        <br>B. Find a lot of “health blogs”
        <br>C. Read through
</td>
        <td><u>Tasks</u>
        <br>A. Find website focused on recipes that follow restrictions
        <br>B. No pictures, just lists </td>
        <td><u>Tasks</u>
        <br>A. Look up how to bookmark on browser
        <br>B. Bookmark each individual recipe</td>
        <td><u>Tasks</u>
        <br>A. Open bookmarks, but struggle to find each recipe
        <br>B. Spend time scrolling</td>
        <td><u>Tasks</u>
        <br>A. Open all recipes
        <br>B. Scroll to the ingredient list 
        <br>C. Handwritten shopping list</td>
      </tr>
      <tr>
        <th>FEELING ADJECTIVE</th>
        <td>Frustration</td>
        <td>Dejected</td>
        <td>Frustrated</td>
        <td>Impatient</td>
        <td>Impatient</td>
      </tr>  
      <tr>
        <th>IMPROVEMENT OPPORTUNITIES</th>
        <td>Label and define labels for diet restrictions  </td>
        <td>Use images and clearly labeled recipe names</td>
        <td>Allow recipes to be saved in a list</td>
        <td>Make ingredient list easy to access</td>
        <td>Compile a grocery list that can be printed</td>
      </tr>
  </table>
<br>

### Competitive Audit
  <table class="table1">
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
        <td>Sites were often full of blogs that made navigating more challenging</td>
      </tr>  
      <tr>
        <td>Saving feature being available when viewing full recipe</td>
        <td>Many sites had too much information on the page</td>
      </tr>
  </table>
  <br>

## Exploring the Design
<br>

### User Flow
![Healthy Eating User Flow Chart](/assets/img/h-e-userflow.png)
<span class="caption">In order to get a sense of what screens I may need I created a user flow chart. This chart helped me understand that I needed a home page, some sort of navigation page, and a full recipe page.</span>
<br>

### Wireframing
![Healthy Eating Lofi Wireframes](/assets/img/h-e-lofi-wireframes.png)
<span class="caption">Now that I knew what screens I needed and had competition to reference, I drafted some paper wireframes. I used these paper wireframes to put together digital wireframes. While putting these screens together, I found that it would possibly be helpful to give users access to the lists they are saving their recipes to.</span>
<br>

### Prototyping

<img align="right" width="250" src="/assets/img/h-e-lofi-prototype.gif" alt="Healthy Eating Low Fidelity Prototype">

Since mobile screens are so small, I needed to minimize the information on the main page. To do this, I added a hamburger menu that gives the user access to their profile, their lists, a search page, and a way back to the home page.

<br>The main challenge I experience was the navigation 
<br>and search bar. Since I wanted to keep the homepage 
<br>clutter-free, I elected to make a separate 
<br>navigation page.

<br>In terms of allowing the user to save recipes, I decided 
<br>to use the widely used + symbol with a pop-up for the 
<br>user to interact with and then receive a confirmation.

Feel free to check out the [Lofi Mobile App Prototype](https://www.figma.com/proto/qwc4SbThKsxZS2YmGiqXuV/Health-Food?node-id=1-3&page-id=0%3A1&scaling=scale-down&starting-point-node-id=1%3A3&viewport=433%2C126%2C0.17) to see experience the user flow.

<br>

## Refining the Design
<br>

### Usability Testing
To get feedback on my low-fidelity prototype, I conducted a remote moderated usability study with 5 users. My general findings were as follows:
* Information needs to be prioritized
* The search engine needs to be more easily accessible
* Users need a clear way to go back and forth between screens
* Icons need to be more readable
* Screen transitions were inconsistent
* Some interactions weren’t clear to users

<br>

### Mock Ups
![Healthy Eating Mock Ups](/assets/img/h-e-mockups.png)
<span class="caption">To make the app feel more like it was being viewed on a phone, I added a status bar to all the screens. This helped me notice that I had more space in my top bar to include the search bar. This allowed me to remove the search page from the side menu, and instead have the filters be accessible after users type something into the search bar.
To determine my color palette, I used a random palette generator and focused on colors that would read as “fresh” to users, so my main colors were greens and a light yellow, like that of vegetables.</span>
<br>

### High Fidelity Prototype

<img align="right" width="250" src="/assets/img/h-e-hifi-prototype.gif" alt= "Healthy Eating High Fidelity Prototype">

<br>Besides the search engine, much of the design stayed 
<br>true to the low-fidelity prototype. The inclusion of the 
<br>search bar in the header gives the users more freedom 
<br>to browse. I did keep the idea of only having the filters 
<br>accessible after something has been input 
<br>into the search bar.

<br>The other big change was how the lists were displayed. 
<br>I initially wanted the list images to be stacked in a 
<br>diagonal to give the look of stacked cards, but after 
<br>colors and images were added, it looked too busy. In 
<br>order to differentiate between the listed recipes 
<br>versus the lists of lists, I kept the stacked card 
<br>look but had them stacked horizontally instead.

Check out the [High Fidelity Prototype](https://www.figma.com/proto/qwc4SbThKsxZS2YmGiqXuV/Health-Food?node-id=215-52&page-id=215%3A51&scaling=scale-down&starting-point-node-id=215%3A52&viewport=-343%2C371%2C0.71) to experience the final user experience for the mobile app.

<br>

### Responsive Website
![Healthy Eating Desktop Mockup](/assets/img/h-e-desktop.png)

After creating the app, I needed to create a responsive website as well in order to accommodate more users.

There is currently only a tablet and desktop website design.

My process to translate this mobile app to a website for a larger screen was a bit of a challenge initially, as the recipe cards did not look right on a larger screen and in multiple columns. This is why I decided to create something similar to the cards, but in more of a grid layout without borders.

With the extra space, I was able to include some more information as well. This allowed me to include the website logo, name, and a way to access filters without typing into the search bar.

Experience how this website works on [Tablet](https://www.figma.com/proto/0l6ep0JM4RmVudx2TM3vyr/Arcade-Support?node-id=162-1808&page-id=162%3A1807&scaling=scale-down&starting-point-node-id=162%3A1808&viewport=577%2C591%2C0.16) or [Desktop](https://www.figma.com/proto/0l6ep0JM4RmVudx2TM3vyr/Arcade-Support?node-id=667-4981&page-id=667%3A4980&scaling=contain&starting-point-node-id=667%3A4981&viewport=838%2C550%2C0.15).

<br>

## Final Thoughts
<br>

### What insights have I gained from this project?
I developed a greater understanding of how mobile websites translate to both tablet and desktop screens. I had a lot of information to organize for this website/app, so I had to find creative ways to prioritize information.

### How would I continue this project?
Before this website/app should be launched in any way, the current prototypes should be tested once more in order to refine the concept. As is the case with any site, there is always room for innovation.