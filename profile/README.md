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

1. Creator makes videos, and sends them to our server over [socket.io](https://github.com/socketio/socket.io).
2. The server uploads data to IPFS network.
3. Subscribers get stream data hash from server.
4. Subscribers use data hash to get live stream from IPFS.

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
The generated avatar can be used as secondary creation NFT, and can also be used in live streaming as AR mask.

<div align="center">
  <img src=https://github.com/VOKA-AI/.github/blob/main/assets/ARMask1.png width="300"/><img src=https://github.com/VOKA-AI/.github/blob/main/assets/ARMask2.png width="300"/>
</div>

Lack of usage scenarios is a bottleneck that restricts the development of NFT.
Using NFT to generate avatar, used in live streaming and other fields like video chat with friends can promote the development of NFT.

As a Web3.0 platform, ***The Eden*** will issue its owen tokens.

## Mission

In the world of Web2.0, live-streaming has become the popular entertainment activity for daily life.
With the advent of the era of Web3.0, current live-streaming platforms cannot meet the needs of Web3.0 users. 
In the world of Web3.0, people tend to be anonymous or use network identity, so decentralized identity (DID) will become an essential part of Web3.0. 
However, all live-streaming platforms cannot use DID at present. 
With the development of Metaverse and AI, the technology of multiplayer interaction will be implemented. 
Compared with the traditional live-streaming communication, the new type of broadcasting like cloud gaming is not only easy to get the audiences and the KOLs closer, 
but also create the opportunity for the second social networking between audiences. 
Therefore, our goal is to build a Web3.0 exclusive Live-Streaming service platform.

## Service


## Related Repos
* [video-streaming website front-end](https://github.com/VOKA-AI/live-web)
* [video-streaming website back-end](https://github.com/VOKA-AI/live-backend)
* [3D avatar AR Mask](https://github.com/VOKA-AI/react-face-mask)
* [3D avatar generating AI](https://github.com/VOKA-AI/3DAvatarGenerator)
* [3D avatar generating website](https://github.com/VOKA-AI/AIAvatarGenerator)
* [smart contracts](https://github.com/VOKA-AI/VokaAIProtocol)

