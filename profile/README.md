## Projects

[English](https://github.com/VOKA-AI/.github/blob/main/profile/README.md)

[中文](https://github.com/VOKA-AI/.github/blob/main/profile/README_CN.md)

### THE EDEN

![TheEdenBack](https://github.com/VOKA-AI/.github/blob/main/assets/TheEdenBack.png)

THE Eden is a decentralized live streaming platform for web3.0. 
which focusing on decentralized games and AMA interviews on ETH and Polygon network. 

The project will provide 3D NFT avatar generating technology from 2D PFP NFT by using our AI algorithm, and be able to live stream with the 3D avatars. 

Different from previous live broadcasts, The Eden creates the opportunity for interaction between viewers and anchors in the same space through Metaverse space scenes. 

GameFi providers and AMA KOLs can open their own DAO to promo their own channel within the platform.

Media data delivery of the platform was based on IPFS. The process is as follows:

1. Creator makes videos, and sends them to our server over socket.io.
2. The server uploads data to IPFS network.
3. Subscribers get stream data hash from server
4. Subscribers use data hash to get live stream from IPFS.

Our servers run both IPFS and our service, responsible for uploading data to IPFS, reponsing to the request of stream data hash from subscribers, as well as identifying authentication.

The advantages of IPFS based media delivery system are as follows:
1. Suitable to Web3, has the advantages of Web3
2. Save bandwidth cost.
3. Secure（content based）
4. Cannot be controlled by one authority figure or government
5. Scalibility and availability

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

