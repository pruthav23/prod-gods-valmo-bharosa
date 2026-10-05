# Valmo Bharosa – RTO Reduction Prototypes

**Team Prod Gods · IIT Kanpur · Meesho DICE Challenge**

RTO (return-to-origin) parcels are orders that reach the customer but come back undelivered, costing the seller and Meesho twice. Valmo Bharosa attacks RTO with three working prototypes.

## 👉 Live landing page

**https://pruthav23.github.io/prod-gods-valmo-bharosa/**

One page, three buttons, one per prototype.

## Prototypes

| Prototype | What it does | Live link |
|---|---|---|
| **Valmo Pakka** | Checks the order is genuine and the buyer is ready, before dispatch | https://valmo-pakka.streamlit.app/ |
| **Valmo Pata** | Converts messy addresses into precise DIGIPIN locations for first-attempt delivery | https://valmo-pata.streamlit.app/ |
| **Valmo Wapas Nahi** | Resells refused parcels to nearby buyers instead of shipping them back | https://prodgods-rto-demo.onrender.com/present |

## Source code

Each prototype has its own repository:

| Prototype | Source code |
|---|---|
| **Valmo Pakka** | https://github.com/mansis23/valmo-pakka |
| **Valmo Pata** | https://github.com/pruthav23/valmo-pata |
| **Valmo Wapas Nahi** | https://github.com/basudevm23/dice-s3-proto |

## Note for reviewers

The apps are on free hosting and sleep when idle. The **first load can take 30–60 seconds**. On Streamlit, click *"Yes, get this app back up"* if shown.

## Running the landing page locally

It is a single static file. Open `index.html` in any browser. No build step.

## Team

Prod Gods – Basudev Mohapatra ([@basudevm23](https://github.com/basudevm23)), Mansi Shyam Ghoodke ([@mansis23](https://github.com/mansis23)), Prutha Vinay ([@pruthav23](https://github.com/mansis23))
