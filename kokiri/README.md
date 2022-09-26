# Kokiri

### Description

Objective:

Kokiri is Hubble Lab's demo application with a custom machine learning model to estimate the amount of carbon present in the soil found within a geospatial image provided and requested through Iris our Decentralized Terrestrial Satellite Oracle Network (DtsON).

Implementation:

Kokiri will consist of an Electron.js desktop web app and a python-based backend. A scientific review of all papers pertaining to Soil Organic Carbon estimation indicate the most used and robust ML model for this task is a Random Forest Regressor based model. We will therefore be using a Random Forest Regressor for Kokiri. As for the satellite imagery, we currently have free-tier access to Planet Lab's catalog which includes all of California. To simply things for the demo we will be choosing UC Berkeley's "Glade" as our Area of Interest to extract carbon data from. Becauses I live right next to campus, I can take soil samples to perform spectroscopy and get ground truth carbon data to then train our model with. It is very likely that we will require multiple ground samples to create a model that performs well with any data. If that turns out to be the case we will find more areas nearby to take ground samples from. 

Applications:

Using a better trained ML model, Hubble Labs can then build what we call a Data Distlling DON (ddDON). ddDONs are DONs that take complicated data types that smart contracts can't easily interact with, like an image, and extract or distill simpler and more specific information from them. Kokiri's technology could therefore be extended to build a Soil Organic Carbon ddDON. It would perform similarly to Iris in that it would recieve a request for data, the network would find random nodes to report the data back to a leader node, the leader node would compare the results and return the average. With a ddDON as described previously, HL would be able to build the world's first truly decentralized carbon tokenization dapp and marketplace. 


### Team Members & Roles

- Salvador Salcedo, Founder, Lead Developer

- Connor Moore, Oracle and Smart Contract Developer

- Evan Robert, Enviromental Science and ML Engineer


### Hackathon Track

- Re/Defi


### Project Details

- Demo Video _(*Phase 2 & 3, Required)_

- Requirements _(*Phase 2 & 3, Required)_

- Instructions to build and test _(*Phase 2 & 3, Required)_
