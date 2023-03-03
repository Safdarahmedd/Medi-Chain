# Medi-Chain
This project is a Decentralised Application built on the Ethereum Blockchain to store Electronic Medical Records in a standardized and secure format. 
It uses IPFS protocol to provide hashes for these records, which acts as a unique address for the smart contract upon which a GET request can be sent 
for reading the record. Patients can grant access to their records to medical practitioners and manage access rights with a private key. 
After diagnosis, non-identifiable information about the patient's illness is streamed to a data warehouse hosted in Google cloud’s Big query which uses 
this data for real-time disease tracking and long term analytics that can determine health trends in the country. This data is visualised with the help of Tableau.

![home](https://user-images.githubusercontent.com/59877986/222836468-9c405cc8-2d04-4448-bfeb-2cfd92d4b1fb.jpg)


## Installation

The projects requires NodeJS and npm to work. Instructions to install all other dependencies are given below.
#### Node modules

1. Move to the project directory and open it in your terminal.
2. Run `npm install` to install project dependenccties.

#### Ganache

1. Go to [Ganache homepage](https://truffleframework.com/ganache) and download. 
2. If you are on Linux, you must have received an _.appimage_ file. Follow installation instructions available [here.](https://itsfoss.com/use-appimage-linux/)

#### IPFS

1. Go to the [github page](https://github.com/ipfs/ipfs-desktop) of IPFS and install IPFS Desktop

#### Local server

1. Install Node lite-server by running the following command on your terminal `npm install -g lite-server`

#### Metamask

1. Metamask is a browser extension available for Google Chrome, Mozilla Firefox and Brave Browser.
2. Go to the this [link](http://metamask.io/) and add Metamask to your browser.

### UI
![access](https://user-images.githubusercontent.com/59877986/222836474-4aea4099-aa16-4ea2-844d-98c2e7987e9b.jpg)

### Google Big Query schema
![schema](https://user-images.githubusercontent.com/59877986/222836840-79791c0c-550a-480b-a018-b1eb23123eaf.jpg)

### Tableau Dashboard
![tableau](https://user-images.githubusercontent.com/59877986/222836483-f3f8f337-3122-4e6e-82c6-44111b90f579.jpg)
