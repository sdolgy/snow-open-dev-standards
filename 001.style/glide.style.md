Glide Style Guide
=================

Introduction
------------
Something...


External References
-------------------
[Glide Stack: Service Now](http://wiki.service-now.com/index.php?title=Glide_Stack)


Process all records from a specified table
------------------------------------------

``` js

var tableName = "incident";
var target = new GlideRecord(tableName);
target.query();   // Issue the query to the database to get all records
while (target.next()) {   
  // add code here to process the incident record
}

```