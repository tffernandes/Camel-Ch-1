# Chapter 1 - File Copy Example

This example is copying files from data/inbox to data/outbox directory.

It was modified from the original example and now it is a ready-to-go Eclipse project.

## Running

### To run the example via command

    mvn compile exec:java -Dexec.mainClass=camelinaction.FileCopierWithCamel
    
When the example is done, then you can see that the file has been copied from `data/inbox/message1.xml` to `data/outbox/message1.xml`.

### To run the example via Eclipse

Run as "Java Application" and choose FileCopierWithCamel.

