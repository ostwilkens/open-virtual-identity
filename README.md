# Open Virtual Identity
_An open standard for personal virtual identities and all they entail_

## The problem
Every video game, social platform or other internet community that allow the end user to create a virtual avatar all have widely differing functionality, and, worst of all, they don't talk to each other. This means the user needs to create a new avatar on every new service they come across. Changes or achievements made on one service don't carry over to others. 

## The solution
Build a system where the user can set up their avatar once, and use it on any one platform that chooses to support it. Avatar visuals, virtual item ownership and other properties are always up-to-date on all platforms. 

## Goal of the project
The hope is to have a future where the following scenario could play out:
> Kim is playing the new hit MMO, _Wicked Wizard Party_. 
> Kim defeats a powerful wizard, receiving a _Wizard Hat_ as a reward. Kim equips the _Wizard Hat_, which grants +5 intellect, making Kims' spells more powerful. 

> Kim later logs in on the social meetup platform, _VRChitChat_. Kims' avatar dons the Wizard Hat in this world as well. As there are no RPG elements to VRChitChat, the +5 intellect bonus has no effect. 

> Before bed, Kim wants to play some _Angry Battle Soldiers_ on the living room games console. Before going into battle, Kim switches out the _Wizard Hat_ for a _Protective Helmet_. While intellect does slightly improve Control Point capping speed in this game, Kim decides the bonus armor of the _Protective Helmet_ is more beneficial. 

The "metaverse" future is inevitable, and it will hopefully be:

* Open source
* (Mainly) decentralized
* Owned by noone
* Easy to implement for developers

# Technology
_Everything below is a work in progress_

## Interacting entities

* Item creator/admin
* Ownership provider
* End user
  * Content consumer and owner of virtual identity

## Required functionality

* Item ownership
  * _Item creator/admin_ decides which _Ownership provider_ can prove item ownership
  * Item quantity is retrieved from all _Ownership providers_ on request
* Currency
  * Currencies are just items with a 'currency' type
* User properties

* Item visuals (3d models? 2d sprites?)
  * items can have 3d models tied to them
  * item descriptions (main color: blue)
  * standards for visuals
  * ? tools for generating models
  * ? tools for enforcing/applying the standards to existing 3d models (poly count reduction, retopo)

tags: metaverse, snow crash
