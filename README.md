# Eco Scan
Simplifying recycling for a better tomorrow, **today**.
## Inspiration and the Birth of a Solution
### The Problem
A simple question **"Can I recycle this item?"** may not always have such a simple answer. According to a survey conducted by [Paper+Packaging](https://www.paperandpackaging.org/sites/default/files/2021-09/New%20Survey%20Reveals%20Gaps%20in%20Consumer%20Recycling%20Behavior%20and%20Knowledge%20-%20For%20Immediate%20Release_1.pdf) shows that about 50% of the Americans who recycle do not know the appropriate recycling technique.
This may cause confusion in appropriate recycling, and people may just forego recycling entirely and instead throw their items in the trash. This can cause severe detrimental impacts on the already strained resources of our planet, by further increasing waste pollution. This can start a vicious cycle bringing a doom.
### A New Hope
To combat this problem we bring our solution **EcoScan**. We wanted to harness the disruptive potential of _Generative AI_ technology, and the human desire for achievement to incentivize society as a whole to maximize their recycling. The best part about this is that our project can be used on any device with a camera. Coupled with Google's built-in accessibility features for web apps like read text aloud, or auto-translate, it makes it useful for allowing marginalized groups who do not know English to know the latest tips and tricks in recycling as well.

## What it does
The concept is simple _(as it should be)_. A user navigates to the [EcoScan](https://eco-scan.tech/) (currently taken down due to it not being proofed against attacks) website and creates an account. After creating the account, the user can scan any item and the web app will provide detailed recycling instructions on that item. Moreover, it provides an incentive by scoring the user's recycling efforts. The app currently assumes that if you scan it then you recycle it, and increases the points which the user has. These points are assigned based on the **environmental degradation** that would be caused if the product were to not be recycled. 

To incentivize the community we have a **leaderboard** which keeps track of the total points and displays the top 5 in the community. _Gamifying_ the application in this way adds further incentive to contribute to the good cause.

## How we built it
This web app was built using the Flask framework, Firebase for the backend database and authorization along with javascript for handling real time function calls to the object detection and recycling machine learning model API. The website is hosted on firebase hosting while the https API's are current hosted on python anywhere.
## How it works
This flowchart demonstrated how the web app functions:
![image](https://github.com/user-attachments/assets/f75977f5-9494-4732-9781-15c338f35f29)

## Challenges we ran into
1) Integrating Python and Javascript calls with Flask.
2) Gamifying the web app so that it incentivizes. Dealing with firebase backend was a new experience for all of us so it was challenging to accomplish that.
## Accomplishments that we're proud of
We honestly did not think we could create a full stack project within the time span of 24 hours but we made it work. The feeling is underscribable
This project also contributes to the [UN Sustainability development goals](https://sdgs.un.org/goals) which creates a sense of pride in furthering our common development goals.
## What we learned
This project really pushed our tech knowledge beyond our limits. All of us learnt new tech stacks and furthered our knowledge of API calls and web hosting. 

## What's next for EcoScan
In the future, we can improve Eco Scan's _gamification_ and possibly add more incentives than being the best recycler (we still believe that being the best recycler **is** the best incentive).
Enhance **User Experience** by showing the recycling image and trash image.
