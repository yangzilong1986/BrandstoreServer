<p align="center">
  <img src="https://raw.githubusercontent.com/srinathwarrier/BrandstoreApp/master/app/src/main/res/drawable-xxhdpi/brandstorelogoicon.png" alt="Brandstore"/>
</p>

<p align="center">
    <img src="http://img.shields.io/badge/license-MIT-lightgrey.svg?style=flat" alt="License: MIT" /> <br><br>
</p>

## Introduction.
Brandstore is a One-stop-shop for Mall related activites.
Primary features include :

#

1. Catalog of all the Stores in a mall
2. Details of type of products available in each store
3. Take me there - Text-based Indoor mall navigation

#

The Brandstore project was started as a Startup and was launched for testing in one of the largest Malls in India. The primary goal was for the user to be able to search for any product in the mall [Apparel, footwear, accessories and many more categories] in a detailed approach yet with a simple UI. The goal was to index the whole mall and make it searchable for the User. Following the lean approach, we took to testing within a few months with a working application. But after multiple rounds of testing and re-iteration, we realized that the product was not scalable enough to be a Successful startup. There simply wasn't a "10X problem" to target. However, our text-based "Take me there" functionality was highly in demand by multiple vendors. So, we are open sourcing the product as a whole for Other developers to contribute and use.

The UI Front end is an Android app, while the server was a Nodejs setup (using Sails) running on an EC2 instance. 

This project is the source code for the Brandstore NodeJS Server application. 

The Android app code is also available [here] (https://github.com/srinathwarrier/BrandstoreApp) 
You can find the app on [Google Play] (https://play.google.com/store/apps/details?id=com.brandstore1)

### Architecture

The server uses the following Technologies : 

1. [Nodejs] (https://nodejs.org) for the Core server stack
2. [Express JS] (https://expressjs.com/) (node framework) for the REST Calls 
3. [Sails JS] (http://sailsjs.org/) (node framework) for the Server MVC architecure. (Both Waterline ORM and Blueprint API have been used)
4. MySQL as the Database
5. [Node-mysql] (https://www.npmjs.com/package/node-mysql) as the plugin to connect to Mysql databases

The Models (generated by Sails) used in this Server are : 

* Brand 
* BrandType 
* Collection 
* CollectionOutletAssignment 
* FloorZone 
* Hub 
* HubTransit 
* HubType 
* Location 
* Offer 
* Outlet 
* Product 
* ProductTag 
* StaticAveragePrices 
* Tag 
* TagHierarchy 
* TagType 
* User 
* UserFavorite 
* UserInteraction

### ⚠️ Requirements

* Requires to be downloaded and then run on a local node.
* Not available on npm yet. [WIP]

### 🔑 License
Brandstore is released and distributed under the terms and conditions of the [MIT License](https://github.com/srinathwarrier/BrandstoreServer/blob/master/LICENSE.md).

### 👥 Contributions
If you run into problems, please open up an issue. We also actively welcome pull requests. By contributing to Brandstore you agree that your contributions will be licensed under its MIT license.

If you use Brandstore or any of its code in your app we would love to hear about it! Drop me a [mail](warriersrinath@gmail.com).

### 📗 Documentation
Brandstore server code is yet to be documented completely. [WIP]

### 💻 Authors
A shoutout to the original contributors of the project before we published it on Github.

Co-founders : Srinath Warrier, Diwakar Gandhi

Developers : Ravi Sanker, Sonika , Summeet Bhalla, Gargi Barania.

### ❓ Support or Contact
Having trouble with Brandstore? Drop me a [mail](warriersrinath@gmail.com).