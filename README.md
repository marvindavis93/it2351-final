# it2351-final


Excutive Summary

 There are 7 tables in MarvinGuitarShop database. 6 tables are connected using one to many relationships. Administrators table is not part of the ERR. That table is used to store usernames and passwords that will be used to authenticate user who tries to access this database. Since we have direct access to database we don’t have to authenticate, but I database is used as backend of some web site, it would be used.
Address table stores full add like state, city, zip, street and house number. It has foreign key customer id as well. The reason address is moved as separate table because some customers may have more than one addressees.  If address fields were in the customer table, we could not deal with customers having two addresses.
Order item helps to join order and product tables, since order and product tables have may to many relationships by logic. One customer may order several products; one products can be ordered by serval customers. 












Database Adminstration 

There is address of customer, but still in order table there are two address ids for shipping and billing. And they are not connected to address table meaning that they may have non existing address ids. If order table anyway contains address id, then we should remove customer id from address table and connect address and order tables for address id.

In order table all card information are given, I would create another table called Card and move all card information like card number, type, expiration to that table and connect order and card tables using card id field. We can use card number as primary key since it is unique.

I would create a trigger that throws exception if list price of product updated to lower price only. If it is updated to higher price, no exception will be thrown and it updates the price.  
 




MySQL CERTS


diploma itself is the most important credential that we can use to find a job. Especially if diploma is specialized in database fields. But to increase the chance of being hired in respective companies, one can take certificates. Now owner of MySQL is Oracle. Oracle has a big reputation. That’s why taking database expert certificate from Oracle increases the probability of finding a good job place.
There two types of certifications for MySQL:
•	Database Administration
•	Database Developer
I am interested in Database Administration certification ad alternative one is programmers who use MySQL.
Oracle has its own training as well, but it is not necessary, if we have devotion and patience, we can learn ourselves just using the internet resources in addition to resources and topics covered in this class.
MySQL Database Administration certification has two types: Professional and Specialist. I think it is very good try to take the certification. First of all, while preparing we learn a lot and preparation itself makes us the master. Next once we receive, it will increase our chance to find the very good job. Third, we use that knowledge while preparing in the job. That’s why certification is not just a paper, it has only huge benefits.


