
a.What is the purpose of this application, where is the data it uses pulled from, and what application features are important for someone looking at the code to understand?

The purpose of this application is to all a user to search for a book using the google books API

b.	What are some good ways to us passwords, keys, etc. in your applications while preventing them from being accessed by the outside world?

This application could be converted to a virtual bookshelf. This would allow users to create password protected accounts and in which they can add their own books.

c.	Your favorite SQL database includes tables called properties and addresses.- The properties table has one record per property, and has 2,000 records in it.- The properties table has one column only: prop_id.- The addresses table has one record per property, per year, and has 500,000 records in it.- The addresses table has three columns: prop_id, address, and year.- The year column is comprised of integer values for each year (2010, 2011, and so on)What is a SQL query that will pull all of the prop_id’s and current (2019) addresses for any property in the addresses table, along with a column denoting whether that property exists in the properties table?

SELECT address FROM addresses WHERE addresses.year = int(2019) AND prop_id.addresses = prop_id.property

d. What are some cases for or against containerization of internally-used micro-applications?

The pros of containerization of internally-used micro-applications is:

1) Allows to run program in various environments as everything is self contained.
2) Its quick to load and start up
3) Testing your application is easier as their is little difference in the production environment.

The cons of containerization of internally-used micro-applications is:

1) Security issues can arise because the application share the same OS. If the kernel is exploited then this can comprise the entire app.
2) Can consume large amounts of computer resources.
3) The configuration for networking can become complicated.
