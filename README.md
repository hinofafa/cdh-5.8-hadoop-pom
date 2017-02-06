# cdh-5.8-hadoop-pom

This is a basic pom.xml file used to compile the Hadoop programs in CDH-5.8 Quick Start VM

## Getting started

**Step 1.** Generate a `pom.xml` file through the following maven commands:

    mvn -B archetype:generate \
        -DarchetypeGroupId=org.apache.maven.archetypes \
        -DgroupId=hk.ust.YOUR_USERNAME \
        -DartifactId=YOUR_APP_NAME`
  
**Step 2.** In the base directory, replace the generated `pom.xml` with the one in this repo.

**Step 3.** In `pom.xml`, change the following line and replace my username with yours.

    <groupId>hk.ust.weiwa</groupId>
    
You can now start writing your Hadoop code.
