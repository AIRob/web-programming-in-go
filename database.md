# Databases 

While there are some limitations, database/sql provides a good baseline interface for drivers, and has seen improvements in Go 1.8. Go has many pure go database drivers for popular databases, so you don't need to be limtied in your choice. 

## Which database should you use?



### NoSQL

There are certain clearly defined uses where a NoSQL database makes sense. 


There are many databases available, if you are looking for a relational database (and you should be, unless you have very specific requirements), Postgresql is reliable, performant and has a lot of features which rival NoSQL ones. If you do only require document data, consider starting with a pure Go key/value store like BoltDB, but be wary of unknowingly and over time building half a relational database without the ACID constraints within your app.

If you're already familiar with a database however, and want to get up and running quickly, just use that one - most mainstream databases now have good support in Go. 





## Connecting to the Database






## References 

* PSQL driver 
* MYSQL DRiver 