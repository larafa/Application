# Database
## Amazon RDS: Simplif.ai's database solution

Simplif.ai uses Amazon RDS to store data about users, such as:
* email address
* notes
* summaries
* social network accounts

Our database communicates with the backend to store data when necessary, as well as retrieve information for the backend when it is requested. The class structures for our data in RDS can be found in the design document.


Note: In order to keep Amazon RDS inside the free tier, we will use less than 20GB of storage.

More information regarding the setup and use of the RDS can be found here: https://aws.amazon.com/getting-started/tutorials/create-mysql-db/
