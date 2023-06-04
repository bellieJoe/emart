# Installation

Welcome to the installation guide for the Emart application! This guide will walk you through the steps required to install Emart on your preferred device. With the Emart application installed, you'll have access to a seamless and convenient shopping experience right at your fingertips. Whether you're using a smartphone, tablet, or computer, this guide will provide you with the necessary instructions to get Emart up and running quickly. So let's dive in and get started with the installation process to unlock a world of exciting shopping possibilities with Emart!

## Acquiring the project source code

The project source code is included on the official CD of Emart. If you do not have a CD, please approach the developers for a secure copy of the source code.

## Tools and Dependencies

To install the Emart website locally on your computer you need the following tools installed:

1. Xampp - https://www.apachefriends.org/download.html
2. Any browser eg.(Google, Microsoft Edge, Firefox) to access the system.

## Configuring the Xampp server

To setup Emart on Xampp server please follow the steps below:

1. Open the Xampp directory folder `C:\\xampp`.
2. Open `htdocs` folder.
3. Copy the `e-mart` folder from the zip file of the CD to the `htdocs` folder of Xampp.
4. After that open the Xampp application and start the Apache and MySQL like this. <img src="/assets/images/xampp-start.png" width="500">
5. Open your browser and enter the `localhost/phpmyadmin` url which look like this. <img src="/assets/images/phpmyadmin.png" >
6. On the sidebar of phpmyadmin panel click the `new` button to create a new database and name it `db_emart`.
7. After creating the `db_emart` database click the `import` <img src="/assets/images/phpmyadmin-import-btn.png" width="100">  button on the top navigation of phpmyadmin then click `Choose File` <img src="/assets/images/phpmyadmin-choosefile.png" width="100"> button and select the .sql file for the Emart included on the CD.
8. After that click the `Go` button and wait while installing the database.
9. After Installing the database open another tab on the browser and enter `localhost/e-mart` to access the site which look like this. 
<br><center><img src="/assets/images/emart_landing.png" width="500"></center>


