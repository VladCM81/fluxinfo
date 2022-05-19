
# Introduction

To make a long story short, I discovered the world of crypto-currency not long ago with a lot of interest for the Flux project.
I decided in March 2022 to set up a Cumulus node at the time of Flux halving.
On Flux official Discord channel, I often saw the question "*after how many days will I obtain my reward?*". As this information evolves with each new node added to the Flux network, I decided to create a basic webpage where this dynamic information could be found. It has evolved a lot since then, see the [webpage evolution](https://github.com/VladCM81/fluxinfo#webpage-evolution) for more information.

Please note that **I am not a web developer at all**. I only do this for fun in my spare time and to help others from Flux community. I have no particular skills in development and have adopted a kind of "*learn by doing*" method. I know that the website is not perfect at all and that there are things to improve, correct and optimize.

# Flux Nodes Info webpage

The webpage intent is to provide Flux community useful real-time information related to the Flux nodes.

Here is a non-exhaustive list of the main features:
- Show the number of active nodes per tier (Cumulus, Nimbus and Stratus)
- Calculate the delay between each payout depending on the number of nodes
- Calculate the rewards (incl. PA) per node as well as the monthly profit
- Show the node rank and expected next payout in days, hour and minutes
- Simulate the monthly profit based on the number of owned nodes and VPS cost, if any.

# Webpage evolution

It started in March 2022 with a very basic webpage with few very information:

<img width="320" alt="FluxInfo_2022-03-20" src="https://user-images.githubusercontent.com/102852122/167937453-064e686b-eb40-4c8b-b08a-13c144ad59a0.png">

I then tried to give the website a nice look using free HTML/CSS template that I customized. This is what it looked like initially.

<img width="550" alt="FluxInfo_2022-03-21" src="https://user-images.githubusercontent.com/102852122/167937583-a3013206-a7db-492f-a313-32658de7ef4f.png">

I wanted to be able to know exactly when I would get my next reward for my Cumulus node, so I added a feature to retrieve the rank (based p, the node IP address) to determine when the next reward would arrive.

<img width="400" alt="FluxInfo_2022-03-31" src="https://user-images.githubusercontent.com/102852122/167937685-81907e43-e6fa-4cb1-9c6b-e1241cc38a02.png">

Early in April, I gave the site a new look because several community members had asked me for a dark mode. Having encountered difficulties to switch from one mode to the other, I decided to leave only the dark mode on the website. New features had also been added such as the Flux halving migration progress for each tier.

<img width="600" alt="FluxInfo_2022-04-02" src="https://user-images.githubusercontent.com/102852122/167937753-a89634d0-c34c-42e8-8133-728851c7c61d.png">

The idea then came to me to add sliders to simulate nodes ownerships so we could know how much Flux could be earned and how much profit could be made based depending on hosting costs (if any).

<img width="600" alt="FluxInfo_2022-04-10" src="https://user-images.githubusercontent.com/102852122/167937841-7539573b-7b67-4c7b-b0be-b99647226699.png">

I then added a section with the total monthly profit for those lucky enough to manage several different tier Flux nodes.

<img width="600" alt="FluxInfo_2022-04-21" src="https://user-images.githubusercontent.com/102852122/167937926-b11c5692-1f23-49d8-85b7-cb863292899c.png">

Lastly, I added radio buttons to switch prices on the website for 3 currencies (USD, EUR and GBP). I also rebuilt the website from scratch with only HTML, CSS and JS and I removed all the PHP code that was used before for initial calculation. The VPS cost sliders have also been replaced by input textbox.

<img width="300" alt="FluxInfo_2022-05-06" src="https://user-images.githubusercontent.com/102852122/167937988-62eafd64-4464-4a62-8ed6-0209bb74a86a.png">

## Roadmap (or todolist)

- Give an option to enter both IP or Flux walletID for node rank info section
- Create a feature that would determine which tier nodes to install based on a Flux collateral volume
- Add button to refresh data fetching, calculation and node ranking
- Add a light/dark mode toggle
- Add others data and graphs usefull for the Flux community
- Feel free to suggest things you would like to see implemented

## Tech Stack

**Server hosting:** It runs on Flux!

**Website:** HTML, CSS and Javascript

## Useful Links

- RunOnFlux : https://runonflux.io/
- Flux API documentation: https://docs.runonflux.io/
- HTML5 UP : https://html5up.net/

## Contact and support me

You can reach out to me on [Twitter](https://twitter.com/VladCM81) and on [Discord](https://discord.io/runonflux) (in the Flux official channel).

If you appreciate my work, you can support me with few Flux sent to the following wallet address: t1eLxWdsBEwbMW611HBuEQJHwR1nCet4ojr
