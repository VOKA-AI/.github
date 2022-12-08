[English](https://github.com/VOKA-AI/.github/blob/main/profile/README.md)

[中文](https://github.com/VOKA-AI/.github/blob/main/profile/README_CN.md)

## Introduction

<div align="center">
<img src=https://github.com/VOKA-AI/.github/blob/main/assets/TheEdenBack.png width=80% />
</div>

***The Eden*** is a decentralized live streaming platform for Web3.0. 
which focusing on decentralized games and AMA interviews on [ETH](https://ethereum.org/en/) and Polygon network. 

The project will provide 3D NFT avatar generating technology from 2D PFP NFT by using [our AI algorithm](https://github.com/VOKA-AI/3DAvatarGenerator), and be able to live stream with the 3D avatars. 
Different from previous live broadcasts, The Eden creates the opportunity for interaction between viewers and anchors in the same space through Metaverse space scenes. 
GameFi providers and AMA KOLs can open their own DAO to promo their own channel within the platform.

<div align="center">
  <img src=https://github.com/VOKA-AI/.github/blob/main/assets/architecture.jpg width=80% align="center"/>
  <p>Architecture</p>
</div>

 

Media data delivery of the platform was based on [IPFS](https://ipfs.tech/). The process is as follows:
<div align="center">
  <img src=https://github.com/VOKA-AI/.github/blob/edit2/assets/process.jpg width=80% align="center"/>
  <p>process</p>
</div>

1. KOLs makes videos on the client, including fetching NFT picture from blockchain, generate 3D avatar, and used as face mask, then send them to ***The Eden*** server over [socket.io](https://github.com/socketio/socket.io).
2. ***The Eden*** server will do some pre-processing, such as encoding, then uploading it to IPFS network.
3. Audiences using client to interact with ***The Eden***, geting data hash from server, combine with *smart contract*, audiences can pay to subscribe, send virtual gifts to KOLs.
4. Audiences use data hash to get live stream from IPFS.

Our servers run both IPFS and our service, responsible for uploading data quickly to IPFS, reponsing to the request of data hash from subscribers, as well as identifying authentication.

<div align="center">
  <img src=https://github.com/VOKA-AI/.github/blob/main/assets/network.jpg width=80% align="center"/>
  <p>Media delivery network</p>
</div>

The advantages of IPFS based media delivery system are as follows:
1. Suitable to Web3.0, has the advantages of Web3.0.
2. Higher availability and scalibility.
3. Save bandwidth cost.
4. Cannot be controlled by one authority or government.
5. More secure.


As mentioned above, ***The Eden*** provide 3D avatar generation services, 
which can generate 3D models from 2D NFT pictures. 
The generated avatar can be used as secondary creation NFT, and can also be used in live streaming as [AR mask](https://github.com/VOKA-AI/react-face-mask).

<div align="center">
  <img src=https://github.com/VOKA-AI/.github/blob/main/assets/ARMask1.png width="300"/><img src=https://github.com/VOKA-AI/.github/blob/main/assets/ARMask2.png width="300"/>
</div>


https://user-images.githubusercontent.com/19359257/206367690-ee1ba05c-1a6b-4a89-84a2-1aa091141a09.mov


Lack of usage scenarios is a bottleneck that restricts the development of NFT.
Using NFT to generate avatar, used in live streaming and other fields like video chat with friends can promote the development of NFT.

As a Web3.0 platform, ***The Eden*** will issue its own tokens.


## Business Model & Token Related

### Business Model

<div align="center">
  <img src=https://user-images.githubusercontent.com/20713531/206183113-14125208-6b75-44a5-9c35-2ad1a97f7cbb.jpg width=80% align="center"/>
  <p>Business Model</p>
</div>

### How to Participate

#### Audience Mode (**Watch to Earn**)
In Audience Mode, users are required with NFT face mask to earn tokens by watching broadcast. Each NFT has Activity Level. The Activity Level will affect the Everyday EDC Production (EEP). The EEP is the Estimated Number according to the Trend of the previous 5 days EPPs. 

In order to level up the NFT, users have some method to gain Activity:

1.	Chancel Daily Subscribe: Spend EDC to subscribe KOL channel to earn 1 Activity.
2.	Gift Purchase: Purchase gift or donation for KOL. Spend 1 EDC to get 1 Activity.
3.	Daily Online Rewards: 20 mins online activity will gain 1 Activity. Higher Level has longer Daily Reward Duration. 
4.	Register Invitation: Every 1 New Register to gain 3 Activities. 
5.	EDT – EDC Swap: Exchanged EDT to EDC. Get every 1 EDC to gain 1 Activity.  

<div align="center">
  <img src=https://user-images.githubusercontent.com/20713531/206182941-ab894eb3-d38c-4bb1-8dcc-317e1eedbf83.png width=80% align="center"/>
  <p>The Level of NFT 3D face mask has different factors</p>
</div>


#### KOL Mode (**Live-Streaming to Earn**)
Every user can be a KOL and own an exclusive channel. KOL Channel can be purchased by EDT, which is similar as the Land NFT of GameFi. Every Channel has exclusive IPFS storage and Live Room. 

IPFS storage will store the “Wonderful Moment” of broadcast content. 

The Live Room has capacity of audience. KOL can self-purchase or crowdfunding from subscribers to upgrade the Live Room. The subscribers will have multiple speed to increase the EDC Production. (Pending)


#### Miner Mode (**Skating Mining**)

Miners will contribute the assets for IPFS live-streaming service. In term, they will get EDT as return. (Pending)


### Tokenomics and the usage of Token

#### EDT: Governance Token

1.	EDC to EDT Swap Transaction Fee
2.	Channel Purchase and Live Room Upgrade (Land NFT purchase)
3.	3D PFP Face Mask Purchase
4.	Airdrop NFT Mint
5.	Governance Voting

#### EDC: Platform Token

1.	Gift Purchase and Donation
2.	Channel Daily Subscribe
3.	EDT to EDC Swap Transaction Fee


## Mission

In the world of Web2.0, live-streaming has become the popular entertainment activity for daily life.
With the advent of the era of Web3.0, current live-streaming platforms cannot meet the needs of Web3.0 users. 
In the world of Web3.0, people tend to be anonymous or use network identity, so decentralized identity (DID) will become an essential part of Web3.0. 
However, all live-streaming platforms cannot use DID at present. 
With the development of Metaverse and AI, the technology of multiplayer interaction will be implemented. 
Compared with the traditional live-streaming communication, the new type of broadcasting like cloud gaming is not only easy to get the audiences and the KOLs closer, 
but also create the opportunity for the second social networking between audiences. 
Therefore, our goal is to build a Web3.0 exclusive Live-Streaming service platform.

## Features

* Decentralized live-streaming
* User data self-owned
* Dual Tokenomic
* Multi-Platform

## Service

* AMA Interview.
* GameFi Boardcasting.
* Crypto/Defi Eduction.
* VTuber and other Entertainments.

## Related Repos
* [video-streaming website front-end](https://github.com/VOKA-AI/live-web)
* [video-streaming website back-end](https://github.com/VOKA-AI/live-backend)
* [3D avatar AR Mask](https://github.com/VOKA-AI/react-face-mask)
* [3D avatar generating AI](https://github.com/VOKA-AI/3DAvatarGenerator)
* [3D avatar generating website](https://github.com/VOKA-AI/AIAvatarGenerator)
* [smart contracts](https://github.com/VOKA-AI/VokaAIProtocol)

