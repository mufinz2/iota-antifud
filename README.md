*Last updated: December 22, 2017

Please also read this. Very good FAQ! 

https://www.reddit.com/r/CryptoCurrency/comments/7jnsap/iota_and_tangle_discussioninfo_scam_or_not/

**Purpose of Writing**

Since posting FUD is so ridiculously low-effort in comparison to setting the record straight, I felt it necessary to put a log of copy-pastas together to balance the scales so its just as easy to answer the FUD as it was to generate it. So next time you hear someone say "IOTA is centralized" you no longer have to take an hour out of your day to set the record straight. You just copy-paste away and move on. 

It's also worth mentioning IOTA devs are too damn busy working on the protocol and doing their job to answer FUD. So I felt a semblance of responsibility.

Here they are. These answers are too my understanding so if you see something that doesn't look right let me know! They are divided into the following categories so if you are interested in a specific aspect of IOTA you can scroll to that section.

1) WALLET

2) COMMUNITY

3) INVESTING

4) TECHNICAL

**************

# WALLET

## How to generate wallet and seed

Download official wallet [here](https://github.com/iotaledger/wallet/releases)

1) only use the sidebar generators to create your seed. Also generate it while not connected to the internet, preferably in an air gapped device that never has nor will connect to the internet. But, if you don’t trust generators at all you can also make your seed by drawing a 9x9 matrix on paper (81 char seed) and roll [dice](https://imgur.com/a/vnq5L) for the values in each cell.

2) if you send from an address, trash that address and never use it again. You can receive to an address as many times as you want but once you send from it you gotta move to a new address. The desktop wallet does this automatically so no need to worry about doing it yourself.

3) when a snapshot occurs, you have to download the latest wallet version and hit attach to tangle until your balance shows up. You won’t lose your iota if you don’t do this but people often post their balance is zero after a snapshot and all they have to do is hit attach to tangle a few times.

That’s it. That’s all there is to the wallet commotion. Really not that hard imo but with so many new users it appears we’re getting into situations where the blind is leading the blind.

## Are you sure a computer can’t just guess my seed?

An IOTA seed is 81 characters long. There are more IOTA seed combinations than atoms in the universe. All the computers in the world combined would take millions of years just to find your randomly generated one that’s located somewhere between the 0th and the 27^81st combination. The chance for someone to randomly generate the exact same seed as yours is 1 / (27^81). 

If you can’t fathom the number 27 ^ 81, this video should help:

https://www.youtube.com/watch?v=p8YIdmwcubc

## Wallet pending transactions

First try promoting the transaction again through the transaction bundle. Promoting is only available in the wallet version 2.5.5 or later.

In the wallet, go to edit node configuration > custom and type in a node from the list below. All the public nodes listed by default on the wallet are overused. Read the FAQ linked at the top to get more details on pending transactions and whats going on. 

https://iota.dance/nodes

Or punch in your bundle hash in either of the re-attach websites below and they will reattach it for you. You can get your bundle hash via the transaction hash [here](https://thetangle.org/): 

http://www.reattach.online/

or this one

https://reattach.iotalpha.io/

## Why is UCL wallet taking so long!!??

It will release when it’s ready. Most folks are going to be transferring their iota to it so they are making damn sure it’s bullet proof. We don’t need a [parity](https://www.theregister.co.uk/2017/11/16/parity_flaw_not_fixed/) situation to happen to iota.

**************

# COMMUNITY

## IOTA introduction video to share with family

https://youtu.be/LyC04NrJ3yA

## Tangle visualizers


http://tangle.glumb.de/

http://iota.dance/live/

http://live.iotaknot.com/

## Here’s a guide to setup a full node

https://forum.helloiota.com/1191/Setting-Up-a-Full-Node-A-Comprehensive-Guide

and Nelson for automatic neighbor discovery: https://github.com/SemkoDev/nelson.cli

"If you want to help the network then spam the network. If you **really** want to help the network then create a full node and let others spam you!" 

## No questions or concerns get upvoted, only downvoted!

That’s just the nature of this business. Everyone in these communities has money at stake and are extremely incentivized to keep only positive news at the top of the front page. There is nothing you're going to do about that on this subreddit or any crypto subreddit. It's just a reddit fact of life we have to deal with. Everyone has a downvote and everyone has an upvote. But what can be done is just simply answer the questions even if they are downvoted to hell. Yea most people wont' see the answers or discussion but that one person will. every little bit counts.

I will say that there are most certainly answers to nearly every FUD topic out there. Every single one. A lot of the posts I'm seeing as of late especially since the price spike are rehashed from months ago. They are often not answered not because there isn't an answer/explanation, but because regulars who have the answers simply don't see them (for the reason listed above). I can see how it's easy for this to be interpreted (especially by new users) as there not being an answer or "the FUDsters are on to something" but thats just not the case.

## Developer's candidness

https://i.redd.it/qb0ik4tgny401.jpg

## IOTA Devs do not respond appropriately to criticism

When critiquers provide feedback that is ACTUALLY useful to the devs, then sure they'll be glad to hear it. So far not once has an outside dev brought up something that the IOTA devs found useful. Every single time it ends up being something that was already taken into consideration with the design and if the critiquer did an ounce of research they would know that. Thus you often find the IOTA devs dismissing their opinion as FUD and responding with hostility because all their critique is really doing is sending the message to their supporters that they are not supposed to like IOTA anymore.

Nick Johnson was a perfect example of this. The Ethereum community was co-existing [peacefully](http://www.reddit.com/r/ethereum/comments/6qm0y2/is_the_ethereum_team_defending_their_ground/dkyrdzv) with IOTA’s community (as they do with nearly all alt coins) until Nick wrote his infamous article. Then almost overnight Ethereum decided it didn’t like IOTA anymore and we’ve been dealing with that shit since. As of today, add LTC to that list with Charlie’s (even admitting) ignorant judgement of IOTA.

12/17/2017: Add [John McAfee (bitcoin cash)](https://i.redd.it/rsizfpeyq5401.png) and [Peter Todd (bitcoin)](https://twitter.com/petertoddbtc/status/942206322023587840) to the list of public figures who have posted ignorantly on IOTA. 

## Dev's said something on slack!

Slack is a place for casual banter. It's intent is not for every message to be screenshotted and broadcasted all over the internet. If you interpret something on slack seriously and end up dissapointed, that isn't the fault of the devs.

## Announcement of announcements:

You only get in trouble with this practice if you "overhype" something or are too cryptic and let your community's imaginations run wild. I will say the last time the IOTA dev's hyped something, the data market place was announced so their track record is pretty good and they have enough common sense to know what will be big and what won't. But it only takes one mishap to sour the tone so its a thin line to walk.

## A lot of crypto communities certainly like to hate on IOTA...

IOTA is disrupting the disrupters. It invented a completely new distributed ledger infrastructure (the tangle) that solved all of the fundamental problems with blockchains (namely fees & scaling). A LOT of capital crypto projects are blockchains and will become obsolete if IOTA succeeds. These projects have billions of dollars invested into them meaning everyone in their communities are incentivized to see IOTA fail and spread as much FUD about it as possible. This includes well known organizations, public figures, and brands. Everyone commenting in these subreddits and crypto communities have their own personal money at stake and skin in the game. Misinformation campaigns, paid reddit posters, upvote/downvote bots, and corrupt moderators are all very real in this space.  



**************

# INVESTING

## How do I buy IOTA

https://medium.com/@fuo213/how-to-buy-iota-the-complete-guide-for-crypto-dummies-e63560caf921

## What is the IOTA foundation?

IOTA foundation is a non-profit established in Germany and recognized by the European Union. Blog post here: https://blog.iota.org/iota-foundation-fb61937c9a7e

## How many companies and organizations are interested, partnered or actively using IOTA?

A lot, and often too many to keep up with. Pergamum was awesome enough to compile a list with sources.

http://www.reddit.com/r/Iota/comments/7j2jpp/summary_iota_partners_corporate_interests_and/

## How was IOTA distributed?

All IOTAs that will ever exist were sold at the ICO in 2015. There was no % reserved for development. Devs had to buy in with their personal money. Community donated back 5% of all IOTA so the IOTA foundation could be setup.

## No inflation schedule? No additional coins? How is this sustainable?

Interestingly enough, IOTA is actually the only crypto that does not run into any problems with a currency cap and deflationaryism. Because there are zero fees, you will always be able to pay for something for exactly what it's worth using IOTA, no matter how small the value. If by chance in the future a single iota grows so large in value that it no longer allows someone to pay for something in fractions of a penny, the foundation would just add decimal points allowing for a tenth or a hundreth or a thousandth of an iota to be transacted with.

## Companies technically don’t have to use the IOTA token

[Yes they do](https://i.redd.it/t6gmplq0c2tz.jpg)

Worth clarifying that 0 iota data transactions are perfectly fine and are welcomed since they still provide pow for 2 other transactions and help secure the network. In the early stages, these types of transactions will probably be what give us the tps/pow needed to remove the coordinator and allow the network defend 34% attacks organically.

But... if someone does not want to sell or exchange their data for free (0 IOTA transaction), then Dominic is saying that the IOTA token must be used for that or any exchange in value on the network.

This is inherently healthy for the ecosystem since it provides a neutral and non-profit middle ground that all parties/companies can trust. If one company made their own token it wouldn’t be trusted since companies are incentivized by profits and nothing is stopping them from manipulating their token to make them more money. Thus, the IOTA foundation will not partner with anyone who refuses to take this option off the table.

## Microsoft fake?

Microsoft is in fact real: see David's response here: https://www.reddit.com/r/Iota/comments/7inys6/does_anyone_have_information_on_why_microsoft/dr05u5u/

And this article covering the whole situation: https://www.psychologytoday.com/blog/mind-in-the-machine/201712/how-fear-is-being-used-manipulate-cryptocurrency-markets

IOTA formal blog post: https://blog.iota.org/iotas-data-marketplace-setting-the-record-straight-576fbf0b4513

## All these companies are going to influence IOTA development!!

Microsoft has no influence on the development of IOTA. They either choose to use it or they don’t. Same goes for Bosch, Innogy, Fujitsu, Schneider electric etc etc.

## Internet of things is cheap and will stay cheap

Internet of things is one application of IOTA and considered by many to be the 4th industrial revolution. Go do some googling. IOTA having zero fees enables M2M for the first time in history. Also, if a crypto can do M2M it sure as shit can do M2P and P2P. M2M is hard mode.

## IOTA surpassing speculation

IOTA, through the data marketplace, will be the first crypto to surpass speculation and actually be used in the real world for something. From there, it will branch out into other use cases, such as P2P. Or maybe P2P use of IOTA will grow in parallel with M2M, because why not?

https://blog.iota.org/iota-data-marketplace-cb6be463ac7f

Might I add with its infinite scaling, IOTA is the ONLY crypto that has the capability to replace fiat at the moment.

12/19/17 update: Bosch reinforces IOTA's break-out from speculation by buying IOTA tokens for its future use in the data marketplace. 
https://i.redd.it/8e5b8bi9ov401.png

http://www.bosch-presse.de/pressportal/de/en/robert-bosch-venture-capital-makes-first-investment-in-distributed-ledger-technology-137411.html

## Investing in a new project barely off the ground

Investing in a project in its early stages was something typically reserved for wealthy individuals/organizations before ICO’s became a thing. With early investing comes much less hand holding and more responsibility on the user to know what they are doing. If you have a hard time accepting this responsibility, don’t invest and wait for the technology to get easier for you. How many people actually knew how to use and mine bitcoin in 2009 before it had all its gui infrastructure?

IOTA is a tangle, the first of its kind. NOT a copy paste blockchain. As a result wallets  and applications for IOTA are the first of their kind and translating the tangle into a nice clean user-friendly blockchain experience for the masses is even more taxing. It was built for machines after all. 

## Why is the price of my coin falling?!

This may be the most asked question on any crypto subreddit but it's also the easiest to explain. The price typically falls when bad things happen to a coin or media fabricates bad news about a coin and a portion of investors take it seriously. The price increases when good things happen to a coin, such as a new exchange listing or a partnership announced etc.. The one piece that is often forgotten but trumps all these effects is something called "market forces".

Market forces is what happens to your coin when another coin gets a big news hit or a group of other coins get big news hits together. For example, when IOTA data marketplace released, IOTA hit a x5 bull run in a single week. But did you notice all the other alt coins in the red? There are a LOT of traders that are looking at the space as a whole and looking to get in on ANY bull action and will sell their other coins to do so. This effect can also be compounded over a long period of time such as what we witnessed when the bitcoin fork FOMO was going on and alt coins were squeezed continuously to feed it for weeks/months.

These examples really just scratch the surface of market forces but the big takeaway is that your coin or any coin will most certainly fall (or rise) in price at the result of what other coins are doing, even if your coin hasn't done anything. If you don't want to play the market-force game or don't have time for it, then you can never go wrong buying and holding.

It's also important to note that there are layers of investors. There's a top layer of light-stepping investors that are a mixture of day traders and gamblers trying to jump in and jump out to make quick money then look for the next buying opportunity at another coin. There's a middle layer of buyers and holders who did their research, believe in the tech and placing their bets it will win out in the long run. And the bottom layer are the founders and devs that are in it till the bitter end and there to see the vision realized. When a coin goes on a bull run, always expect that any day the top layer is going to pack up and leave to the next coin. But the long game is all about that middle layer. That is the layer that will be giving the bear markets their price-drop resistance. That is why the meme "HODL" is so effective because it very elegantly simplifies this whole concept for the common joe and makes them a part of that middle layer regardless if they understand whats going on or not.

*************

# TECHNICAL

## How is IOTA free and how does it scale

IOTA is an altruistic system. Proof of work is done in IOTA just like bitcoin. Only a user’s device/phone must do pow for 2 other transactions before issuing one of its own. Therefore no miners and no fees. And the network becomes faster the more transactions are posted. Because of this, spamming the network is encouraged since they provide pow for 2 other transactions and speed up the network.

## IOTA is centralized

IOTA is more decentralized than any blockchain crypto that relies on 5 pools of [miners](https://www.buybitcoinworldwide.com/mining/china/), all largely based in China. Furthermore, coordinator isn’t a central server all transactions pass through, contrary to popular misconception. It is just normal actor who adds transactions to the tangle, which other nodes can use as milestones, if they wish. It’s a shepherd, you could say, which the herd can follow so they don’t go astray (following some malicious nodes or whatnot). The Monte Carlo Random Walk algorithm is what will create consensus in the herd when there is no shepherd any more. It will be comparable to every sheep calling out while also following the sound of the call of the rest of the herd. That way they can all tangle up together.

Referencing the coordinator is also [optional](https://www.reddit.com/r/Iota/comments/7717ms/at_what_point_will_iota_remove_the_validator/).

Also, if you research and understand how IOTA intends to work without the coordinator, it’s easier to accept it for now as training wheels. I suggest reading pg 15 and on of the white paper analyzing in great depth how the network will defend different attack scenarios without a coordinator. For the past several months, IOTA foundation has been using St Petersburg college’s super computer to stress test IOTA and learn when they can turn the coordinator off. There will likely be a blog about the results soon.

This is another great read covering double spends on IOTA without a coordinator: www.tangleblog.com/2017/07/10/is-double-spending-possible-with-iota/

This too: http://www.reddit.com/r/Iota/comments/7eix4a/any_iota_guru_that_can_explain_what_this_guy_is/dq5ijrm

Also this correspondence with Vitalik and Come_from_Beyond https://twitter.com/DavidSonstebo/status/932510087301779456

At the end of the day, outstanding claims require outstanding evidence and folks approaching IOTA with a “I’ll believe it when I see it” attitude is completely understandable. It’s all about your risk tolerance.

## Can IOTA defend double spend attacks?

99% of these “but did they think about double spend attacks?” type questions could just be answered if people went and did their own research. Yes *of course* they thought about that. That’s like crypto101…

www.tangleblog.com/2017/07/10/is-double-spending-possible-with-iota/

## Will IOTA have smart contracts?

We believe so and plenty of rumors fly around about this. For now this is all we know: 
https://twitter.com/iotatoken/status/894301083689943040

## Trinary vs binary?

"By using a ternary number system, the amount of devices and cycles can be reduced significantly. In contrast to two-state devices, multistate devices provide better radix economy with the option for further scaling"

https://www.nature.com/articles/srep36652

https://www.reddit.com/r/CryptoCurrency/comments/6jgbvb/iota_isnt_it_the_perfect_cryptocurrency/dje8os2/

## Bitcoin with lightning network will make IOTA obsolete.

If you want lightning network, IOTA already released it. Called flash channels.

https://blog.iota.org/instant-feeless-flash-channels-88572d9a4385

## IOTA rolled its own crypto!

This is why: https://blog.iota.org/the-transparency-compendium-26aa5bb8e260

[Cybercrypt](https://blog.iota.org/iota-foundation-hires-cybercrypt-615d2df79001) has been hired to review and audit it. IOTA is currently running SHA-3/KECCAK now until Curl is ready. 

## MIT said bad things about IOTA

https://blog.iota.org/curl-disclosure-beyond-the-headline-1814048d08ef

https://medium.com/@comefrombeyond/cfbs-comments-on-https-www-media-mit-edu-posts-iota-response-5834c7f8172d

## Nick Johnson says IOTA is bad!

Nick Johnson is an ethereum dev who is incentivized to see IOTA fail, see CFBs twitter responses here.

https://mobile.twitter.com/nicksdjohnson/status/912676954184323073?lang=en

And this

https://t.co/1HgfPhg2lP

And this

https://www.reddit.com/r/Iota/comments/72lly0/comment/dnjk9f5?st=JB2VKUBB&amp;amp;amp;amp;amp;amp;sh=a2892548

## IOTA is not private!

Masked authenticated messages exist right now so data can be transferred privately. Very important for businesses.

## Coin privacy

Centralized coin mixer is out that foundation runs. Logs are kept so they can collect data and improve it Folks can copy the coin mixer code and run it themselves. Goal is for mixer to be decentralized and ran by any node.

## How do nodes scale? How on earth can all that data be stored?

Full nodes store, update and verify from the last snapshot, which happens roughly every month. Its on the roadmap to make snapshotting automatic and up to each full node’s discretion.With automatic snapshots, each full node will act as a partial perma-node and choose when to snapshot its tangle data. If someone wants to keep their tangle data for several months or even years, they could just choose not to snapshot. Or if they are limited on hard drive space, they could snapshot every week.

Perma-nodes would store the entire history of the tangle from the genesis. These are optional and would likely only be created by companies who wish to sell historical access of the tangle as a service or companies who heavily use the tangle for their own data and want to have quick, convenient access to their data’s history.

Swarm nodes are also in development which will ease the burden on full nodes. https://blog.iota.org/iota-development-roadmap-74741f37ed01

## Node discovery is manual? Wtf?

Nelson ~~is fixing~~ has fixed this: 

https://medium.com/deviota/carriota-nelson-automatic-peer-discovery-for-iota-bdca9b8b8750

https://medium.com/deviota/carriota-nelson-in-a-nutshell-1ee5317d8f19

https://github.com/SemkoDev/nelson.cli

## What does Nelson mean for us?

It means that all the full nodes the community has been setting up are now going to properly play their role in contributing to the network. So far most of the network has been throttled through the 14 plus odd public nodes shown in the wallet. These nodes are very juicy targets for attackers. Now the network will be properly distributed amongst thousands of full nodes.

https://medium.com/deviota/carriota-nelson-automatic-peer-discovery-for-iota-bdca9b8b8750

>We need to continue the progress on CarrIOTA, but I think, this small side-project is worth the time. It will (hopefully) increase the amount of full nodes and explode the size of the network in a short amount of time.

Also if you want to setup your own full node here’s a guide, the hardware requirements are very small.

https://forum.helloiota.com/1191/Setting-Up-a-Full-Node-A-Comprehensive-Guide

Nelson is now public, github is here: 

https://github.com/SemkoDev/nelson.cli

## IOTA open source?

IOTA protocol is open source. The coordinator is closed source. The coordinator will be open source in December, 2017. Dom confirmed in AMA here: https://answers.thenextweb.com/s/dominik-schiener-and-david-sonstebo-d0XXq0

https://imgur.com/a/xWQUp

****************

## My IOTA donation address:

*9PZFQNPLVDUNGAOYYMMXFWMGNPMNAJWZKTYOOMCYQTZQA9RPVVN9SE9KGOL9HWZFJBXKQGEOY9JJYDXB9TY9FLQPXB*






