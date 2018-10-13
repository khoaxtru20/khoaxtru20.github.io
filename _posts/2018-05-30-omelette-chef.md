---
layout: post
title:  "Omelette Chef, The Game"
date:   2018-05-30
tags: [northwestern, unity, cinema 4d, game, design]
---

### The Project
In this first-person, high-stakes cooking game, you are a chef focused on making one thing: omelettes. Keep the customers happy by completing their orders accurately and promptly. Make too many mistakes, and you're out of the kitchen!

### Process
This started as a ten-week game project for a class and I took it through an additional eight-weeks of tuning to help Ivy complete it as a capstone project. We initially wanted to make a game for VR, but with our time constraints, we focused our efforts on creating a 3D version that could easily be converted into a VR game. Inspired by games like Overcooked, Cooking Mama, and Diner Dash, we utilized our recent musings of game and user design theories to create a fun, engaging, and narratively unique game that explored the affordances and limitations of interactive media.

### Results
<div style="position:relative;height:0;padding-bottom:56.25%; margin-bottom:2%;"><iframe src="https://www.youtube.com/embed/8Mh3MZShoEs?ecver=2" width="640" height="360" frameborder="0" style="position:absolute;width:100%;height:100%;left:0" allowfullscreen></iframe></div>

### Takeaways
On the back end, Keith and I ran into this obstacle which was designing the structure for the multitude of interactions that would take place in this game. We played with Unity's OnTrigger(), OnCollision(), methods, but maintenance was an issue when scaled. We ultimately decided on using a dictionary to hold the interactions. This meant we were having to pass around static objects, which instinctually felt inefficient, but it was decent enough for our prototype. If we were to continue with this game, I would like some feedback and suggestions on managing the interactions.

On the front end, Ivy and I felt our way through the importing process of 3D objects from Maya to Unity. We had never done it before, but we learned a couple of lessons. The following information is directed to anybody curious about art design for games.

First, don't worry too much about scale of an object when creating it, or rather, focus on the detail, and subsequently the scale of the object needed to produce the intended detail; Unity can further manipulate the scale of an object once imported. Second, remove all unnecessary points and polygons before exporting from Maya. Along with this point, be sure to clearly name your objects! Third, be wary of where the origin lives in your object; this will become the pivot point of the object in Unity, which may or may not be important depending on what you need the object for. Lastly, if you have repeated objects with different colors, only import one version of each unique object. For the different colors and shades, import as materials.

This was a fun project to make and to collaborate on. Thanks to Keith Kravis and Ivy Gao for their contributions to this game, and to Dr. Ozge Samanci and Dr. Robert Zubeck for their feedback and guidance.
