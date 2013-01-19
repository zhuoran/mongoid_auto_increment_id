
#This is a Java tool for generate auto-incremented sequence number like MYSQL. 
##Idea from MongoDB document: [How to Make an Auto Incrementing Field](http://www.mongodb.org/display/DOCS/How+to+Make+an+Auto+Incrementing+Field)

================================================================
USAGE
===============================================================

1.check out the source code


2.mvn clean install -Dmaven.test.skip


3.add dependency into pom.xml

        <dependency>
		<groupId>me.zhuoran.mongo.MongoIdentity</groupId>
		<artifactId>MongoIdentity</artifactId>
		<version>1.0</version>
	</dependency>