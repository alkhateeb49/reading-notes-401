# Class 16

* ## Many to many relationships <br/>
A many-to-many relationship occurs when multiple records in a table are associated with multiple records in another table. For example, a many-to-many relationship exists between customers and products: customers can purchase various products, and products can be purchased by many customers.<br/>

Relational database systems usually don't allow you to implement a direct many-to-many relationship between two tables. Consider the example of keeping track of invoices. If there were many invoices with the same invoice number and one of your customers inquired about that invoice number, you wouldn't know which number they were referring to. This is one reason for assigning a unique value to each invoice.<br/>

To avoid this problem, you can break the many-to-many relationship into two one-to-many relationships by using a third table, called a join table. Each record in a join table includes a match field that contains the value of the primary keys of the two tables it joins. (In the join table, these match fields are foreign keys.) These foreign key fields are populated with data as records in the join table are created from either table it joins.<br/>

A typical example of a many-to many relationship is one between students and classes. A student can register for many classes, and a class can include many students.<br/>

The following example includes a Students table, which contains a record for each student, and a Classes table, which contains a record for each class. A join table, Enrollments, creates two one-to-many relationships—one between each of the two tables.<br/>

![Image](img/relation.png)

---
