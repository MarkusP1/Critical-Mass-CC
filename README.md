# Critical-Mass-CC

## Work and Project Examples
  ### Project 1: [Undercover: Jimmy Bond](https://drive.google.com/drive/folders/1rKIa_9TUR32OVxwM6uH_3rgQRAr7WhP1?usp=sharing)
  We developed this immersive 3D stealth-shooter game as a team of two for the Applied AI in Games course taken in the Fall 2021 semester. The project was built in Unreal Engine (UE) using Blueprints and C++ and well as Photoshop, Blender and some additional visual libraries. The workload was shared equally where my focus was primarily on the development of the AI systems involved as well as some level design and flow. 
  
  I implemented two systems, the first being a pathfinding AI with obstacle avoidance and the second a proximity/line-of-sight detection algorithm. The pathfinding alogrithm was a tweaked version of grid-based A* that was designed from the ground-up without the use of pre-existing UE functions. This was applied to all the NPCs in the game to provide realism to the gameplay.
  
  The sight-detection algorithm was also applied to the NPCs and was built using the field-of-view and distance vectors available. The idea here was to allow NPC civilians to "see" when you had a weapon out, and cause you to lose if you remained in their view for a given peroid of time that was distance dependent (closer = faster).
  
  I also had a shared role in the creation of the levels visually, including the themes and construction of the levels themselves. Additionally, I contributed to minor gameplay components such as sounds and custom voice-lines which were done in multiple languages.
  
  ### Project 2: [EcoMaps](https://github.com/MarkusP1/CalgaryHacks2022)
  EcoMaps was developed during CalgaryHacks2022 as part of a 24hr coding challenge that took place in late February. It was built using React and used Google and Bing APIs for geocoding and distance/route data. 
  
  My primary role in this project was on reasearch into emissions data as well as initial design ideas and implementation of the scores and donut graphs.
  The data was primarly from readily available emissions and fuel consumption data from Natural Resources Canada which was then broken down into three main vehicle types. I also used ridership data from the City of Calgary to understand emissions/person during transit. 
 
 I then used the data to calculate the "EcoScore" which was our way of displaying which method of transportation was the most sustainable and realistic. (ie, walking to Vancouver is most sustainable but not feasable!).
  This score was then dispalyed on the donut graphs which I thought allowed for easy visual comparison especially with the color indication.
  
  ### Project 3: [Bandwagon](https://github.com/MarkusP1/Bandwagon)
  Bandwagon is a multi-user, web-based application built as a team of three using a React front-end and a SQLite database with a .NET backend API. Users can create accounts and vote on NBA games to pick up points and badges as well as redeem points for items in the store.
  
  My role in this project was primarily on the front-end development of multiple pages as well as the development of our prediction algorithm and database population.
  For page design, I was specifically focused on the games, badges and profile pages which were initally designed on paper. For the games page I took inspiration from [fivethirtyeight](https://fivethirtyeight.com/) to create clean and visually appealing components. 
  
  The prediction algorithm was created using an an amalgamation of pre-existing techniques alongside trial and error and some basic learning/comparison in python.
  
  Lastly, I was involved in populating our database with as much NBA stats and data that was readily available. This was done through some statistics APIs available online as well as a very minor amount of manual entry.


## Inspiration
I've picked these three recent examples as they have all inspired me in different ways.

 ### [Brittany Chiang](https://github.com/bchiang7)
  Brittany Chiang's repo was shown to me by a professor while we were discussing project ideas. 
  
  What inspired me was the design and experience of her spotify app and personal website. She was able to cleanly convey information in a visually appealing way that was simple and easy to follow.
  ### ML Avalanche Prediction [Repository](https://github.com/SBeairsto/Avalanche_project) and [App](https://avalanche.shinyapps.io/seatosky/?fbclid=IwAR3DoIDe5qAXSPFprox-04GYM2GWhihwrptnqdl-4tnjpH2XwAIUwnkWeHw)
  
  ### Kurzgesagt: [Site](https://kurzgesagt.org/) and [Youtube](https://www.youtube.com/channel/UCsXVk37bltHxD1rDPwtNM8Q)

## Focus
