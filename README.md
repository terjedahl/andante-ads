
<img src="https://ads.andante.no/static/media/Andante_ads_logo.png" width=300 alt="Andante Ads">

<hr>

**_An ad network for the 21st century_**


## Description

A multi-sided platform for online advertisements.  

Advertisers quickly and easily defines ads with target audiences, 
sets bid limits and budgets, 
and makes deposits on-chain from which settlement is drawn.

Publishers define spots and target audiences, sets minimum prices, 
and are automatically payed after 24 hours on-chain.

Audiences are not tracked, and no attempt is made to recognize users or behavior across sites.
No cookies are used.  Any data collected from clicks is purposefully anonymized maximally, 
limited only by need to ascertain uniqueness of user.   

Settlement is per click, not per impression.  This incentivizes publishers to optimise ad placement and promotion to maximize profit. 
It simultaneously disincentivizes "ad-stuffing" and other deceptive practices.

Advertisers are only charged for one click per audience member per ad per spot.  IP and other parameters are stored per click to be able to identify it as a unique first time click or not. 
Best attempts are made to prevent "click fraud", while at the same time ensuring maximal settlement to publishers, e.g. multiple unique audience users behind a shared IP. 

Settlement happens on-chain, and are therefore easily verifiable by both advertisers and publishers. 
Settlements are anonymized by using dedicated IDs on-chain, only known to the owner of that ID. 
Currently _**80%**_ of all charges are transferred directly from advertisers to publishers.

Settlements are batched and processed at least once per day, but with a 24 hour delay. 
The delay gives advertisers (and publishers) time to contest a charges. Contestation will be processed manually.

Ad and spot performance logs are made visible to both advertisers and publishers, allowing both sides to study results and optimize accordingly.

The _bidding algorithm_ is public, and bidding logs will also be made visible to both parties!  
In short:  New ads (without enough performance history) will be subject to "first-price" bidding. 
Once enough performance history has accumulated for a given ad, it will be transitioned to "CRT-weighted second-price" bidding.

Ads will always be embedded in a dedicated frame. This will ensure that no malicious code can access anything on a loaded page outside of the ads frame.  

Different formats and content types will be developed in cooperation with both advertisers and publishers. 
Currently the two main types are "banner" and "sidebar" - the first short and wide for displaying at top of page or between paragraphs - the second taller and narrow for displaying on left or right side of page. 

The ads' base content (HTML) will be hosted and served from Andante Ads, while embedded media (such as images and video) may be served from elsewhere.
The base content may be submitted as simple lines of text or a mix of markdown and HTML.  


## Milestones

- Basic landing page. _Done_.
- Sign-in with crypto wallet (Metamask). _Done_.
- Account selection/creation once signed in.  _Done(2024-07-01)._
- Add creation, definition and formats, audiences, bid, budget.
- Spot creation - format and embedding, audiences, bid.
- Bidding mechanism.
- Accounting mechanism.
- Settlement mechanims.
- Blockhain settlement contract and integration.
- Testing.
- Q&A for advertisers, publishers, and audiences.
- Launch.


## Misc

Andante Ads is currently featured on [Backdrop Build](https://backdropbuild.com/builds/v5/andante-ads).

