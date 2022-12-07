## Projects

[English](https://github.com/VOKA-AI/.github/blob/main/profile/README.md)

[中文](https://github.com/VOKA-AI/.github/blob/main/profile/README_CN.md)

### THE EDEN

<div align="center">
<img src=https://github.com/VOKA-AI/.github/blob/main/assets/TheEdenBack.png width=80% />
</div>

THE Eden is a decentralized live streaming platform for web3.0. 
which focusing on decentralized games and AMA interviews on ETH and Polygon network. 

The project will provide 3D NFT avatar generating technology from 2D PFP NFT by using [our AI algorithm](https://github.com/VOKA-AI/3DAvatarGenerator), and be able to live stream with the 3D avatars. 
Different from previous live broadcasts, The Eden creates the opportunity for interaction between viewers and anchors in the same space through Metaverse space scenes. 
GameFi providers and AMA KOLs can open their own DAO to promo their own channel within the platform.

<div align="center">
  <img src=https://github.com/VOKA-AI/.github/blob/edit/assets/architecture.jpg width=80% align="center"/>
</div>

 

Media data delivery of the platform was based on [IPFS](https://ipfs.tech/). The process is as follows:

1. Creator makes videos, and sends them to our server over [socket.io](https://github.com/socketio/socket.io).
2. The server uploads data to IPFS network.
3. Subscribers get stream data hash from server.
4. Subscribers use data hash to get live stream from IPFS.

Our servers run both IPFS and our service, responsible for uploading data quickly to IPFS, reponsing to the request of data hash from subscribers, as well as identifying authentication.

<div align="center">
  <img src=https://github.com/VOKA-AI/.github/blob/edit/assets/network.jpg width=80% align="center"/>
</div>

The advantages of IPFS based media delivery system are as follows:
1. Suitable to Web3, has the advantages of web3.0.
2. Higher availability and scalibility.
3. Save bandwidth cost.
4. Cannot be controlled by one authority or government.
5. More secure.

#### Mission

In the world of Web2.0, live-streaming has become the popular entertainment activity for daily life.
With the advent of the era of Web3.0, current live-streaming platforms cannot meet the needs of Web3.0 users. 
In the world of Web3.0, people tend to be anonymous or use network identity, so decentralized identity (DID) will become an essential part of Web3.0. 
However, all live-streaming platforms cannot use DID at present. 
With the development of Metaverse and AI, the technology of multiplayer interaction will be implemented. 
Compared with the traditional live-streaming communication, the new type of broadcasting like cloud gaming is not only easy to get the audiences and the KOLs closer, 
but also create the opportunity for the second social networking between audiences. 
Therefore, our goal is to build a Web3.0 exclusive Live-Streaming service platform.

#### Features
NFT AI Avatar Generator 
Using VOKA AI technology to build up 3D avatar for live-streaming from 2D NFT.
Distributed Live Broadcast Service Center
Through the decentralized internal data center to provide live-streaming rendering, storage, video-on-demand 
Multi-Platforms
The Eden will support IOS, Android and Web platforms.

#### Service

#### Related Repos
* [video-streaming website front-end]()
* [video-streaming website back-end]()
* [3D avatar AR Mask]()
* [3D avatar generating AI]()
* [3D avatar generating website]()
* [smart contracts]()

