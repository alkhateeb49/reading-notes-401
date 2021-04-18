# Class 11

* ## Spring guide: Accessing Data with JPA<br/>
This article will focus on introducing Spring Data JPA into a Spring project and fully configuring the persistence layer. For a step by step introduction about setting up the Spring context using Java-based configuration and the basic Maven pom for the project, see this article.<br/>
As we discussed in an earlier article, the DAO layer usually consists of a lot of boilerplate code that can and should be simplified. The advantages of such a simplification are many: a decrease in the number of artifacts that we need to define and maintain, consistency of data access patterns and consistency of configuration.<br/>
Spring Data takes this simplification one step forward and makes it possible to remove the DAO implementations entirely. The interface of the DAO is now the only artifact that we need to explicitly define.<br/>

---

* ## Baeldung: Comparing repositories<br/>

You can compare repositories and create patch files using the comparerpd utility.

This feature is especially useful when you want to compare repositories or generate patches on Linux and UNIX systems where the Administration Tool is not available. The compare utility is available on both Windows and UNIX systems.

When you run the comparerpd utility, the system also equalizes the repository objects. The equalizing process outputs the my_current_rpd_equalized.rpd file, an informational file containing the output of the equalization done between the compared repositories. Equalizing ensures that objects with the same qualified names have the same unique identifiers (UIDs). Objects with the same name but different UIDs are automatically updated to use the same UID (or equalized). Including when equalization is not needed, the my_current_rpd_equalized.rpd file is generated. The my_current_rpd_equalized.rpd file is saved to the original repository's location.
You can specify an output CSV file using -O, an XML patch file using -D, or an MDS XML directory tree using -M. You cannot specify more than one output type at the same time.

If the patch contains passwords, such as connection pool passwords, the patch file is encrypted using the repository password from the current repository. The current repository password effectively becomes the patch file password. You might need to supply this patch file password when applying the patch, if it is different from the repository password for the original repository.

---