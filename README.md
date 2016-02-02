# JPetStore-Azure-Cloud-Application

For deployment, JPetStore needs to be built with Apache Maven. The only requirements are JDK >=1.5 and Maven >= 2.0.8

Running JpetStore with Tomcat:

1.	Download and Unzip Tomcat
2.	Download JpetStore source code
3.	From Eclipse, Import -> Maven -> Existing Maven Projects -> unzipped jpetstore source
4.	Delete parent pom references from pom.xml
5.	Change the stripe dependency 
6.	Run as maven project to build war files. The war file gets created in the “target” directory
7.	JpetStore is now accessible from the browser 
