# Researches I've made while working on labs

## InvocationTargetException

https://www.google.com/search?sxsrf=ALeKk02cfPR2nDiwFycr0FGWr25WWTEZFg%3A1591351077025&ei=JRfaXq6FAZGo1fAP67amsAI&q=+InvocationTargetException&oq=+InvocationTargetException&gs_lcp=CgZwc3ktYWIQAzIGCAAQBxAeMgYIABAHEB4yBggAEAcQHjIGCAAQBxAeMgYIABAHEB4yBggAEAcQHjIGCAAQBxAeMgYIABAHEB4yBggAEAcQHjIGCAAQBxAeUK-MAVivjAFgmpEBaABwAHgAgAGxAogBsQKSAQMzLTGYAQCgAQGqAQdnd3Mtd2l6&sclient=psy-ab&ved=0ahUKEwjuq6LdtOrpAhURVBUIHWubCSYQ4dUDCAw&uact=5

## Error creating bean with name 'entityManagerFactory' defined in class path resource [org/springframework/boot/autoconfigure/orm/j pa/HibernateJpaConfiguration.class]: Invocation of init method failed; nested exception is java.lang.NoClassDefFoundError: javax/xml/bind/JAXBException: javax.xml.bind .JAXBException

https://stackoverflow.com/questions/47503046/error-creating-bean-with-name-entitymanagerfactory-when-add-spring-boot-jpa-de/47504698

https://mvnrepository.com/artifact/javax.xml.bind/jaxb-api/2.4.0-b180830.0359

## Unable to instantiate default tuplizer [org.hibernate.tuple.entity.PojoEntityTuplizer]: NullPointerException

https://www.google.com/search?q=Unable+to+instantiate+default+tuplizer+%5Borg.hibernate.tuple.entity.PojoEntityTuplizer%5D%3A+NullPointerException&oq=Unable+to+instantiate+default+tuplizer+%5Borg.hibernate.tuple.entity.PojoEntityTuplizer%5D%3A+NullPointerException&aqs=chrome..69i57.13004j0j9&sourceid=chrome&ie=UTF-8

https://stackoverflow.com/questions/8891154/unable-to-instantiate-default-tuplizer-org-hibernate-tuple-entity-pojoentitytup

## InvocationTargetException: Error loading configuration for /frontend_cloud: 400 Bad Request

https://www.google.com/search?q=InvocationTargetException%3A+Error+loading+configuration+for+%2Ffrontend_cloud%3A+400+Bad+Request&oq=InvocationTargetException%3A+Error+loading+configuration+for+%2Ffrontend_cloud%3A+400+Bad+Request&aqs=chrome..69i57j69i58.2353j0j7&sourceid=chrome&ie=UTF-8

https://github.com/spring-cloud/spring-cloud-gcp/issues/246

## Useful code to add in pom.xml to avoid errors while building

```
<!-- https://mvnrepository.com/artifact/javax.xml.bind/jaxb-api -->
<dependency>
    <groupId>javax.xml.bind</groupId>
    <artifactId>jaxb-api</artifactId>
    <version>2.4.0-b180830.0359</version>
</dependency>
<dependency>
    <groupId>javassist</groupId>
    <artifactId>javassist</artifactId>
    <version>3.12.1.GA</version>
</dependency> 
```


## gzip: stdin: unexpected end of file tar: Child returned status 1 tar: Error is not recoverable: exiting now

https://www.google.com/search?q=gzip%3A+stdin%3A+unexpected+end+of+file+tar%3A+Child+returned+status+1+tar%3A+Error+is+not+recoverable%3A+exiting+now&oq=gzip%3A+stdin%3A+unexpected+end+of+file+tar%3A+Child+returned+status+1+tar%3A+Error+is+not+recoverable%3A+exiting+now&aqs=chrome..69i57j69i58.1743j0j7&sourceid=chrome&ie=UTF-8

https://stackoverflow.com/questions/39643013/gzip-stdin-not-in-gzip-format-tar-child-returned-status-1-tar-error-is-not-r

## spring initializr curl

https://www.google.com/search?sxsrf=ALeKk02uVDZuzrpIbmmhhFWliQmaI-rr3A%3A1591428011674&ei=q0PbXuvqKOWk1fAP_7GTsAg&q=spring+initializr+curl&oq=spring+initializr+curl&gs_lcp=CgZwc3ktYWIQAzIFCAAQywEyBggAEBYQHjoECAAQRzoCCABQ6PIEWMmABWCghAVoAHABeACAAboDiAGcDpIBBzItMS4yLjKYAQCgAQGqAQdnd3Mtd2l6&sclient=psy-ab&ved=0ahUKEwir7Miq0-zpAhVlUhUIHf_YBIYQ4dUDCAw&uact=5

https://github.com/spring-io/initializr

https://docs.spring.io/initializr/docs/current/reference/html/

## how to unzip linux

https://www.google.com/search?q=how+to+unzip+linux&oq=how+to+unzi&aqs=chrome.3.0j69i57j0l6.8771j0j7&sourceid=chrome&ie=UTF-8

https://linuxize.com/post/how-to-unzip-files-in-linux/

## lab 5 task 7 question 1 solution

https://www.coursera.org/learn/google-cloud-java-spring/discussions/weeks/2/threads/K1aQ3AQtSOGWkNwELcjhBg

```
cd ~

mkdir message-processor

cd message-processor

curl https://start.spring.io/starter.tgz -d dependencies=cloud-gcp-pubsub -d bootVersion=2.1.9.RELEASE -o message-processor.tgz

tar -xzvf message-processor.tgz

rm message-processor.tgz
```
