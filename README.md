# marketPlaceTechGig
It includes techgig code for marketplace block chain

# Delivery files and component
 It include all the nodes(Total 8 nodes- 6 for dairy companies, and 1 each for farmer/gov and vets ) network files, its crypto material, channel files.
#Inlusion 
It includes a project for installing and instantiate chaincode on a blockchain network.
It includes a java war project for running the middleware application, which connect the frontend application to a  blockchian network, ideally we create 1 each of this java appliction for 8 nodes to get them connected to their respective blockchain network node.
It includes the initial drafted chaincode file for all the process taking place in the marketplace scenario. 


#To start the blockchian network

:Note- Ensure to have prerequisite completed for hyperledger fabric
1)copy the marketplace_solution content in a folder on linux server 
2) docker-compose up -d (in side the folder, pasted above) => For peers to come up
3) ./channelCreateJoin.sh => for peers to join respective channel

Network is up now

#Install and Instantiate chaincode

4) From the Java project(MarketPlaceInfra). Inside the package "org.hyperledger.fabric.mp", there are 11 files to install and instantiate the chaincode
on 3 different channel. It will install chaincode on the nodes according to the channel they have joined.
