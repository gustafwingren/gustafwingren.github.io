---
title: "Introduction to Wingrens Kök!"
date: 2022-07-27
categories:
  - Wingrens  Kök 
tags:
  - UX/UI
  - Wireframe
  - dotnet
  - C#
  - Azure
  - Angular
---

This is going to be the first post in a new series where I will share my thoughts about the whole process in making a new website, Wingrens Kök.

In this post I will go through some of the decisions that I have done and some background to the project.

## Background
Since I have a big heart for food, trying new food and developing new recipes I have had a hard time managing recipes in a notebook so I have tried a few different websites where you can add your own recipes. But I have always found that they are lacking a few things. 

So since I want to deepen my own knowledge in development I think that it is a good project. 
In this project I will be responsible for the whole process from creating use cases to actually use it in my daily life. 

## Features
I have a few things that I have been missing in the other recipe services that I have been using. I will try to summerize them below.

### Scale a recipe
A few of the services actually have this feature. For me it's a must that you can change a base recipe on the fly. But when doing this the user must be aware that the time doesn't change as much. 

### Covert between units 
This is a really good feature that I have been missing. Most of the recipes that I use are normally written in volume and not by weight. For me a recipe should be written by weight. Mostly so it is easy to reproduce an outcome very precisely. 

### Versions for recipes
One thing that is really good when developing a new recipe is that you create a recipe by trying it out in iterations. And between these iterations you need to track what you changed and that is something that I have been missing. 

### Printable recipes
I have been trying and trying again to get nice recipes that have been printed from the web. My goal is that you can mark certain recipes and then send them to a service which actually prints them in book format. We'll see if I ever come to that but that would be a really nice feature. 

## Technical limitations
In this section you'll get to know the different cornerstones that the project will be using. Most of the desicions I have made is only because I want to deepen my own knowledge within these areas. 

### C#
First and formost I will write the backend parts with C# and dotnet. 

### Angular
For the frontend I will use Angular. This is probably the worst choice since the project isn't really a SPA(single page app). But I think that with routes this should be doable. 

### Other
I haven't decided in what kind of SQL the project will using. Probably I will use a normal SQL hosted in Azure. 
Other than that I will use scss, typescript and I plan to use Auth0 as a service for storing users. 

## Next step
The next step and next post in this series is that I create most of the scenarios and use cases that will be the foundation for the project. 

Stay tuned for the next post. Since I'm on parental leave I'm not sure how frequently I will be able to create these posts.