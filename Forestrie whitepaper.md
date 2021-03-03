# Forestrie whitepaper

## Vision
An Open Public Assets Catalogue would allow to permanently store, categorize, search and uniquely identify any asset. Such catalogue would provide an infrastructure for many existing use cases' needs and enable a huge variety of applications to be developed, i.e., ownership tracking, marketplaces, marketing platforms, supply chain tracking solutions, intellectual property coining, and many more. This is the next step in the globalization and decentralization evolution.

We are working on a protocol that aims to make it a reality.
Our goal is to develop a global assets catalogue protocol, that uses economical incentives to encorage humanity to enrich the catalogue with anything they find useful. Assets catalogue records are immutable, but records ownership as an asset, is transferable.

It must be public and provide free access for developers to develop, using this catalogue, the wide range of use cases and applications mentioned above.

It must be decentalised and community governed, to forever remain neutral and unbiased. 

It must be an open sourced, democratic, community based project, since it is built for people, by the people (versus for "users", by corporations).

It aims to serve as public memory.

## Abstract
The protocol provides the algorithm for the creation of a catalogue as a directed graph in a blockchain network infrastructure, new blocks validation and creation mechanics and the interface for usage. It introduces a revenue distribution model that incentivizes contributions to the catalogue, by treating each attribute block as a financial asset that can be bought with the **WATER** token and yield income for the contributors.

Each block represents a) a unique word - an **attribute**; or b) any unique partially ordered set of other, existing as blocks, attributes - a ***poset***, which groups the attributes into meaningful descriptions. 
Creation of a block is attempted by **seeding** and **watering** it by the Seeder. The **Planters** are responsible on validating this block is legite and finding the Earliest Longuest match to which this block will be connected.  Successful seeding results in a **planted** block. 

Each planted block can be used in planting any new block, i.e., the same block with the attribute *blue* can be used in the “iPhone 12 *blue*” block, as well as in the “The *blue* book” block. *iPhone 12 Blue* block can be used in planting *iPhone 12 Blue 256GB*.

Each time a block was used in successful planting it will reward the block owner, the ***Seeder***, with a relative fraction of a WATER token. Any successful seeding will recursively reward all used attributes’ Seeders and pay for the "gas" to finance the network operators and validators – the Planters.

Any attempt of *seeding* will cost the attribute owner *Water*, whether it was planted successfully or not. Seeding might not succeed in case it did not pass validations, i.e. uniqueness validation, or insufficient funds. *Water* ***rooted*** in unsuccessful seeding, will reward the Planters only. This will also act as the first layer of defense against attacks and spam.    

Each *planted* block potentially can ***root a tree***, therefore there are no leaves possible, since any asset, potentially, can be specified more, by being connected to additional attributes, indefinitely.


