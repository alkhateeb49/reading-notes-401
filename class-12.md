# Class 12

* ## Related data in Spring <br/>
The entities handle the relation between tables as a relationship. When you handle a relationship with an entity, the reference to another entity is stored as a field in the entity. In addition, set the following relationship annotations in the persistence property or instance variable that references an entity:<br/>
- - OneToOne (One-to-one)
- - OneToMany (One-to-many)
- - ManyToOne (Many-To-One)
- - ManyToMany (Many-To-Many)<br/><br/>

If the relationship annotation is not specified for referencing the entity, the operations will not function properly. Note that if the generic type is not used in the reference where collection is used, the target entity must be specified as the relationship target.<br/>
Instead of using an annotation, you can also define a relationship using the O/R mapping file. However, note that when a relationship is defined in the O/R mapping file and if the same definition is specified in the annotation, the definition in the annotation is overwritten.<br/>


---

* ## Baeldung: Spring Integration Testing <br/>
INTEGRATION TESTING is a level of software testing where individual units / components are combined and tested as a group. The purpose of this level of testing is to expose faults in the interaction between integrated units. Test drivers and test stubs are used to assist in Integration Testing.<br/>
During the process of manufacturing a ballpoint pen, the cap, the body, the tail and clip, the ink cartridge and the ballpoint are produced separately and unit tested separately. When two or more units are ready, they are assembled and Integration Testing is performed. For example, whether the cap fits into the body or not.<br/>
### System Integration Testing<br/>
This type of integration testing focuses on the interactions and interfaces between systems (A system is a group of interacting or interrelated entities that form a unified whole). The other system that needs to be integrated with can either be internal or external (developed by someone else over which the organization has no control). Such systems are normally exposed via an Application Programming Interface (API) or a Microservice.<br/>

---