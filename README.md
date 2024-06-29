# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.2.0/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.2.0/maven-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/3.2.0/reference/htmlsingle/index.html#web)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)

### Maven Parent overrides

Due to Maven's design, elements are inherited from the parent POM to the project POM.
While most of the inheritance is fine, it also inherits unwanted elements like `<license>` and `<developers>` from the parent.
To prevent this, the project POM contains empty overrides for these elements.
If you manually switch to a different parent and actually want the inheritance, you need to remove those overrides.

---

### Vscode configuration (Transitioning from Intellij)

In vscode how do I perform or achieve the following common actions on a spring project
* Folder icons compatible for spring project
* Theme compatible for spring project
* Search by file name
* Run configurations to run spring app. 
* How to set up break points and do debugging
* Hot live reload
* Todo and fixme list 
* Auto format the code on save
* Check style integration 
* Sonarqube integration
* How to write and run unit test
* View documentation of any thing in the code
* Refactoring
  * Extract variable
  * Extract method
  * Inline variable
  * Go to declaration
  * Go to all implementations
* Emmets for common use cases
  * for example soutv should give system.out.printline("$variable of the upperline)

Currently I have the following extensions installed in vscode - Extensions installed on WSL: Ubuntu-22.04:
* redhat.fabric8-analytics
* redhat.java
* visualstudioexptteam.intellicode-api-usage-examples
* visualstudioexptteam.vscodeintellicode
* vmware.vscode-boot-dev-pack
* vmware.vscode-spring-boot
* vscjava.vscode-java-debug
* vscjava.vscode-java-dependency
* vscjava.vscode-java-pack
* vscjava.vscode-java-test
* vscjava.vscode-maven
* vscjava.vscode-spring-boot-dashboard
* vscjava.vscode-spring-initializr
* yzhang.markdown-all-in-one

FYA - https://chatgpt.com/c/63d819bc-a6df-4ffa-b870-65dbe383cb74