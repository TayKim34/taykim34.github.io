---
layout: post
title: Case Study Arcade Support
subtitle: A website feature that allows users to submit a support ticket regarding any problems found at the arcade.

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
      tr:nth-child(even){background-color: #f2f2f2}
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
Customers may find that an arcade machine may not be working properly. To ensure the issue is fixed as soon as possible, the customer needs a way to communicate with an attendant about the issue.

### The Goal
The goal is to create a feature in an arcade website to allow users to submit support tickets.

<br>

## Research & Defining the Problem
<br>

### Hypothesis
If the user has an easy way to communicate any issues regarding the arcade machines, then there will be a greater chance that the machines will be in working order sooner.

<br>

### Personas
To understand the users that would face such a problem, I developed a couple of personas.

<img src="/assets/img/a-s-persona1.png" alt="Gamer Persona Example" style="box-shadow: 5px 5px 10px grey;">
<span class="caption">A passionate gamer that used arcade time as decompressing time.</span>
<br>

<img src="/assets/img/a-s-persona2.png" alt="Mother Persona Example" style="box-shadow: 5px 5px 10px grey;">
<span class="caption">A caring mother wants their kids to play in a working and clean environment.</span>
<br>

### Journey Mapping
To understand the issues these users may face, I developed a journey map for each.

<b>Name: Austin</b>
<br>Goal: Play games to relax after work
  <table class="table2">
      <tr>
        <th> ACTION </th>
        <td><b>Arrive at arcade</b></td>
        <td><b>Get quarters</b></td>
        <td><b>Play a game</b></td>
        <td><b>Play another game</b></td>
        <td><b>Leave arcade</b></td>
      </tr>
      <tr>
        <th>TASK LIST</th>
          <td><u>Tasks</u>
         <br>A. Drive to arcade
          <br>B. Park
          <br>C. Make sure I have wallet on me before leaving car</td>
        <td><u>Tasks</u>
        <br>A. Get cash from atm
        <br>B. Insert cash into change machine
        <br>C. Get quarters from change machine </td>
         <td><u>Tasks</u>
          <br>A. Notice favorite racing game
         <br>B. Insert quarters to start playing
         <br>C. Enter game
         <br>D. Play game but notice one button isn’t responding properly</td>
        <td><u>Tasks</u>
        <br>A. Sit at a different racing game
        <br>B. Notice it’s a little sticky
        <br>C. Get wet paper towels from bathroom to remove stickiness
        <br>D. Insert quarters
        <br>E. Play game </td>
          <td><u>Tasks</u>
          <br>A. Feels I should look for attendant to complain about gross and not working machines
          <br>B. Is too nervous/tired to talk to anyone at this time
         <br>C. Return to car</td>
      </tr>
      <tr>
        <th>FEELING ADJECTIVE</th>
        <td>Excitement</td>
        <td>Content</td>
        <td>Frustrated, Irritated</td>
        <td>Disgusted, Dejected, Content</td>
        <td>Frustrated, Nervous</td>
      </tr>  
      <tr>
        <th>IMPROVEMENT OPPORTUNITIES</th>
        <td></td>
        <td></td>
        <td>An indication that the machine isn’t working properly</td>
        <td>MA way to inform that a machine isn’t clean</td>
        <td>CA way to contact an attendant quickly</td>
      </tr>
  </table>
  <br>
<b>Name: Mary</b>
<br>Goal: Drop off kids at arcade for fun
  <table class="table2">
      <tr>
        <th> ACTION </th>
        <td><b>Go to arcade</b></td>
        <td><b>Drop kids off</b></td>
        <td><b>"Mommy Time"</b></td>
        <td><b>Pick up kids</b></td>
        <td><b>Leave arcade</b></td>
      </tr>
      <tr>
        <th>TASK LIST</th>
          <td><u>Tasks</u>
         <br>A. Drive to arcade
          <br>B. Corral children from car to arcade</td>
        <td><u>Tasks</u>
        <br>A. Hand cash to oldest
        <br>B. Remind them to call or text if there's any issues
        <br>C. Tell them you'll be back in a few hours</td>
         <td><u>Tasks</u>
          <br>A. Get coffee to go
         <br>B. Check phone to ensure there wasn't an immediate issue with the kids
         <br>C. Browse clothing store</td>
        <td><u>Tasks</u>
        <br>A. Return to arcade around expected time
        <br>B. Ask kids about how much fun they had
        <br>C. One child tattles about another making a mess</td>
          <td><u>Tasks</u>
          <br>A. Look for attendant to tell about the mess and apologize
          <br>B. Doesn't immediately see one
         <br>C. Return to car</td>
      </tr>
      <tr>
        <th>FEELING ADJECTIVE</th>
        <td>Tired, Frustrated</td>
        <td>Determined, Concerned, Flustered</td>
        <td>Relieved, Concerned, Content</td>
        <td>Relieved, Flustered</td>
        <td>Guilty, Flustered</td>
      </tr>  
      <tr>
        <th>IMPROVEMENT OPPORTUNITIES</th>
        <td></td>
        <td>A way to view the state of the arcade</td>
        <td></td>
        <td>A way to communicate a mess has been made</td>
        <td>A way top contact an attendant quickly</td>
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
![Arcade Support User Flow Chart](/assets/img/a-s-userflow.png)
<span class="caption">From what I’ve seen from personal experience and my competitive audit, starting the user flow by scanning a QR code to make it easier for users to access the website quickly while in the arcade. This flow generally follows the steps it takes to find, fill out, and submit a form. This allowed me to get a sense of what pages I’d need to include.</span>
<br>

### Wireframing
![Arcade Support Lofi Wireframes](/assets/img/a-s-lofi-wireframes.png)
<span class="caption">I initially started with the screens necessary for the user to be able to submit a form. After that, I determined what pages would be typically included in an arcade’s website and made a site map from there.</span>
<br>

### Prototyping
<img align="right" width="250" src="/assets/img/a-s-lofi-prototype.gif" alt="Arcade Support Low Fidelity Prototype">

While this project focused on the support feature of 
<br>an arcade website, I still needed to design a full website for the feature to be included in. I had the website focus on <br> a small handful of information, which I narrowed down based on my research of competitors.

I included assets from the Figma community to make 
<br>the forms more interactive for user testing. I 
<br>also added a Safari browser frame to make the 
<br>app feel a bit more authentic.

View the [Low Fidelity Mobile Prototype](https://www.figma.com/proto/0l6ep0JM4RmVudx2TM3vyr/Arcade-Support?node-id=24-112&page-id=0%3A1&scaling=scale-down&starting-point-node-id=25%3A160&viewport=354%2C561%2C0.11)

<br>
<br>
<br>
<br>

## Refining the Design
<br>

### Usability Testing
Before moving on to adding colors and images, I needed users to test the core functionality of my website design. I conducted a remote moderated usability test with 5 different users. My findings were as follows:
* Most users want a quick submission process, so users would prefer a more simple process.
* Users like having options, but not too many, so I should ensure all categories for support forms are necessary and incorporate an “other” option.
* Most users don’t like large text boxes, so the forms should avoid using large text boxes when possible.
* Some users interpret “malfunction” differently than intended, so forms should use more straightforward and clear language.
* Some users struggled with finding/reading some features, so the design should have enough contrast and highly visible coloring.

<br>

### Mock Ups
![Arcade Support Mock Ups](/assets/img/a-s-mockups.png)

<span class="caption"> When deciding on colors for this arcade website, I decided to work with an arcade logo. I used the logo to give me a sense of direction for the typography and the color palette. 
Once images were added and the background darkened, it appeared some sections were blending in together. To avoid this, I included dividers in the main color.</span>
<br>

### High Fidelity Prototype
<img align="right" width="250" src="/assets/img/a-s-hifi-prototype.gif" alt="Arcade Support High Fidelity Prototype">

<br>Viewing the prototype helps me see if the ideas worked 
<br>as intended. The main thing that helped a lot was having 
<br>the clicked category a different color from the rest of 
<br>the categories allowed the user to know exactly what 
<br>page they were on. I used blue as the primary color and 
<br>pink as the accent color. I decided this because pink 
<br>is a bit harder on the eyes, so I wanted to minimize
<br>the use as much as possible, but kept it because it 
<br>contrasted well next to the blue.

View how the [High Fidelity Mobile Prototype](https://www.figma.com/proto/0l6ep0JM4RmVudx2TM3vyr/Arcade-Support?node-id=162-1834&page-id=162%3A1807&scaling=scale-down&starting-point-node-id=162%3A1808&viewport=577%2C591%2C0.16) works
<br>
<br>
<br>
<br>
<br>
<br>
<br>

### Desktop Website
![Arcade Support Desktop Mockup](/assets/img/a-s-desktop.png)
<span class="caption">Converting this mobile design to a desktop screen was initially challenging. The core of my initial website design very much favored a mobile screen since that would likely be where most users would be seeing the website.
Check out the [High Fidelity Desktop Prototype](https://www.figma.com/proto/0l6ep0JM4RmVudx2TM3vyr/Arcade-Support?node-id=667-5037&page-id=667%3A4980&scaling=contain&starting-point-node-id=667%3A4981&viewport=954%2C658%2C0.21) to see how the interactions work on a larger screen.</span>

<br>

## Final Thoughts
<br>

### What insights have I gained from this project?
I gathered a lot of insight into how forms are made and how to make them more accessible to more users.

### How would I continue this project?
The main way to continue this project would be to conduct more usability testing, as the high-fidelity designs have yet to be tested. It would also be ideal to have a tablet version of the website eventually.
