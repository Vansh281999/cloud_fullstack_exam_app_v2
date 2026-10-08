# Spring Boot — New MCQ Add-On Set

**New questions only: 226**

Source basis: `split_1(1).txt`, `split_2(1).txt`, `split_3(1).txt`.
These are additional questions intended to expand the existing 675-question database; the original questions are not included here.

## Statistics
- Easy: 65
- Medium: 114
- Hard: 47
- Single correct: 184
- Multiple correct: 42

## Coverage
Spring Boot goals; project setup/Initializr; project structure/startup; starter projects; Boot 4 starter naming; auto-configuration; DevTools; profiles/logging; ConfigurationProperties; external configuration; embedded servers; Actuator; Spring vs Spring MVC vs Spring Boot; H2/JDBC/JPA auto-configuration; CommandLineRunner; Boot testing; Maven parent/plugin; Gradle setup; integrated scenarios.

---

### Q1. [Easy] [SINGLE CORRECT]

What primary combination of outcomes does the transcript associate with the goal of Spring Boot?

A. Build applications quickly and make them production-ready
B. Replace Java with another language and database
C. Eliminate all application code
D. Provide only a UI framework

**Answer: A**

**Explanation:** The transcript states the key goal as building production-ready applications quickly.

**Topic:** Spring Boot goals
**Source:** split 2 Step 05

---

### Q2. [Easy] [SINGLE CORRECT]

Which pre-Spring-Boot task is specifically described as repetitive project setup work?

A. Manually managing framework dependencies and their versions
B. Converting every class to TypeScript
C. Writing CSS for every controller
D. Replacing HTTP with FTP

**Answer: A**

**Explanation:** Before Spring Boot, dependency management, configuration, and non-functional features had to be handled repeatedly.

**Topic:** Spring Boot goals
**Source:** split 2 Step 02

---

### Q3. [Medium] [SINGLE CORRECT]

A team needs a REST API and wants to avoid separately configuring Spring MVC, a JSON binding framework, and logging for every new project. Which Spring Boot idea most directly addresses this setup problem?

A. Production-ready defaults and automated setup
B. Manual web.xml expansion
C. More servlet subclasses
D. A larger view layer

**Answer: A**

**Explanation:** Spring Boot reduces repeated configuration and provides defaults aimed at rapid, production-ready application setup.

**Topic:** Spring Boot goals
**Source:** split 2 Step 02

---

### Q4. [Medium] [MULTIPLE CORRECT]

Which two concerns are explicitly presented as part of the production-ready side of Spring Boot's goal? [Select all that apply]

A. Different configuration for different environments
B. Application monitoring
C. Replacing all unit tests with manual testing
D. Removing all logging

**Answers: A, B**

**Explanation:** Profiles/configuration support different environments, while Actuator and related features support monitoring.

**Topic:** Spring Boot goals
**Source:** split 2 Step 05

---

### Q5. [Easy] [SINGLE CORRECT]

Which feature is connected in the transcript to reducing the need to manually restart the server after code changes?

A. Spring Boot DevTools
B. Spring Boot Actuator
C. Spring Boot Starter Security
D. Spring Boot Parent POM

**Answer: A**

**Explanation:** DevTools is presented as a developer-productivity feature that automatically picks up code changes.

**Topic:** Spring Boot goals
**Source:** split 2 Step 05

---

### Q6. [Medium] [SINGLE CORRECT]

Which statement best captures the distinction the transcript makes between speed and production readiness?

A. Spring Boot aims to improve both, not just project creation speed
B. Spring Boot only optimizes local development
C. Spring Boot only adds monitoring after deployment
D. Spring Boot's only purpose is dependency management

**Answer: A**

**Explanation:** The transcript emphasizes both 'quickly' and 'production-ready' as essential parts of the goal.

**Topic:** Spring Boot goals
**Source:** split 2 Step 05

---

### Q7. [Easy] [MULTIPLE CORRECT]

Which of the following were listed as Spring Boot features supporting production readiness? [Select all that apply]

A. Default logging
B. Profiles
C. Configuration properties
D. Spring Boot Actuator

**Answers: A, B, C, D**

**Explanation:** All four are explicitly named as production-readiness features in the transcript.

**Topic:** Spring Boot goals
**Source:** split 2 Step 05

---

### Q8. [Medium] [SINGLE CORRECT]

Before Spring Boot, why could even a simple web application require substantial configuration?

A. Developers had to configure items such as DispatcherServlet and component scanning manually
B. The JVM did not support classes
C. HTTP had to be implemented from scratch
D. Java had no dependency system at all

**Answer: A**

**Explanation:** The transcript cites DispatcherServlet, component scan, view resolver, data source, and other configuration as manual work.

**Topic:** Spring Boot goals
**Source:** split 2 Step 02

---

### Q9. [Hard] [SINGLE CORRECT]

A project is spending days repeating the same initial configuration across environments and new applications. Which Spring Boot principle from the material is most relevant?

A. Reduce repeated setup through conventions, starters, and automatic configuration
B. Add more XML descriptors
C. Move configuration into every controller
D. Avoid build tools

**Answer: A**

**Explanation:** Spring Boot is introduced as a way to reduce repeated setup and get production-ready features quickly.

**Topic:** Spring Boot goals
**Source:** split 2 Step 02

---

### Q10. [Medium] [MULTIPLE CORRECT]

Which set pairs a Spring Boot feature with the purpose stated in the transcript? [Select all that apply]

A. Starter projects — quickly define dependencies
B. Auto-configuration — automatically provide configuration from classpath context
C. DevTools — automatically pick up code changes
D. Actuator — support production monitoring

**Answers: A, B, C, D**

**Explanation:** Each pairing is directly supported by the Spring Boot section of the transcript.

**Topic:** Spring Boot goals
**Source:** split 2 Step 05

---

### Q11. [Easy] [SINGLE CORRECT]

Where does the transcript direct the learner to start a new Spring Boot project?

A. start.spring.io
B. localhost:8080
C. maven.apache.org
D. springmvc.io

**Answer: A**

**Explanation:** Spring Initializr is described as the starting point at start.spring.io.

**Topic:** Spring Initializr
**Source:** split 2 Step 03

---

### Q12. [Easy] [SINGLE CORRECT]

In the demonstrated Spring Boot project creation flow, which build tool was selected?

A. Maven
B. Ant
C. Gradle Kotlin only
D. Make

**Answer: A**

**Explanation:** The transcript's Spring Initializr example selects Maven as the build tool.

**Topic:** Spring Initializr
**Source:** split 2 Step 03

---

### Q13. [Easy] [SINGLE CORRECT]

Which language is selected in the demonstrated Spring Boot Initializr setup?

A. Java
B. Kotlin
C. Groovy
D. Scala

**Answer: A**

**Explanation:** The project is created using Java.

**Topic:** Spring Initializr
**Source:** split 2 Step 03

---

### Q14. [Medium] [SINGLE CORRECT]

Why does the transcript advise avoiding a Spring Boot snapshot version when creating the project?

A. Snapshots are versions under development rather than released versions
B. Snapshots always disable embedded servers
C. Snapshots cannot use Maven
D. Snapshots are only for testing HTML

**Answer: A**

**Explanation:** The transcript explicitly describes snapshots as versions still being developed.

**Topic:** Spring Initializr
**Source:** split 2 Step 03

---

### Q15. [Medium] [SINGLE CORRECT]

Which project metadata field is compared to a Java package name in the transcript?

A. Group ID
B. Artifact ID
C. Version
D. Packaging

**Answer: A**

**Explanation:** The transcript compares Group ID to a package name and Artifact ID to the project name.

**Topic:** Spring Initializr
**Source:** split 2 Step 03

---

### Q16. [Easy] [SINGLE CORRECT]

Which project metadata field is described as the name of the project?

A. Artifact ID
B. Group ID
C. Java version
D. Configuration format

**Answer: A**

**Explanation:** The demonstrated artifact ID is the project name.

**Topic:** Spring Initializr
**Source:** split 2 Step 03

---

### Q17. [Easy] [SINGLE CORRECT]

Which default packaging choice is used in the demonstrated Spring Boot Initializr setup?

A. Jar
B. Ear
C. Tar
D. Zip-only web archive

**Answer: A**

**Explanation:** The transcript selects Jar packaging.

**Topic:** Spring Initializr
**Source:** split 2 Step 03

---

### Q18. [Easy] [SINGLE CORRECT]

Which configuration format is selected in the demonstrated Spring Initializr example?

A. Properties
B. XML only
C. YAML only
D. JSON only

**Answer: A**

**Explanation:** The example takes properties as the configuration format.

**Topic:** Spring Initializr
**Source:** split 2 Step 03

---

### Q19. [Medium] [SINGLE CORRECT]

A developer selects Spring Web in Initializr for a REST API. According to the transcript, what is the direct web-stack role of that selection?

A. It is used to build web applications including RESTful applications using Spring MVC
B. It configures only database migrations
C. It replaces Java
D. It creates only command-line programs

**Answer: A**

**Explanation:** The transcript says Spring Web is used to build web applications and RESTful applications using Spring MVC.

**Topic:** Spring Initializr
**Source:** split 2 Step 03

---

### Q20. [Medium] [MULTIPLE CORRECT]

Which Spring Boot project setup statements are supported by the transcripts? [Select all that apply]

A. Initializr can generate a project ZIP
B. The generated project can be imported as an existing Maven project
C. Maven downloads the project's dependencies
D. The example launches the application on Tomcat port 8080

**Answers: A, B, C, D**

**Explanation:** All four steps are explicitly shown in the project setup walkthrough.

**Topic:** Spring Initializr
**Source:** split 2 Step 03

---

### Q21. [Medium] [SINGLE CORRECT]

After extracting the ZIP generated by Spring Initializr, which IDE import path is demonstrated for the Maven example?

A. File → Import → Existing Maven Projects
B. File → New → JavaScript Project
C. File → Export → WAR
D. File → Convert → Servlet Project

**Answer: A**

**Explanation:** The transcript demonstrates importing the extracted project as an existing Maven project.

**Topic:** Spring Initializr
**Source:** split 2 Step 03

---

### Q22. [Easy] [SINGLE CORRECT]

Which pair of directories is presented as part of the generated Spring Boot project layout in the Initializr walkthrough?

A. src/main/java and src/main/resources
B. src/html and src/css
C. web.xml and WEB-INF only
D. bin/main and lib/test

**Answer: A**

**Explanation:** The transcript points to source main Java and source main resources in the generated project.

**Topic:** Spring Initializr
**Source:** split 2 Step 03

---

### Q23. [Easy] [SINGLE CORRECT]

A newly generated Spring Boot project starts on which port in the transcript's default web setup?

A. 8080
B. 3000
C. 5432
D. 9090

**Answer: A**

**Explanation:** The application is shown launching on Tomcat at port 8080.

**Topic:** Spring Initializr
**Source:** split 2 Step 03

---

### Q24. [Medium] [SINGLE CORRECT]

Which version-related statement is consistent with the transcript's guidance for Initializr?

A. Prefer the latest released version available and avoid snapshot versions
B. Always choose a milestone version
C. Always choose the oldest version
D. Version selection does not matter

**Answer: A**

**Explanation:** The material repeatedly recommends a latest released version rather than a snapshot.

**Topic:** Spring Initializr
**Source:** split 2 Step 03

---

### Q25. [Medium] [SINGLE CORRECT]

When the transcript mentions Spring Boot 4, which web starter name is shown for newer projects?

A. spring-boot-starter-webmvc
B. spring-boot-starter-web
C. spring-boot-starter-http-only
D. spring-boot-starter-restmvc-test-only

**Answer: A**

**Explanation:** The transcript notes that Spring Boot 4 examples use spring-boot-starter-webmvc, whereas older examples used spring-boot-starter-web.

**Topic:** Starter projects
**Source:** split 2 Step 03

---

### Q26. [Medium] [SINGLE CORRECT]

For Spring Boot 4, which testing starter name is shown in the transcript?

A. spring-boot-starter-webmvc-test
B. spring-boot-starter-test
C. spring-boot-testing-web-only
D. spring-boot-starter-junit-only

**Answer: A**

**Explanation:** The transcript contrasts Spring Boot 4's webmvc test starter with the older starter-test name.

**Topic:** Starter projects
**Source:** split 2 Step 03

---

### Q27. [Hard] [MULTIPLE CORRECT]

Which statements about the Boot 4 starter naming change are correct? [Select all that apply]

A. The transcript shows spring-boot-starter-webmvc for web applications
B. The transcript shows spring-boot-starter-webmvc-test for tests
C. Older examples may still show spring-boot-starter-web
D. Older examples may still show spring-boot-starter-test

**Answers: A, B, C, D**

**Explanation:** The transcript explicitly explains the newer and older starter names so learners do not get confused by older course code.

**Topic:** Starter projects
**Source:** split 2 Step 03

---

### Q28. [Easy] [SINGLE CORRECT]

In the Spring Boot setup demonstrated in the transcript, what happens after the generated project is successfully imported and run?

A. The application launches as a Java application with embedded Tomcat
B. A browser downloads the source code
C. Maven converts the Java code to JavaScript
D. The application is forced into WAR-only deployment

**Answer: A**

**Explanation:** The transcript runs the Spring Boot application as a Java application and shows Tomcat starting on 8080.

**Topic:** Boot application setup
**Source:** split 2 Step 03

---

### Q29. [Medium] [SINGLE CORRECT]

Why can the generated Spring Boot project appear to download many libraries during its first setup?

A. Maven resolves the project's dependencies brought in by the selected starters
B. Tomcat compiles CSS
C. Initializr runs every endpoint
D. Actuator generates all application metrics before startup

**Answer: A**

**Explanation:** The setup shows Maven downloading many dependencies declared or implied by the selected starters.

**Topic:** Boot application setup
**Source:** split 2 Step 03

---

### Q30. [Medium] [MULTIPLE CORRECT]

Which two project areas are explicitly identified as places for main source code and application configuration? [Select all that apply]

A. src/main/java
B. src/main/resources
C. src/test/java
D. src/test/resources

**Answers: A, B**

**Explanation:** The question asks specifically for main source and main configuration; the transcript assigns those to src/main/java and src/main/resources.

**Topic:** Boot application setup
**Source:** split 2 Step 03

---

### Q31. [Medium] [SINGLE CORRECT]

Which Spring Boot capability is illustrated when a generated application can be started without the learner writing a web-server installation procedure?

A. Embedded server support
B. Manual web.xml deployment
C. Client-side routing
D. Database sharding

**Answer: A**

**Explanation:** The generated web setup starts with embedded Tomcat, removing the need for a separate server installation in that flow.

**Topic:** Embedded servers
**Source:** split 2 Step 11

---

### Q32. [Medium] [SINGLE CORRECT]

A learner runs the application as a Java application and sees Tomcat start on port 8080. What does this observation most directly confirm?

A. The Boot web application is using an embedded servlet container
B. The project has no external dependencies
C. The application is using Angular
D. The database has been created

**Answer: A**

**Explanation:** The transcript uses the startup log to show the embedded Tomcat server starting.

**Topic:** Embedded servers
**Source:** split 2 Step 11

---

### Q33. [Easy] [SINGLE CORRECT]

What is the best description of a Spring Boot starter according to the transcript?

A. A convenient dependency descriptor for a particular application capability
B. A replacement for the JVM
C. A servlet URL mapping
D. A database table definition

**Answer: A**

**Explanation:** Starters group the dependencies normally needed for a particular type of feature.

**Topic:** Starter projects
**Source:** split 2 Step 06

---

### Q34. [Medium] [SINGLE CORRECT]

A team wants to build a REST API with Spring MVC and JSON conversion. Which starter role from the transcript best matches this need?

A. A web starter that brings together the needed web dependencies
B. The Actuator starter only
C. A JDBC starter only
D. A security starter only

**Answer: A**

**Explanation:** The web starter is presented as the convenient dependency descriptor for web/REST applications.

**Topic:** Starter projects
**Source:** split 2 Step 06

---

### Q35. [Easy] [SINGLE CORRECT]

Which framework is explicitly named as performing JSON conversion in the Spring Boot web example?

A. Jackson
B. JUnit
C. Mockito
D. Hibernate

**Answer: A**

**Explanation:** The transcript explains that Jackson performs the Bean/list-to-JSON conversion.

**Topic:** Starter projects
**Source:** split 2 Step 07

---

### Q36. [Easy] [SINGLE CORRECT]

Which starter is identified for Spring Data JPA database access?

A. spring-boot-starter-data-jpa
B. spring-boot-starter-actuator
C. spring-boot-starter-security
D. spring-boot-starter-devtools

**Answer: A**

**Explanation:** The transcript maps database access through JPA to Spring Boot Starter Data JPA.

**Topic:** Starter projects
**Source:** split 2 Step 06

---

### Q37. [Easy] [SINGLE CORRECT]

Which starter is identified for JDBC-based database access?

A. spring-boot-starter-jdbc
B. spring-boot-starter-aop
C. spring-boot-starter-actuator
D. spring-boot-starter-webmvc-test

**Answer: A**

**Explanation:** The transcript maps JDBC database access to Spring Boot Starter JDBC.

**Topic:** Starter projects
**Source:** split 2 Step 06

---

### Q38. [Easy] [SINGLE CORRECT]

Which starter is identified for securing a Spring Boot web application or REST API?

A. spring-boot-starter-security
B. spring-boot-starter-jdbc
C. spring-boot-starter-actuator
D. spring-boot-starter-parent

**Answer: A**

**Explanation:** The transcript explicitly names Spring Boot Starter Security for securing web applications and REST APIs.

**Topic:** Starter projects
**Source:** split 2 Step 06

---

### Q39. [Hard] [MULTIPLE CORRECT]

Which statements about Spring Boot starters are correct? [Select all that apply]

A. They group dependencies for a feature
B. They reduce the need to list every related library manually
C. They are chosen according to the application's use case
D. They themselves replace all application configuration

**Answers: A, B, C**

**Explanation:** Starters simplify dependency selection, but the transcript separately explains that dependencies alone are not the whole configuration story.

**Topic:** Starter projects
**Source:** split 2 Step 06

---

### Q40. [Medium] [SINGLE CORRECT]

A project adds a web starter and suddenly sees Spring MVC, Tomcat, and JSON-related libraries in its resolved dependencies. What concept best explains this?

A. The starter pulls in a predefined set of related dependencies
B. Actuator has generated the libraries
C. The browser downloaded them
D. JUnit converted them into web dependencies

**Answer: A**

**Explanation:** That is precisely the convenience provided by starter projects.

**Topic:** Starter projects
**Source:** split 2 Step 06

---

### Q41. [Hard] [SINGLE CORRECT]

Why does the transcript describe starters as 'convenient dependency descriptors' rather than as complete applications?

A. They describe the dependency set needed for a capability, while the application still needs configuration and code
B. They are executable business services
C. They are database records
D. They are deployment servers

**Answer: A**

**Explanation:** The transcript says starters group dependencies; it then separately introduces auto-configuration.

**Topic:** Starter projects
**Source:** split 2 Step 06

---

### Q42. [Medium] [SINGLE CORRECT]

Which pairing is correct based on the starter examples in the transcript?

A. Data JPA → JPA database access
B. JDBC → monitoring endpoints
C. Security → JSON serialization
D. Actuator → servlet request parsing

**Answer: A**

**Explanation:** The transcript associates Data JPA with JPA access, JDBC with JDBC access, Security with security, and Actuator with monitoring.

**Topic:** Starter projects
**Source:** split 2 Step 06

---

### Q43. [Medium] [MULTIPLE CORRECT]

Which four concerns are used in the web-starter explanation to show why many dependencies might otherwise be needed? [Select all that apply]

A. Spring MVC
B. Tomcat
C. JSON conversion
D. Testing frameworks in a separate test scenario

**Answers: A, B, C, D**

**Explanation:** The transcript lists these as examples of the frameworks or facilities that would need to be assembled without starters.

**Topic:** Starter projects
**Source:** split 2 Step 06

---

### Q44. [Medium] [SINGLE CORRECT]

If a learner chooses the wrong starter for a use case, what does the transcript imply?

A. The learner should choose a different starter appropriate to the application capability
B. The starter dynamically rewrites the Java language
C. The database schema is automatically replaced
D. The IDE will refuse to open the project

**Answer: A**

**Explanation:** The key guidance is to select the starter matching the intended capability.

**Topic:** Starter projects
**Source:** split 2 Step 06

---

### Q45. [Medium] [SINGLE CORRECT]

What two inputs are highlighted as helping determine Spring Boot auto-configuration?

A. Frameworks/classes on the classpath and configuration already provided by the application
B. CPU speed and screen resolution
C. Browser type and HTML version
D. Database rows and user count

**Answer: A**

**Explanation:** The transcript explicitly describes both classpath contents and existing configuration as factors.

**Topic:** Auto-configuration
**Source:** split 2 Step 07

---

### Q46. [Easy] [SINGLE CORRECT]

Which statement about auto-configuration is closest to the transcript's explanation?

A. Spring Boot provides default configuration based on what is available in the classpath
B. Spring Boot ignores classpath contents
C. Spring Boot configures only controllers
D. Spring Boot requires every bean to be XML-defined

**Answer: A**

**Explanation:** Auto-configuration is defined as automated configuration driven by classpath frameworks plus existing configuration.

**Topic:** Auto-configuration
**Source:** split 2 Step 07

---

### Q47. [Medium] [SINGLE CORRECT]

What happens to Spring Boot's defaults when a developer provides configuration that overrides them?

A. The developer's configuration can override the defaults
B. The application must stop permanently
C. The starter is removed from the classpath
D. Actuator disables itself

**Answer: A**

**Explanation:** The transcript explicitly says Boot provides defaults that can be overridden by your own configuration.

**Topic:** Auto-configuration
**Source:** split 2 Step 07

---

### Q48. [Easy] [SINGLE CORRECT]

Which JAR is named in the transcript as containing the auto-configuration logic?

A. spring-boot-autoconfigure.jar
B. spring-core-test.jar
C. hibernate-web.jar
D. jackson-runtime-only.jar

**Answer: A**

**Explanation:** The transcript names spring-boot-autoconfigure.jar as the location of auto-configuration logic.

**Topic:** Auto-configuration
**Source:** split 2 Step 07

---

### Q49. [Medium] [SINGLE CORRECT]

According to the transcript, what does the auto-configuration report show besides configurations that match?

A. Negative matches where attempted auto-configurations did not match their conditions
B. Only successful HTTP responses
C. Only SQL statements
D. Only Java compilation errors

**Answer: A**

**Explanation:** The debug auto-configuration report also shows negative matches.

**Topic:** Auto-configuration
**Source:** split 2 Step 07

---

### Q50. [Medium] [SINGLE CORRECT]

A project includes an embedded H2 database on the classpath. Which auto-configuration effect is demonstrated?

A. A data source can be automatically configured
B. An Angular application is created
C. A JSP is automatically generated
D. A Git repository is initialized

**Answer: A**

**Explanation:** The transcript says an embedded database on the classpath leads to data-source auto-configuration.

**Topic:** Auto-configuration
**Source:** split 2 Step 07

---

### Q51. [Medium] [SINGLE CORRECT]

A web application is present on the classpath. Which auto-configuration behavior is demonstrated?

A. A DispatcherServlet can be automatically configured
B. A database table is generated
C. A Maven repository is created
D. A TypeScript compiler is enabled

**Answer: A**

**Explanation:** The transcript explicitly uses the web application classpath as an example for DispatcherServlet auto-configuration.

**Topic:** Auto-configuration
**Source:** split 2 Step 07

---

### Q52. [Hard] [SINGLE CORRECT]

If JPA is present on the classpath, which pair is named as being automatically configured?

A. EntityManagerFactory and transaction manager
B. Jenkins and Git
C. ViewResolver and JSP compiler
D. Jackson and Mockito only

**Answer: A**

**Explanation:** The transcript states that JPA on the classpath leads Boot to configure an EntityManagerFactory and transaction manager.

**Topic:** Auto-configuration
**Source:** split 2 database auto-configuration

---

### Q53. [Medium] [MULTIPLE CORRECT]

With a web starter on the classpath, which capabilities are described as auto-configured? [Select all that apply]

A. Embedded servlet container
B. DispatcherServlet
C. Default error pages
D. Bean/list to JSON conversion

**Answers: A, B, C, D**

**Explanation:** The transcript lists all four as results of the Boot web setup.

**Topic:** Auto-configuration
**Source:** split 2 Step 07

---

### Q54. [Hard] [SINGLE CORRECT]

Which component is named as providing the Bean/list-to-JSON message conversion in the web example?

A. Jackson HTTP message conversion
B. Spring Test runner
C. Hibernate entity manager
D. Maven dependency graph

**Answer: A**

**Explanation:** The transcript attributes the automatic JSON conversion to Jackson and its message-converter configuration.

**Topic:** Auto-configuration
**Source:** split 2 Step 07

---

### Q55. [Medium] [SINGLE CORRECT]

A developer enables debug logging and searches for a configuration report. What are they trying to inspect?

A. The decisions made by Spring Boot auto-configuration
B. The list of HTTP request bodies
C. The CSS compiled by the browser
D. The Git commit history

**Answer: A**

**Explanation:** The transcript recommends examining the auto-configuration report in debug mode.

**Topic:** Auto-configuration
**Source:** split 2 Step 07

---

### Q56. [Hard] [MULTIPLE CORRECT]

Which condition is part of the example for H2 console auto-configuration? [Select all that apply]

A. A web servlet class is present
B. H2 is present on the classpath
C. The H2 console enable property is set
D. A matching database console condition is available

**Answers: A, B, C**

**Explanation:** The transcript says H2 console auto-configuration checks for a web servlet, H2 on the classpath, and the enabling property.

**Topic:** Auto-configuration
**Source:** split 2 H2 auto-configuration

---

### Q57. [Hard] [SINGLE CORRECT]

Why does adding an embedded H2 dependency have effects beyond merely adding a JAR?

A. Its presence on the classpath can trigger related auto-configuration such as a data source
B. The JAR rewrites the controller code
C. The JAR replaces Java bytecode with HTML
D. The JAR turns every request into POST

**Answer: A**

**Explanation:** Boot uses classpath conditions to decide what to auto-configure.

**Topic:** Auto-configuration
**Source:** split 2 H2 auto-configuration

---

### Q58. [Hard] [MULTIPLE CORRECT]

Which statements accurately describe auto-configuration behavior in the transcripts? [Select all that apply]

A. It can use classpath information
B. It can use existing application configuration
C. It can expose information about negative matches in the report
D. It is entirely independent of starters

**Answers: A, B, C**

**Explanation:** Starters bring frameworks onto the classpath; auto-configuration then uses the classpath plus configuration context.

**Topic:** Auto-configuration
**Source:** split 2 Step 07

---

### Q59. [Medium] [SINGLE CORRECT]

A developer manually configures a component that Boot would normally provide by default. What principle from the transcript explains why this can work?

A. Boot's default auto-configuration can be overridden by application configuration
B. Boot ignores manual configuration
C. Manual configuration always disables Java
D. Only Actuator can override defaults

**Answer: A**

**Explanation:** The transcript directly states that developer configuration can override Boot's defaults.

**Topic:** Auto-configuration
**Source:** split 2 Step 07

---

### Q60. [Easy] [SINGLE CORRECT]

What is the primary developer-productivity purpose given for Spring Boot DevTools?

A. Automatically pick up code changes instead of requiring a manual server restart
B. Expose health endpoints
C. Manage database transactions
D. Generate JPQL

**Answer: A**

**Explanation:** DevTools is introduced to reduce manual restart work during development.

**Topic:** DevTools
**Source:** split 2 Step 08

---

### Q61. [Easy] [SINGLE CORRECT]

Where must Spring Boot DevTools be added in the Maven project according to the walkthrough?

A. pom.xml
B. application-prod.properties
C. web.xml
D. settings.gradle only

**Answer: A**

**Explanation:** The transcript adds the DevTools dependency to pom.xml.

**Topic:** DevTools
**Source:** split 2 Step 08

---

### Q62. [Medium] [SINGLE CORRECT]

A developer saves a valid controller change while DevTools is active. What behavior is demonstrated?

A. A restart is automatically triggered and the changed behavior can be tested after refresh
B. The project is deleted
C. Actuator is disabled
D. Maven changes the database schema

**Answer: A**

**Explanation:** The transcript shows a restart automatically triggered after saving a code change.

**Topic:** DevTools
**Source:** split 2 Step 08

---

### Q63. [Medium] [SINGLE CORRECT]

Which event in the transcript proves DevTools is reacting to source changes?

A. The console shows an automatic restart after the class is saved
B. A new database is installed
C. The browser downloads Java
D. The server changes from Tomcat to Jetty

**Answer: A**

**Explanation:** The restart log is the visible evidence of DevTools responding to the code change.

**Topic:** DevTools
**Source:** split 2 Step 08

---

### Q64. [Hard] [SINGLE CORRECT]

Which change is explicitly described as something DevTools cannot handle in the walkthrough?

A. Changes to pom.xml
B. Changes to a controller class
C. Changes to a Java method
D. Adding a new class

**Answer: A**

**Explanation:** The transcript states that DevTools cannot handle changes in pom.xml.

**Topic:** DevTools
**Source:** split 2 Step 08

---

### Q65. [Medium] [MULTIPLE CORRECT]

Which activities fit the role of DevTools described in the transcript? [Select all that apply]

A. Improving developer productivity
B. Automatically detecting application code changes
C. Reducing manual restarts during development
D. Providing production health metrics as its primary role

**Answers: A, B, C**

**Explanation:** The first three describe DevTools; production monitoring is the role assigned to Actuator.

**Topic:** DevTools
**Source:** split 2 Step 08

---

### Q66. [Hard] [SINGLE CORRECT]

A developer expects a pom.xml dependency edit to be automatically hot-applied by DevTools in the same way as a Java source edit. What should they conclude from the transcript?

A. That expectation is incorrect because pom.xml changes are specifically noted as unsupported by DevTools
B. That Actuator will apply the change
C. That the browser will rewrite the POM
D. That Maven is unnecessary

**Answer: A**

**Explanation:** The transcript explicitly calls out pom.xml changes as a limitation.

**Topic:** DevTools
**Source:** split 2 Step 08

---

### Q67. [Medium] [SINGLE CORRECT]

Why is DevTools grouped with Initializr and starters in the transcript?

A. All three are presented as features that help developers build applications faster
B. All three are database technologies
C. All three are testing frameworks
D. All three replace Spring MVC

**Answer: A**

**Explanation:** The transcript groups Initializr, starters, auto-configuration and DevTools as speed/productivity features.

**Topic:** DevTools
**Source:** split 2 Step 08

---

### Q68. [Medium] [SINGLE CORRECT]

Which statement best differentiates DevTools from Actuator in the material?

A. DevTools targets development productivity, while Actuator targets production monitoring and management
B. They are identical features
C. Actuator restarts code and DevTools exposes health
D. Both are Maven plugins

**Answer: A**

**Explanation:** The transcript clearly assigns development productivity to DevTools and production monitoring to Actuator.

**Topic:** DevTools vs Actuator
**Source:** split 2 Steps 08/12

---

### Q69. [Medium] [SINGLE CORRECT]

Which sequence matches the demonstrated DevTools feedback loop?

A. Edit Java code → save → automatic restart → refresh/test changed behavior
B. Edit code → deploy WAR manually → reboot OS → refresh
C. Edit code → rebuild browser cache → stop database
D. Edit code → disable Spring Boot → regenerate ZIP

**Answer: A**

**Explanation:** That is the concrete workflow shown in the DevTools demonstration.

**Topic:** DevTools
**Source:** split 2 Step 08

---

### Q70. [Easy] [SINGLE CORRECT]

What problem do Spring Boot profiles solve in the transcript?

A. Using different configuration for different environments
B. Converting JSON to Java
C. Replacing Maven
D. Creating new HTTP methods

**Answer: A**

**Explanation:** Profiles are introduced for dev, QA, staging, production, and other environment-specific configuration.

**Topic:** Profiles
**Source:** split 2 Step 09

---

### Q71. [Easy] [SINGLE CORRECT]

Which filename pattern is used for a development profile in the transcript?

A. application-dev.properties
B. dev-application.properties.xml
C. profile.dev.yml-only
D. environment_dev.java

**Answer: A**

**Explanation:** The transcript uses application-dev.properties.

**Topic:** Profiles
**Source:** split 2 Step 09

---

### Q72. [Easy] [SINGLE CORRECT]

Which filename pattern is used for a production profile in the transcript?

A. application-prod.properties
B. prod-application.properties.xml
C. application.production.java
D. production-profile.xml

**Answer: A**

**Explanation:** The transcript uses application-prod.properties.

**Topic:** Profiles
**Source:** split 2 Step 09

---

### Q73. [Medium] [SINGLE CORRECT]

What happens when no profile is active according to the transcript's logging example?

A. The application uses the default values in application.properties
B. The application stops
C. Only production values are loaded
D. Only test values are loaded

**Answer: A**

**Explanation:** The transcript states that application.properties supplies the default configuration when no profile is active.

**Topic:** Profiles
**Source:** split 2 Step 09

---

### Q74. [Easy] [SINGLE CORRECT]

Which property is used in the transcript to activate a profile?

A. spring.profiles.active
B. spring.profile.current
C. spring.environment.use
D. boot.profile.name

**Answer: A**

**Explanation:** The example activates the production profile using spring.profiles.active=prod.

**Topic:** Profiles
**Source:** split 2 Step 09

---

### Q75. [Hard] [SINGLE CORRECT]

When the prod profile is active, how does the transcript describe the relationship between application.properties and application-prod.properties?

A. They are merged, with profile-specific values taking higher priority
B. Only application.properties is used
C. Only application-prod.properties is used and defaults disappear
D. They are both ignored

**Answer: A**

**Explanation:** The example states that default and active-profile properties are merged and the profile has higher priority.

**Topic:** Profiles
**Source:** split 2 Step 09

---

### Q76. [Medium] [MULTIPLE CORRECT]

Which statements about profiles are supported by the transcript? [Select all that apply]

A. Different environments can have different configuration
B. A profile can change logging levels
C. Profile-specific values can override default values
D. Profiles are unrelated to application configuration

**Answers: A, B, C**

**Explanation:** All three positive statements are directly illustrated by the dev/prod logging example.

**Topic:** Profiles
**Source:** split 2 Step 09

---

### Q77. [Easy] [SINGLE CORRECT]

In the transcript's logging example, which logging level produces the most detailed output?

A. TRACE
B. DEBUG
C. INFO
D. ERROR

**Answer: A**

**Explanation:** The material orders the levels so TRACE prints everything, while lower-severity selections show progressively less.

**Topic:** Profiles and logging
**Source:** split 2 Step 09

---

### Q78. [Medium] [SINGLE CORRECT]

If the logging level is INFO in the transcript's simplified model, which levels are printed?

A. INFO, warning, and error
B. TRACE only
C. DEBUG and TRACE only
D. ERROR only

**Answer: A**

**Explanation:** The transcript explains that INFO includes messages at INFO and the levels below it in its example.

**Topic:** Profiles and logging
**Source:** split 2 Step 09

---

### Q79. [Medium] [SINGLE CORRECT]

Which profile setup would best fit a development environment that needs more diagnostic logging than production, according to the transcript?

A. Activate dev and give application-dev.properties a more detailed logging level
B. Activate prod and reduce all logs to ERROR
C. Remove application.properties
D. Disable profiles entirely

**Answer: A**

**Explanation:** The transcript demonstrates TRACE-like logging in development and INFO-like logging in production.

**Topic:** Profiles and logging
**Source:** split 2 Step 09

---

### Q80. [Easy] [MULTIPLE CORRECT]

Which profile/environment statements are correct? [Select all that apply]

A. Dev can use application-dev.properties
B. Prod can use application-prod.properties
C. spring.profiles.active selects the active profile
D. Without an active profile, application.properties supplies default values

**Answers: A, B, C, D**

**Explanation:** Each point is explicitly demonstrated.

**Topic:** Profiles
**Source:** split 2 Step 09

---

### Q81. [Hard] [SINGLE CORRECT]

A property has value DEBUG in application.properties and INFO in application-prod.properties, with prod active. Which value is used in the transcript's example?

A. INFO
B. DEBUG
C. TRACE
D. No value is used

**Answer: A**

**Explanation:** Profile-specific configuration has higher priority when merged with the default configuration.

**Topic:** Profiles
**Source:** split 2 Step 09

---

### Q82. [Easy] [SINGLE CORRECT]

What annotation is recommended in the transcript for grouping many related application configuration values?

A. @ConfigurationProperties
B. @WebServlet
C. @RestController
D. @Before

**Answer: A**

**Explanation:** The transcript recommends @ConfigurationProperties for a larger set of related application properties.

**Topic:** ConfigurationProperties
**Source:** split 2 Step 10

---

### Q83. [Easy] [SINGLE CORRECT]

In the example, which prefix is assigned to the grouped currency-service configuration?

A. currency-service
B. service.currency
C. currency.config.root
D. boot.currency

**Answer: A**

**Explanation:** The demonstrated prefix is currency-service.

**Topic:** ConfigurationProperties
**Source:** split 2 Step 10

---

### Q84. [Easy] [MULTIPLE CORRECT]

Which fields are grouped under the currency-service configuration example? [Select all that apply]

A. url
B. username
C. key
D. dispatcherServletName

**Answers: A, B, C**

**Explanation:** The example defines URL, username and key as configuration properties.

**Topic:** ConfigurationProperties
**Source:** split 2 Step 10

---

### Q85. [Medium] [SINGLE CORRECT]

Why is @Component added to the CurrencyServiceConfiguration example?

A. So Spring can manage an instance of the configuration class
B. To convert it into a servlet
C. To make it a database table
D. To disable property binding

**Answer: A**

**Explanation:** The transcript says @Component is needed so Spring manages the configuration object.

**Topic:** ConfigurationProperties
**Source:** split 2 Step 10

---

### Q86. [Easy] [SINGLE CORRECT]

Where are the currency-service properties configured in the example?

A. application.properties
B. pom.xml
C. web.xml
D. build.gradle only

**Answer: A**

**Explanation:** The properties are mapped from application.properties.

**Topic:** ConfigurationProperties
**Source:** split 2 Step 10

---

### Q87. [Medium] [SINGLE CORRECT]

Which statement best explains the advantage of @ConfigurationProperties over treating each configuration value as an isolated constant?

A. It groups related external configuration into a managed object
B. It removes all configuration files
C. It turns configuration into SQL
D. It prevents different environments

**Answer: A**

**Explanation:** The transcript uses a configuration class to group multiple related service settings.

**Topic:** ConfigurationProperties
**Source:** split 2 Step 10

---

### Q88. [Easy] [SINGLE CORRECT]

In the separate external-properties example from split 1, which annotation is used to bind a property value into a field or property?

A. @Value
B. @Profile
C. @ComponentScan
D. @BeanScope

**Answer: A**

**Explanation:** The transcript demonstrates @Value with ${...} syntax for reading a property.

**Topic:** External configuration
**Source:** split 1 Step 26

---

### Q89. [Medium] [SINGLE CORRECT]

What syntax is emphasized as necessary inside @Value for a property lookup?

A. ${property.name}
B. #{property.name}
C. @property.name
D. [property.name]

**Answer: A**

**Explanation:** The transcript specifically warns that the ${...} form is required for the property lookup example.

**Topic:** External configuration
**Source:** split 1 Step 26

---

### Q90. [Medium] [SINGLE CORRECT]

Which annotation tells the example context to load app.properties from the classpath?

A. @PropertySource
B. @Component
C. @Profile
D. @EnableActuator

**Answer: A**

**Explanation:** The transcript uses @PropertySource with classpath:app.properties.

**Topic:** External configuration
**Source:** split 1 Step 26

---

### Q91. [Medium] [SINGLE CORRECT]

Why can placing an external properties file outside the application resources be useful?

A. Different environments can supply different property files without changing the application code
B. It removes the need for Java
C. It disables Spring Boot
D. It converts the file into JSON automatically

**Answer: A**

**Explanation:** The transcript describes separate Dev, QA, Stage and Production property values.

**Topic:** External configuration
**Source:** split 1 Step 26

---

### Q92. [Easy] [SINGLE CORRECT]

What server is described as Spring Boot's default embedded server in the transcript?

A. Tomcat
B. Jetty
C. Undertow
D. Apache HTTPD

**Answer: A**

**Explanation:** Tomcat is explicitly presented as the default embedded server.

**Topic:** Embedded servers
**Source:** split 2 Step 11

---

### Q93. [Easy] [SINGLE CORRECT]

Which two additional embedded servers are mentioned as supported besides Tomcat?

A. Jetty and Undertow
B. Nginx and IIS
C. Apache HTTPD and Caddy
D. GlassFish and WebLogic

**Answer: A**

**Explanation:** The transcript names Jetty and Undertow as other supported options.

**Topic:** Embedded servers
**Source:** split 2 Step 11

---

### Q94. [Medium] [SINGLE CORRECT]

What major deployment simplification is associated with an embedded server?

A. The application can be packaged as a JAR containing the server and run with Java installed
B. The application must be installed into a separate web server before it can run
C. The browser runs the server
D. The database becomes the server

**Answer: A**

**Explanation:** The transcript explains that the server is part of the JAR, so Java is sufficient to run it.

**Topic:** Embedded servers
**Source:** split 2 Step 11

---

### Q95. [Medium] [SINGLE CORRECT]

What does the transcript mean by the phrase 'make JAR not WAR' in the embedded-server context?

A. Prefer the simpler JAR-based deployment model enabled by an embedded server
B. Never use Java archive files
C. Always deploy XML instead of Java
D. Convert WAR files to CSS

**Answer: A**

**Explanation:** The phrase is used to emphasize the simplified JAR deployment model.

**Topic:** Embedded servers
**Source:** split 2 Step 11

---

### Q96. [Medium] [SINGLE CORRECT]

Which component is brought into the web application's dependency set by the web starter and used to run the application?

A. Spring Boot starter Tomcat
B. Mockito
C. JUnit
D. Spring Boot Actuator

**Answer: A**

**Explanation:** The transcript shows the web starter bringing in Spring Boot starter Tomcat.

**Topic:** Embedded servers
**Source:** split 2 Step 11

---

### Q97. [Medium] [MULTIPLE CORRECT]

Which are benefits of the embedded-server model described in the transcript? [Select all that apply]

A. Simplified deployment
B. A runnable JAR containing the server
C. Only Java is needed on the target to launch the JAR
D. Mandatory external Tomcat installation

**Answers: A, B, C**

**Explanation:** The last option contradicts the demonstrated embedded-server deployment model.

**Topic:** Embedded servers
**Source:** split 2 Step 11

---

### Q98. [Hard] [SINGLE CORRECT]

A machine has Java installed but no separately installed Tomcat. A Spring Boot JAR created with the web starter is copied to it. What does the transcript suggest?

A. The application can still be run because Tomcat is embedded in the JAR
B. It must first install Tomcat manually
C. It can only run from Eclipse
D. It cannot expose HTTP

**Answer: A**

**Explanation:** This is the deployment simplification demonstrated in the embedded-server section.

**Topic:** Embedded servers
**Source:** split 2 Step 11

---

### Q99. [Medium] [SINGLE CORRECT]

Which statement is false about the embedded servers discussed in the transcript?

A. Tomcat is unsupported by Spring Boot web starters
B. Jetty is supported
C. Undertow is supported
D. Tomcat is the default in the demonstrated setup

**Answer: A**

**Explanation:** The transcript explicitly states that Tomcat is the default and Jetty/Undertow are also supported.

**Topic:** Embedded servers
**Source:** split 2 Step 11

---

### Q100. [Easy] [SINGLE CORRECT]

What production concern does Spring Boot Actuator address in the transcript?

A. Monitoring and managing an application in production
B. Compiling TypeScript
C. Writing JPA entities
D. Creating Maven repositories

**Answer: A**

**Explanation:** Actuator is introduced as the feature for production monitoring and management.

**Topic:** Actuator
**Source:** split 2 Step 12

---

### Q101. [Easy] [SINGLE CORRECT]

Which Actuator endpoint is associated with application health?

A. /actuator/health
B. /actuator/routes
C. /actuator/jpa
D. /actuator/boot

**Answer: A**

**Explanation:** The transcript demonstrates localhost:8080/actuator/health for health information.

**Topic:** Actuator
**Source:** split 2 Step 12

---

### Q102. [Easy] [SINGLE CORRECT]

Which Actuator endpoint is associated with Spring beans?

A. beans
B. health
C. metrics
D. mappings

**Answer: A**

**Explanation:** The transcript says the beans endpoint shows Spring beans in the application.

**Topic:** Actuator
**Source:** split 2 Step 12

---

### Q103. [Easy] [SINGLE CORRECT]

Which Actuator endpoint is associated with application metrics?

A. metrics
B. beans
C. health
D. mappings

**Answer: A**

**Explanation:** Metrics are exposed through the metrics endpoint in the transcript.

**Topic:** Actuator
**Source:** split 2 Step 12

---

### Q104. [Easy] [SINGLE CORRECT]

Which Actuator endpoint is associated with request mappings?

A. mappings
B. beans
C. health
D. metrics

**Answer: A**

**Explanation:** The transcript states that the mappings endpoint provides details around configured request mappings.

**Topic:** Actuator
**Source:** split 2 Step 12

---

### Q105. [Easy] [SINGLE CORRECT]

How is Actuator added to the Maven project in the transcript?

A. By adding spring-boot-starter-actuator
B. By adding spring-boot-starter-webmvc-test only
C. By enabling it through Git
D. By replacing the parent POM

**Answer: A**

**Explanation:** The walkthrough adds the actuator starter to pom.xml.

**Topic:** Actuator
**Source:** split 2 Step 12

---

### Q106. [Medium] [SINGLE CORRECT]

What does the base /actuator response demonstrate in the transcript?

A. It exposes links to Actuator resources such as the health endpoint
B. It returns the complete database schema
C. It returns all controller source code
D. It returns Maven dependency XML

**Answer: A**

**Explanation:** The sample response contains a self link and a health link.

**Topic:** Actuator
**Source:** split 2 Step 12

---

### Q107. [Medium] [SINGLE CORRECT]

Which behavior is described as the default exposure in the transcript immediately after enabling Actuator?

A. Only the health endpoint is exposed by default
B. All endpoints are exposed automatically
C. Only metrics are exposed
D. No endpoint is exposed

**Answer: A**

**Explanation:** The transcript explicitly says that by default only the health endpoint is exposed.

**Topic:** Actuator
**Source:** split 2 Step 12

---

### Q108. [Medium] [SINGLE CORRECT]

Where does the transcript say additional Actuator features can be enabled?

A. application.properties
B. pom.xml only
C. web.xml
D. index.html

**Answer: A**

**Explanation:** The transcript says additional endpoints/features can be enabled in application.properties.

**Topic:** Actuator
**Source:** split 2 Step 12

---

### Q109. [Medium] [MULTIPLE CORRECT]

Which monitoring questions fit the purpose of Actuator described in the transcript? [Select all that apply]

A. Is the application up and running?
B. What metrics are available?
C. What Spring beans exist?
D. What request mappings are configured?

**Answers: A, B, C, D**

**Explanation:** Each concern is tied to one of the Actuator endpoints discussed.

**Topic:** Actuator
**Source:** split 2 Step 12

---

### Q110. [Easy] [SINGLE CORRECT]

A production operator wants to verify whether the application is healthy without inspecting business logic. Which endpoint from the material is most directly relevant?

A. /actuator/health
B. /actuator/beans
C. /actuator/mappings
D. /actuator/metrics

**Answer: A**

**Explanation:** Health is the endpoint specifically associated with application health.

**Topic:** Actuator
**Source:** split 2 Step 12

---

### Q111. [Easy] [SINGLE CORRECT]

A developer needs to inspect which controller routes are configured. Which Actuator resource from the transcript is most relevant?

A. mappings
B. health
C. beans
D. metrics

**Answer: A**

**Explanation:** The mappings endpoint is for request mappings.

**Topic:** Actuator
**Source:** split 2 Step 12

---

### Q112. [Medium] [MULTIPLE CORRECT]

Which statements about Actuator are correct? [Select all that apply]

A. It supports production monitoring
B. It provides multiple endpoints
C. Health is demonstrated as an endpoint
D. Its primary purpose in the transcript is automatic code restart

**Answers: A, B, C**

**Explanation:** The last statement describes DevTools instead of Actuator.

**Topic:** Actuator
**Source:** split 2 Step 12

---

### Q113. [Medium] [SINGLE CORRECT]

How does Actuator complement Spring Boot's goal of production readiness?

A. It provides operational visibility such as health and metrics
B. It removes all logging
C. It replaces Maven
D. It turns REST APIs into JSPs

**Answer: A**

**Explanation:** Operational monitoring is explicitly part of the production-ready goal.

**Topic:** Actuator
**Source:** split 2 Step 12

---

### Q114. [Easy] [SINGLE CORRECT]

According to the transcript, what is the core focus of the Spring Framework?

A. Dependency injection
B. REST routing only
C. Embedded web servers only
D. Metrics dashboards only

**Answer: A**

**Explanation:** The transcript defines the core of Spring Framework as dependency injection.

**Topic:** Spring vs Spring MVC vs Spring Boot
**Source:** split 2 Step 13

---

### Q115. [Easy] [SINGLE CORRECT]

What is Spring MVC described as?

A. A Spring module focused on web applications and REST APIs
B. A build tool
C. A database
D. A logging framework

**Answer: A**

**Explanation:** Spring MVC is presented as the web-focused Spring module.

**Topic:** Spring vs Spring MVC vs Spring Boot
**Source:** split 2 Step 13

---

### Q116. [Medium] [MULTIPLE CORRECT]

Which technologies are associated with Spring MVC in the transcript? [Select all that apply]

A. @Controller
B. @RestController
C. @RequestMapping
D. @Autowired as a web-routing annotation

**Answers: A, B, C**

**Explanation:** The first three are explicitly identified as Spring MVC annotations in the comparison; @Autowired is a Spring DI mechanism rather than a mapping annotation.

**Topic:** Spring vs Spring MVC vs Spring Boot
**Source:** split 2 Step 13

---

### Q117. [Medium] [SINGLE CORRECT]

Which Spring Boot feature directly reduces the amount of dependency listing required for a web application?

A. Starter projects
B. Actuator health
C. Profiles
D. Embedded server logs

**Answer: A**

**Explanation:** Starters are described as convenient dependency descriptors.

**Topic:** Spring vs Spring MVC vs Spring Boot
**Source:** split 2 Step 13

---

### Q118. [Easy] [SINGLE CORRECT]

Which Spring Boot feature directly reduces the amount of manual framework configuration?

A. Auto-configuration
B. Jenkins
C. JUnit
D. Entity inheritance

**Answer: A**

**Explanation:** Auto-configuration automatically provides defaults based on classpath and existing configuration.

**Topic:** Spring vs Spring MVC vs Spring Boot
**Source:** split 2 Step 13

---

### Q119. [Hard] [MULTIPLE CORRECT]

Which statements correctly distinguish the three technologies in the transcript? [Select all that apply]

A. Spring Framework focuses on dependency injection
B. Spring MVC focuses on web apps and REST APIs
C. Spring Boot focuses on making application development faster and production-ready
D. Spring Boot is described as a competitor that replaces Spring MVC

**Answers: A, B, C**

**Explanation:** The last option contradicts the transcript.

**Topic:** Spring vs Spring MVC vs Spring Boot
**Source:** split 2 Step 13

---

### Q120. [Medium] [SINGLE CORRECT]

Why does the transcript say Spring Boot was needed as the ecosystem evolved?

A. Using Spring and Spring MVC alone could require substantial repeated configuration
B. Java stopped supporting objects
C. Tomcat stopped supporting HTTP
D. Maven disappeared

**Answer: A**

**Explanation:** The transcript points to pom.xml, web.xml, applicationContext.xml, and other configuration burdens.

**Topic:** Spring vs Spring MVC vs Spring Boot
**Source:** split 2 Step 13

---

### Q121. [Hard] [SINGLE CORRECT]

Which concern is specifically associated with embedded servers in Spring Boot rather than with Spring MVC itself?

A. Simplifying application deployment through a server packaged with the application
B. Defining @Controller
C. Defining @RequestMapping
D. Writing REST business logic

**Answer: A**

**Explanation:** Embedded servers are a Spring Boot feature supporting easy deployment.

**Topic:** Spring vs Spring MVC vs Spring Boot
**Source:** split 2 Step 13

---

### Q122. [Medium] [SINGLE CORRECT]

In the database-demo setup, which combination of dependencies is explicitly selected before the application is launched?

A. JDBC, JPA, H2, and Web
B. Angular, React, Vue, and Redis
C. Only Actuator and Security
D. Only Tomcat and Jackson

**Answer: A**

**Explanation:** The transcript says JDBC, JPA, H2 and Web were chosen in the Spring Initializr setup.

**Topic:** Boot database setup
**Source:** split 2 database demo

---

### Q123. [Easy] [SINGLE CORRECT]

What is H2 described as in the database section?

A. An in-memory database
B. A web server
C. A testing framework only
D. A JSON serializer

**Answer: A**

**Explanation:** The transcript repeatedly refers to H2 as an in-memory database.

**Topic:** H2 with Spring Boot
**Source:** split 2 database demo

---

### Q124. [Hard] [SINGLE CORRECT]

Why does the H2 database become relevant to Spring Boot auto-configuration?

A. Its presence on the classpath allows Boot to detect an embedded database and configure a data source
B. H2 changes the Java compiler
C. H2 creates Actuator endpoints only
D. H2 replaces the web starter

**Answer: A**

**Explanation:** This is the auto-configuration chain described in the transcript.

**Topic:** H2 with Spring Boot
**Source:** split 2 H2 auto-configuration

---

### Q125. [Medium] [SINGLE CORRECT]

What component is described as being configured using the automatically configured data source?

A. JdbcTemplate
B. DispatcherServlet
C. ViewResolver
D. Mockito runner

**Answer: A**

**Explanation:** The transcript says JdbcTemplate is auto-configured using the auto-configured data source.

**Topic:** Boot database setup
**Source:** split 2 H2 auto-configuration

---

### Q126. [Hard] [SINGLE CORRECT]

Which sequence best reflects the H2/JDBC auto-configuration example?

A. H2 on classpath → data source auto-configured → JdbcTemplate auto-configured
B. H2 on classpath → React compiled → Git repository created
C. JPA removed → Tomcat installed → Actuator disabled
D. H2 on classpath → JSP generated → Gradle created

**Answer: A**

**Explanation:** This sequence is directly stated in the auto-configuration discussion.

**Topic:** Boot database setup
**Source:** split 2 H2 auto-configuration

---

### Q127. [Hard] [SINGLE CORRECT]

The H2 console example requires which property to be enabled in addition to relevant classpath conditions?

A. spring.h2.console.enabled=true
B. spring.h2.enabled=true
C. boot.h2.console=auto
D. h2.console.active=jsp

**Answer: A**

**Explanation:** The transcript gives the property as spring.h2.console.enabled=true.

**Topic:** H2 console
**Source:** split 2 H2 auto-configuration

---

### Q128. [Hard] [MULTIPLE CORRECT]

Which conditions are stated for H2 console auto-configuration in the transcript? [Select all that apply]

A. A web servlet class is present
B. H2 is on the classpath
C. The console-enabled property is set
D. A React component exists

**Answers: A, B, C**

**Explanation:** The first three form the demonstrated condition set; React is unrelated.

**Topic:** H2 console
**Source:** split 2 H2 auto-configuration

---

### Q129. [Medium] [SINGLE CORRECT]

What is the main educational point of running the database-demo before implementing business logic?

A. To confirm that the Spring Boot project and selected dependencies start correctly
B. To populate a production database automatically
C. To create user accounts
D. To generate a frontend

**Answer: A**

**Explanation:** The transcript runs the application simply to verify that the generated setup works.

**Topic:** Boot database setup
**Source:** split 2 database demo

---

### Q130. [Medium] [SINGLE CORRECT]

Which feature of Spring Boot makes it possible for JPA-related infrastructure to appear without explicitly wiring each component in the example?

A. Auto-configuration
B. DevTools
C. Actuator
D. Profiles

**Answer: A**

**Explanation:** The transcript attributes EntityManagerFactory and transaction manager setup to auto-configuration when JPA is present.

**Topic:** Boot database setup
**Source:** split 2 JPA auto-configuration

---

### Q131. [Easy] [MULTIPLE CORRECT]

Which database technologies are explicitly paired with Spring Boot starters in the transcript? [Select all that apply]

A. JPA
B. JDBC
C. H2 in the database-demo setup
D. FTP

**Answers: A, B, C**

**Explanation:** JPA, JDBC and H2 appear in the database setup; FTP does not.

**Topic:** Boot database setup
**Source:** split 2 database demo

---

### Q132. [Medium] [SINGLE CORRECT]

What is the purpose of CommandLineRunner in the database-demo example?

A. To run code when the Spring Boot application starts
B. To define a database schema
C. To create HTTP routes
D. To replace Actuator

**Answer: A**

**Explanation:** The transcript describes implementing CommandLineRunner so the DAO query can be fired at application startup.

**Topic:** Spring Boot startup hooks
**Source:** split 2 database demo

---

### Q133. [Easy] [SINGLE CORRECT]

Which interface is explicitly introduced as being present in Spring Boot for running logic at startup?

A. CommandLineRunner
B. RunnableHttpController
C. BootStartupServlet
D. JPAStarterRunner

**Answer: A**

**Explanation:** The transcript says CommandLineRunner is one of the interfaces present in Spring Boot and uses it for startup execution.

**Topic:** Spring Boot startup hooks
**Source:** split 2 database demo

---

### Q134. [Medium] [SINGLE CORRECT]

A developer places a database query in a CommandLineRunner-based example. When is that code intended to execute?

A. During application startup
B. Only after the first HTTP GET request
C. Only when Actuator is opened
D. Only during Maven clean

**Answer: A**

**Explanation:** The example uses CommandLineRunner to execute the DAO query at startup.

**Topic:** Spring Boot startup hooks
**Source:** split 2 database demo

---

### Q135. [Hard] [SINGLE CORRECT]

What architectural idea is illustrated by invoking a DAO from a startup runner?

A. Spring Boot can trigger application code after its context is initialized
B. DAO logic must always be inside a controller
C. Databases cannot be used with Boot
D. Runners replace repositories permanently

**Answer: A**

**Explanation:** The example shows Boot starting the application and then invoking configured application logic.

**Topic:** Spring Boot startup hooks
**Source:** split 2 database demo

---

### Q136. [Easy] [SINGLE CORRECT]

Which starter is automatically imported in the Spring Boot Mockito project described in split 1?

A. spring-boot-starter-test
B. spring-boot-starter-actuator
C. spring-boot-starter-parent
D. spring-boot-starter-security

**Answer: A**

**Explanation:** The transcript says Spring Initializr adds spring-boot-starter-test, which brings in common testing dependencies.

**Topic:** Spring Boot testing
**Source:** split 1 Step 01 Mockito

---

### Q137. [Easy] [SINGLE CORRECT]

Which testing library is specifically said to be brought in transitively by spring-boot-starter-test in the transcript?

A. Mockito
B. Tomcat
C. Jackson
D. Hibernate

**Answer: A**

**Explanation:** The transcript checks the effective POM and finds Mockito under starter-test.

**Topic:** Spring Boot testing
**Source:** split 1 Step 01 Mockito

---

### Q138. [Medium] [SINGLE CORRECT]

Why is spring-boot-starter-test useful in the described setup?

A. It brings together dependencies typically used for unit testing with Spring Boot
B. It creates the embedded Tomcat server
C. It replaces the parent POM
D. It activates production profiles

**Answer: A**

**Explanation:** The transcript describes it as bringing in the dependencies typically used for unit tests.

**Topic:** Spring Boot testing
**Source:** split 1 Step 01 Mockito

---

### Q139. [Medium] [MULTIPLE CORRECT]

Which statement about the Spring Boot testing setup is correct? [Select all that apply]

A. Spring Initializr can add spring-boot-starter-test
B. Mockito is found through the effective POM
C. Test code is kept separately from production code in src/test/java
D. The starter is only used to expose Actuator metrics

**Answers: A, B, C**

**Explanation:** The material supports the first three statements and does not associate starter-test with Actuator.

**Topic:** Spring Boot testing
**Source:** split 1 Steps 01/Unit Testing

---

### Q140. [Medium] [SINGLE CORRECT]

A learner wants a pure Mockito unit test for business logic. What does the transcript recommend about loading the Spring context?

A. Avoid loading the full Spring context when it is unnecessary
B. Always load the entire context
C. Replace Mockito with Actuator
D. Use only XML configuration

**Answer: A**

**Explanation:** The transcript says Mockito tests are faster and should avoid Spring context where possible.

**Topic:** Spring Boot testing
**Source:** split 1 Mockito section

---

### Q141. [Hard] [SINGLE CORRECT]

Which statement best distinguishes the Spring Boot starter-test dependency from the Spring Boot TestContext setup shown elsewhere?

A. Starter-test supplies test dependencies, while a Spring context test may load application configuration
B. They are the exact same mechanism
C. Starter-test is a server, TestContext is a database
D. Starter-test only supports production monitoring

**Answer: A**

**Explanation:** The transcript presents both dependency provisioning and context-based testing as separate concerns.

**Topic:** Spring Boot testing
**Source:** split 1 Unit Testing

---

### Q142. [Medium] [SINGLE CORRECT]

What is the role of spring-boot-starter-parent in the Maven/Spring Boot pairing described in split 3?

A. It is the parent POM used by almost all Spring Boot projects in the example and helps manage dependency versions
B. It launches Actuator endpoints
C. It replaces the JDK
D. It creates database tables

**Answer: A**

**Explanation:** The transcript calls it the parent POM and explains that version management is inherited.

**Topic:** Spring Boot Maven integration
**Source:** split 3 Step 09

---

### Q143. [Medium] [SINGLE CORRECT]

Which parent is described as the parent of spring-boot-starter-parent?

A. Spring Boot Dependencies
B. Spring MVC Parent
C. Maven Test Parent
D. Tomcat Parent

**Answer: A**

**Explanation:** The transcript traces spring-boot-starter-parent upward to Spring Boot Dependencies.

**Topic:** Spring Boot Maven integration
**Source:** split 3 Step 09

---

### Q144. [Medium] [SINGLE CORRECT]

What practical benefit does the Boot parent hierarchy provide to a project's dependencies?

A. Common dependency versions can be inherited so individual versions need not always be written
B. Every dependency becomes optional
C. All dependencies are removed
D. Only Java 8 is permitted

**Answer: A**

**Explanation:** The transcript says versions are managed centrally by the parent/dependencies POM.

**Topic:** Spring Boot Maven integration
**Source:** split 3 Step 09

---

### Q145. [Hard] [SINGLE CORRECT]

A pom.xml contains a Spring Boot starter dependency but no explicit version. Which explanation matches the transcript?

A. The version can be inherited from the Spring Boot parent/dependency-management hierarchy
B. Maven invents a random version
C. Tomcat supplies the version
D. Actuator chooses the version at runtime

**Answer: A**

**Explanation:** The transcript explicitly demonstrates version inheritance from the parent POM.

**Topic:** Spring Boot Maven integration
**Source:** split 3 Step 09

---

### Q146. [Easy] [SINGLE CORRECT]

Which Maven plugin is highlighted as making it easy to run Spring Boot applications?

A. Spring Boot Maven Plugin
B. Maven Clean Plugin
C. Tomcat Compiler Plugin
D. JUnit Runner Plugin

**Answer: A**

**Explanation:** The Spring Boot Maven Plugin is introduced for convenient application execution and image building.

**Topic:** Spring Boot Maven integration
**Source:** split 3 Step 09

---

### Q147. [Easy] [SINGLE CORRECT]

Which command is demonstrated for running a Spring Boot application through the Maven plugin?

A. mvn spring-boot:run
B. mvn boot:start-web.xml
C. mvn actuator:health
D. mvn spring:tomcat

**Answer: A**

**Explanation:** The transcript explicitly runs spring-boot:run through Maven.

**Topic:** Spring Boot Maven integration
**Source:** split 3 Step 09

---

### Q148. [Medium] [SINGLE CORRECT]

Which additional task is mentioned as possible with the Spring Boot Maven Plugin?

A. Build a container image for the Spring Boot application
B. Create CSS sprites
C. Run browser JavaScript
D. Generate SQL tables from HTML

**Answer: A**

**Explanation:** The transcript says the plugin can also be used to build container images.

**Topic:** Spring Boot Maven integration
**Source:** split 3 Step 09

---

### Q149. [Medium] [MULTIPLE CORRECT]

Which statements about the Spring Boot Maven pairing are correct? [Select all that apply]

A. Starters provide convenient dependency sets
B. The parent POM manages dependency versions
C. The Spring Boot Maven Plugin can run the application
D. Maven cannot be used with Spring Boot

**Answers: A, B, C**

**Explanation:** The transcript explicitly presents Maven and Spring Boot as a strong pairing.

**Topic:** Spring Boot Maven integration
**Source:** split 3 Step 09

---

### Q150. [Medium] [SINGLE CORRECT]

What does a starter prevent the developer from having to do manually in the Maven example?

A. List every transitive library needed for a feature
B. Write every controller method
C. Create every database table
D. Write every test case

**Answer: A**

**Explanation:** The starter bundles the related dependencies so they can be brought in through one dependency descriptor.

**Topic:** Spring Boot Maven integration
**Source:** split 3 Step 09

---

### Q151. [Hard] [MULTIPLE CORRECT]

Which dependency set is explicitly used as an example for Spring Boot Web MVC starter composition? [Select all that apply]

A. Spring Boot starter components
B. Jackson
C. Tomcat
D. HTTP converter / Web MVC framework

**Answers: A, B, C, D**

**Explanation:** The transcript describes the web starter as containing the related components needed for Web MVC.

**Topic:** Spring Boot Maven integration
**Source:** split 3 Step 09

---

### Q152. [Medium] [SINGLE CORRECT]

What is the practical effect of inheriting dependency versions from Spring Boot Dependencies?

A. The project's pom.xml can omit many explicit dependency version numbers
B. The project cannot add new dependencies
C. Maven stops resolving transitive dependencies
D. Only starter versions are changed at runtime

**Answer: A**

**Explanation:** The transcript explains that versions are centrally managed and inherited.

**Topic:** Spring Boot Maven integration
**Source:** split 3 Step 09

---

### Q153. [Easy] [SINGLE CORRECT]

Which Gradle DSL is selected in the Spring Boot Gradle project setup shown in the transcript?

A. Gradle Groovy
B. Gradle XML
C. Maven XML
D. Ant Groovy only

**Answer: A**

**Explanation:** The Spring Initializr Gradle example selects Gradle Groovy.

**Topic:** Spring Boot with Gradle
**Source:** split 3 Step 02

---

### Q154. [Medium] [SINGLE CORRECT]

In the Gradle Spring Boot project creation example, which language remains selected?

A. Java
B. Kotlin
C. Groovy
D. Scala

**Answer: A**

**Explanation:** The project uses Gradle Groovy as the build tool DSL but keeps Java as the application language.

**Topic:** Spring Boot with Gradle
**Source:** split 3 Step 02

---

### Q155. [Easy] [SINGLE CORRECT]

Which configuration choice is shown for the Gradle Spring Boot project?

A. Properties
B. XML only
C. JSON only
D. YAML only

**Answer: A**

**Explanation:** The example selects properties as the configuration format.

**Topic:** Spring Boot with Gradle
**Source:** split 3 Step 02

---

### Q156. [Easy] [SINGLE CORRECT]

Which packaging choice is shown for the Gradle Spring Boot project?

A. Jar
B. War only
C. Ear
D. Zip-only executable

**Answer: A**

**Explanation:** The Gradle example uses Jar packaging.

**Topic:** Spring Boot with Gradle
**Source:** split 3 Step 02

---

### Q157. [Easy] [SINGLE CORRECT]

Which dependency is added to the Gradle Spring Boot example to build web and REST applications?

A. Spring Web
B. Spring Security only
C. Spring Data JPA only
D. Actuator only

**Answer: A**

**Explanation:** The example adds Spring Web for web applications including RESTful applications using Spring MVC.

**Topic:** Spring Boot with Gradle
**Source:** split 3 Step 02

---

### Q158. [Medium] [SINGLE CORRECT]

Which project layout does the transcript say Gradle inherits from Maven?

A. src/main/java, src/main/resources, src/test/java, and src/test/resources
B. web/, scripts/, templates/, dist/
C. bin/, lib/, classes/, docs/
D. src/java only and test/

**Answer: A**

**Explanation:** The transcript explicitly says Gradle inherits the project layout from Maven.

**Topic:** Spring Boot with Gradle
**Source:** split 3 Step 01

---

### Q159. [Medium] [MULTIPLE CORRECT]

Which statements about the Gradle Spring Boot project are correct? [Select all that apply]

A. Spring Initializr can generate the project
B. The example uses Gradle Groovy
C. Spring Web is added for web/REST functionality
D. The project cannot use embedded Tomcat

**Answers: A, B, C**

**Explanation:** The fourth statement contradicts the transcript, which says Spring Web uses Apache Tomcat as the default embedded container.

**Topic:** Spring Boot with Gradle
**Source:** split 3 Step 02

---

### Q160. [Hard] [SINGLE CORRECT]

A learner imports a Gradle Spring Boot project into Eclipse. Which issue is actually described in the transcript?

A. The IDE may initially show a Java build-path/JDK resolution problem
B. Actuator refuses to start
C. Tomcat changes to Jetty automatically
D. The project becomes a Maven project

**Answer: A**

**Explanation:** The transcript shows an Eclipse error around java.lang.Object and then configures the build path.

**Topic:** Spring Boot with Gradle
**Source:** split 3 Step 02

---

### Q161. [Medium] [SINGLE CORRECT]

What does spring-boot-starter-webmvc conceptually provide in the split 3 Maven discussion?

A. A bundled set of web-related dependencies needed for a Spring Boot web application
B. Only the JDK
C. Only the database driver
D. Only JUnit

**Answer: A**

**Explanation:** The transcript describes the starter as bringing together Spring Boot starter components, Jackson, Tomcat, converters and Web MVC.

**Topic:** Spring Boot starter composition
**Source:** split 3 Step 09

---

### Q162. [Medium] [SINGLE CORRECT]

Why can a developer use a single Spring Boot web starter instead of listing Tomcat and related web dependencies one by one?

A. The starter already describes and brings the related dependency set
B. Maven ignores all transitive dependencies
C. Tomcat is part of Java SE
D. Jackson is supplied by the browser

**Answer: A**

**Explanation:** This is the convenience the transcript attributes to starter dependencies.

**Topic:** Spring Boot starter composition
**Source:** split 3 Step 09

---

### Q163. [Hard] [SINGLE CORRECT]

Which hierarchy is shown for dependency-version management?

A. Project POM → Spring Boot Starter Parent → Spring Boot Dependencies
B. Project POM → Actuator → JUnit → Tomcat
C. Project POM → JSP → Spring MVC
D. Project POM → H2 → browser

**Answer: A**

**Explanation:** The transcript traces the parent chain through Spring Boot Starter Parent to Spring Boot Dependencies.

**Topic:** Spring Boot Maven integration
**Source:** split 3 Step 09

---

### Q164. [Medium] [SINGLE CORRECT]

Which statement about Spring Boot Starter Parent is NOT supported by the transcript?

A. It is a browser library for rendering React components
B. It acts as a parent POM
C. It helps manage dependency versions
D. It is used in almost all Spring Boot projects in the example

**Answer: A**

**Explanation:** The parent POM is a Maven configuration mechanism, not a browser library.

**Topic:** Spring Boot Maven integration
**Source:** split 3 Step 09

---

### Q165. [Hard] [SINGLE CORRECT]

Which statement best explains why starter dependencies and parent dependency management solve different problems?

A. Starters group related libraries, while the parent hierarchy supplies consistent versions for dependencies
B. Both only configure Actuator
C. Both replace the Java compiler
D. One is a database and the other a server

**Answer: A**

**Explanation:** The transcript discusses starters and parent version management as separate but complementary concepts.

**Topic:** Spring Boot Maven integration
**Source:** split 3 Step 09

---

### Q166. [Hard] [SINGLE CORRECT]

When the transcript removes Spring Boot from a simple application, which automatic behavior is lost and must be configured manually?

A. Component scanning for the application package
B. The Java language
C. The ability to declare classes
D. The existence of interfaces

**Answer: A**

**Explanation:** The transcript says Spring Boot automatically defines a component scan, while plain Spring requires it to be specified.

**Topic:** Spring Boot vs plain Spring
**Source:** split 1 Step 19

---

### Q167. [Medium] [SINGLE CORRECT]

What happens to SpringApplication when the example is changed to plain Spring without Spring Boot?

A. It is removed because SpringApplication is a Spring Boot class
B. It becomes a JDBC template
C. It becomes an Actuator endpoint
D. It becomes a Maven plugin

**Answer: A**

**Explanation:** The transcript explicitly removes SpringApplication when eliminating Boot.

**Topic:** Spring Boot vs plain Spring
**Source:** split 1 Step 19

---

### Q168. [Hard] [SINGLE CORRECT]

Which class is used in the plain-Spring example to create the application context after Spring Boot is removed?

A. AnnotationConfigApplicationContext
B. SpringApplication
C. DispatcherServletBuilder
D. ActuatorContext

**Answer: A**

**Explanation:** The transcript switches from SpringApplication to AnnotationConfigApplicationContext.

**Topic:** Spring Boot vs plain Spring
**Source:** split 1 Step 19

---

### Q169. [Medium] [SINGLE CORRECT]

What must be added explicitly in the plain-Spring example because Spring Boot had been providing it automatically?

A. @ComponentScan
B. spring-boot-starter-webmvc
C. Actuator
D. DevTools

**Answer: A**

**Explanation:** The transcript says Boot automatically defines component scan on the package containing the configuration, whereas plain Spring needs it declared.

**Topic:** Spring Boot vs plain Spring
**Source:** split 1 Step 19

---

### Q170. [Hard] [MULTIPLE CORRECT]

Which statements describe things Spring Boot is shown to provide by default for the example? [Select all that apply]

A. Component scanning around the application's package
B. SpringApplication-based startup
C. Embedded server behavior for the web application
D. A database schema for every entity without configuration

**Answers: A, B, C**

**Explanation:** The transcript shows the first three as Boot functionality; it does not claim Boot creates every database schema automatically.

**Topic:** Spring Boot vs plain Spring
**Source:** split 1 Steps 19/13

---

### Q171. [Medium] [SINGLE CORRECT]

A service URL must differ between Dev and Production. Which strategy is explicitly supported by the transcripts?

A. Externalize the value and provide environment-specific configuration
B. Hard-code one URL in a controller
C. Store the URL in CSS
D. Put the URL in a Java enum and never change it

**Answer: A**

**Explanation:** Both split 1 and split 2 explain externalized configuration and environment-specific values.

**Topic:** External configuration
**Source:** split 1 Step 26 / split 2 Step 09

---

### Q172. [Medium] [SINGLE CORRECT]

Which configuration strategy best matches the transcript's use of application.properties plus application-prod.properties?

A. Keep defaults in application.properties and override selected values in the active profile
B. Duplicate all Java source for each environment
C. Remove default properties whenever a profile exists
D. Store configuration in the database only

**Answer: A**

**Explanation:** The profile example merges default and profile-specific values with profile values taking priority.

**Topic:** Profiles
**Source:** split 2 Step 09

---

### Q173. [Medium] [SINGLE CORRECT]

A developer wants a grouped configuration object for URL, username, and key rather than many separate @Value fields. Which material-specific approach is preferred?

A. @ConfigurationProperties
B. @WebServlet
C. @RequestMapping
D. @ComponentScan

**Answer: A**

**Explanation:** The transcript recommends @ConfigurationProperties for multiple related settings.

**Topic:** ConfigurationProperties
**Source:** split 2 Step 10

---

### Q174. [Hard] [MULTIPLE CORRECT]

A Spring Boot web application has Spring Web on the classpath, an embedded H2 database, and the H2 console enable property. Which combined outcome is most consistent with the transcript? [Select all that apply]

A. A DispatcherServlet can be auto-configured
B. Tomcat can be auto-configured as the embedded server
C. A data source can be auto-configured for H2
D. The H2 console auto-configuration can match its conditions

**Answers: A, B, C, D**

**Explanation:** The transcript gives each of these as examples of conditional or related auto-configuration.

**Topic:** Integrated Boot auto-configuration
**Source:** split 2 Steps 07/11/H2

---

### Q175. [Hard] [SINGLE CORRECT]

A team removes the explicit Tomcat installation step from its deployment runbook because the application is packaged as a Spring Boot JAR using the web starter. Why is that consistent with the material?

A. Tomcat is included through the embedded-server dependency chain in the application
B. Tomcat is no longer needed because HTTP was removed
C. Spring Boot sends requests directly to Java without a server
D. Actuator becomes the web server

**Answer: A**

**Explanation:** The transcript says Spring Boot's web starter brings in starter Tomcat, which is part of the JAR.

**Topic:** Integrated Boot deployment
**Source:** split 2 Step 11

---

### Q176. [Hard] [SINGLE CORRECT]

A developer changes a controller class and expects fast feedback, but changes to pom.xml still require ordinary dependency processing. Which pairing best explains the behavior?

A. DevTools handles application code changes; pom.xml changes are a stated limitation
B. Actuator handles Java changes; Maven handles health
C. Profiles handle code recompilation; Tomcat handles dependencies
D. Starters hot-reload POM changes

**Answer: A**

**Explanation:** That is the exact limitation and purpose combination described in the DevTools section.

**Topic:** Integrated DevTools/Maven
**Source:** split 2 Step 08

---

### Q177. [Medium] [SINGLE CORRECT]

A production deployment needs a health check, metrics, and request-mapping visibility. Which Spring Boot feature should be added rather than relying on DevTools?

A. Spring Boot Actuator
B. Spring Boot DevTools
C. Spring Initializr only
D. Spring Boot Starter Parent

**Answer: A**

**Explanation:** Actuator is the production-monitoring feature; DevTools is for development productivity.

**Topic:** Integrated production readiness
**Source:** split 2 Steps 08/12

---

### Q178. [Hard] [MULTIPLE CORRECT]

A Maven POM omits the version of a Spring Boot-managed library, yet Maven resolves a consistent version. Which two transcript concepts explain this most directly? [Select all that apply]

A. Spring Boot Starter Parent
B. Spring Boot Dependencies
C. DevTools automatic restart
D. Actuator health endpoint

**Answers: A, B**

**Explanation:** The parent hierarchy leads to centralized dependency version management.

**Topic:** Integrated Maven version management
**Source:** split 3 Step 09

---

### Q179. [Hard] [SINGLE CORRECT]

An application needs different logging in development and production, grouped service settings, and production health monitoring. Which combination of Spring Boot features best matches the material?

A. Profiles + @ConfigurationProperties + Actuator
B. DevTools + JUnit + Tomcat only
C. Spring MVC + JSP + Maven Clean
D. H2 + React + TypeScript

**Answer: A**

**Explanation:** Profiles address environment differences, ConfigurationProperties groups configuration, and Actuator handles monitoring.

**Topic:** Integrated configuration/operations
**Source:** split 2 Steps 09/10/12

---

### Q180. [Hard] [SINGLE CORRECT]

Which sequence best represents the Spring Boot development-to-production concepts emphasized across the transcripts?

A. Initializr → starters → auto-configuration → DevTools during development → profiles/configuration → embedded deployment → Actuator monitoring
B. Actuator → CSS → JUnit → HTML → Maven deletion
C. Tomcat → React → JSP → H2 → Git only
D. Maven Clean → browser → servlet → Python

**Answer: A**

**Explanation:** This sequence synthesizes the order and roles of the Spring Boot features covered in the source.

**Topic:** Integrated Spring Boot lifecycle concepts
**Source:** split 2 Steps 03-14

---

### Q181. [Hard] [SINGLE CORRECT]

A learner claims that adding the correct starter is sufficient because all configuration is then complete. Which response matches the transcript?

A. Incorrect: starters provide dependencies; auto-configuration/configuration is a separate part of the Boot mechanism
B. Correct: starters always configure every application setting
C. Correct: configuration files are ignored
D. Incorrect only because Maven is not supported

**Answer: A**

**Explanation:** The transcript explicitly asks whether having the right dependencies is sufficient and answers no: configuration is also needed.

**Topic:** Starters vs auto-configuration
**Source:** split 2 Step 06/07

---

### Q182. [Medium] [MULTIPLE CORRECT]

Which integrated statements are correct according to the transcripts? [Select all that apply]

A. Spring Boot can automatically configure an embedded servlet container for a web application
B. Spring Boot can automatically configure a data source when an embedded database is present
C. Spring Boot can use profiles for environment-specific settings
D. Actuator is introduced as a production monitoring feature

**Answers: A, B, C, D**

**Explanation:** All four statements are directly supported by the Spring Boot material.

**Topic:** Integrated Spring Boot
**Source:** split 2

---

### Q183. [Hard] [SINGLE CORRECT]

A Spring Boot application returns a Java list from a controller and the client receives JSON without explicit conversion code in the controller. Which source explanation is most relevant?

A. Boot's web auto-configuration includes Jackson-based message conversion
B. Profiles converted the list to JSON
C. Actuator serialized the list
D. Maven's parent POM serialized the list

**Answer: A**

**Explanation:** The transcript attributes automatic Bean/list-to-JSON conversion to Jackson message conversion under Boot auto-configuration.

**Topic:** Integrated web auto-configuration
**Source:** split 2 Step 07

---

### Q184. [Medium] [SINGLE CORRECT]

In the Spring Boot Level 4 binary-search example, what is the instructional purpose of starting with a tightly coupled sorting dependency?

A. To illustrate why direct dependency creation makes changing algorithms harder
B. To benchmark Tomcat
C. To configure Actuator
D. To choose a database

**Answer: A**

**Explanation:** The example uses Spring Boot as the setting for demonstrating tight versus loose coupling and dependency injection.

**Topic:** Boot-context dependency injection example
**Source:** split 1 Step 2

---

### Q185. [Medium] [SINGLE CORRECT]

What change makes the binary-search example more loosely coupled before Spring manages the dependency?

A. Passing the sorting algorithm into the binary-search component rather than hard-coding it
B. Moving the algorithm into HTML
C. Adding Actuator
D. Changing the port to 8080

**Answer: A**

**Explanation:** The transcript's goal is to remove direct instantiation and allow a sort algorithm to be supplied.

**Topic:** Boot-context dependency injection example
**Source:** split 1 Step 3

---

### Q186. [Easy] [SINGLE CORRECT]

What annotation is used in the binary-search example to indicate a dependency that Spring should populate?

A. @Autowired
B. @RequestMapping
C. @Actuator
D. @Profile

**Answer: A**

**Explanation:** The transcript uses @Autowired for the dependency relationship.

**Topic:** Spring Boot dependency injection
**Source:** split 1 Step 4

---

### Q187. [Medium] [SINGLE CORRECT]

Which startup class is used in the Spring Boot example to obtain the application context?

A. The Spring Boot application class using SpringApplication
B. The JSP file
C. The POM parent
D. The Actuator endpoint

**Answer: A**

**Explanation:** The transcript explains that running the Spring Boot application class obtains an ApplicationContext.

**Topic:** Spring Boot application context
**Source:** split 1 Step 4

---

### Q188. [Medium] [SINGLE CORRECT]

What package region does Spring Boot automatically scan in the demonstrated example?

A. The package where the main application class is present
B. Only src/test/java
C. Only WEB-INF
D. Only the Maven repository

**Answer: A**

**Explanation:** The transcript says Spring Boot automatically scans the package where the main application class is present.

**Topic:** Spring Boot component scan
**Source:** split 1 Step 4

---

### Q189. [Medium] [SINGLE CORRECT]

Which benefit of Boot's automatic component scanning is demonstrated?

A. The developer does not have to manually specify a component scan for the main application package
B. The developer no longer needs classes
C. Maven is unnecessary
D. Actuator is automatically exposed

**Answer: A**

**Explanation:** This is one of the things explicitly contrasted with plain Spring in split 1.

**Topic:** Spring Boot component scan
**Source:** split 1 Steps 4/19

---

### Q190. [Hard] [MULTIPLE CORRECT]

Which statement about Spring Boot in the Level 4 example is supported? [Select all that apply]

A. It can create and manage the application context
B. It can scan the application package for components
C. It helps assemble dependencies
D. It requires the developer to instantiate every component manually

**Answers: A, B, C**

**Explanation:** The first three describe the Boot/Spring behavior; the fourth is the opposite of dependency injection.

**Topic:** Spring Boot dependency injection
**Source:** split 1 Steps 4/5

---

### Q191. [Easy] [SINGLE CORRECT]

Which feature would you choose for a question like 'Which beans exist in the running application?' based on the transcript?

A. Actuator beans endpoint
B. DevTools restart
C. Profiles
D. Spring Boot Maven Plugin

**Answer: A**

**Explanation:** The beans endpoint is explicitly described as showing Spring beans.

**Topic:** Actuator
**Source:** split 2 Step 12

---

### Q192. [Medium] [SINGLE CORRECT]

Which feature would you choose for a question like 'Why did this auto-configuration not apply?'?

A. The auto-configuration report and its negative matches
B. The health endpoint
C. DevTools
D. The starter parent

**Answer: A**

**Explanation:** The debug report exposes positive and negative auto-configuration matches.

**Topic:** Auto-configuration
**Source:** split 2 Step 07

---

### Q193. [Easy] [SINGLE CORRECT]

Which feature would you choose for a question like 'How can Dev and Prod use different logging levels?'?

A. Profiles
B. Actuator
C. Starter Parent
D. Tomcat

**Answer: A**

**Explanation:** The profile example explicitly uses different logging levels for different environments.

**Topic:** Profiles
**Source:** split 2 Step 09

---

### Q194. [Easy] [SINGLE CORRECT]

Which feature would you choose for a question like 'How can several service settings be grouped into one configuration object?'?

A. @ConfigurationProperties
B. @WebServlet
C. Actuator
D. DevTools

**Answer: A**

**Explanation:** The transcript's currency-service example uses @ConfigurationProperties.

**Topic:** ConfigurationProperties
**Source:** split 2 Step 10

---

### Q195. [Easy] [SINGLE CORRECT]

Which feature would you choose for a question like 'How can the application run on a machine without separately installing Tomcat?'?

A. Embedded server deployment
B. Profiles
C. Actuator
D. SpringRunner

**Answer: A**

**Explanation:** The application JAR includes the embedded server in the demonstrated deployment model.

**Topic:** Embedded servers
**Source:** split 2 Step 11

---

### Q196. [Medium] [MULTIPLE CORRECT]

Which items in the transcript are explicitly associated with the Spring Boot 'build quickly' side of its goal? [Select all that apply]

A. Spring Initializr
B. Starter projects
C. Auto-configuration
D. DevTools

**Answers: A, B, C, D**

**Explanation:** All four are listed as features that help with fast application development.

**Topic:** Spring Boot goals
**Source:** split 2 Step 05

---

### Q197. [Medium] [MULTIPLE CORRECT]

Which items are explicitly associated with the 'production-ready' side of Spring Boot's goal? [Select all that apply]

A. Logging
B. Profiles
C. Configuration properties
D. Actuator

**Answers: A, B, C, D**

**Explanation:** All four are listed in the transcript as production-readiness features.

**Topic:** Spring Boot goals
**Source:** split 2 Step 05

---

### Q198. [Medium] [MULTIPLE CORRECT]

Which statements about Spring Boot web auto-configuration are supported? [Select all that apply]

A. Tomcat can be auto-configured
B. Default error pages can be auto-configured
C. JSON conversion can be auto-configured
D. DispatcherServlet can be auto-configured

**Answers: A, B, C, D**

**Explanation:** The web auto-configuration walkthrough names all four outcomes.

**Topic:** Auto-configuration
**Source:** split 2 Step 07

---

### Q199. [Easy] [MULTIPLE CORRECT]

Which facts about Actuator endpoint roles are correct? [Select all that apply]

A. beans → Spring beans
B. health → application health
C. metrics → application metrics
D. mappings → configured request mappings

**Answers: A, B, C, D**

**Explanation:** Each mapping is explicitly described in the transcript.

**Topic:** Actuator
**Source:** split 2 Step 12

---

### Q200. [Medium] [MULTIPLE CORRECT]

Which statements about embedded servers are correct? [Select all that apply]

A. Tomcat is the default in the demonstrated setup
B. Jetty is supported
C. Undertow is supported
D. The server can be packaged inside the JAR

**Answers: A, B, C, D**

**Explanation:** All four are directly supported.

**Topic:** Embedded servers
**Source:** split 2 Step 11

---

### Q201. [Hard] [MULTIPLE CORRECT]

Which statements about profiles in the logging example are correct? [Select all that apply]

A. application.properties provides defaults
B. application-prod.properties supplies profile-specific values
C. spring.profiles.active selects the profile
D. Profile-specific values have higher priority in the example

**Answers: A, B, C, D**

**Explanation:** These are the exact mechanics demonstrated.

**Topic:** Profiles
**Source:** split 2 Step 09

---

### Q202. [Medium] [SINGLE CORRECT]

In the newer Spring Boot 4 example, which old starter name might a learner still encounter in older course material?

A. spring-boot-starter-web
B. spring-boot-starter-data-jpa
C. spring-boot-starter-actuator
D. spring-boot-starter-security

**Answer: A**

**Explanation:** The transcript warns that older material may show spring-boot-starter-web.

**Topic:** Spring Boot version-specific starters
**Source:** split 2 Step 03

---

### Q203. [Medium] [SINGLE CORRECT]

Which old testing starter name is contrasted with the Boot 4 webmvc test starter?

A. spring-boot-starter-test
B. spring-boot-test-runner
C. spring-test-parent
D. spring-boot-unit-test-webmvc

**Answer: A**

**Explanation:** The transcript says earlier Boot versions might show spring-boot-starter-test.

**Topic:** Spring Boot version-specific starters
**Source:** split 2 Step 03

---

### Q204. [Medium] [SINGLE CORRECT]

Why does the transcript warn learners about older starter names?

A. Older course code may use older starter naming and should not be confused with the newer names
B. Older starters are always invalid in every version
C. Starter names are unrelated to dependencies
D. The IDE translates them automatically

**Answer: A**

**Explanation:** This warning is specifically intended to prevent confusion when seeing earlier examples.

**Topic:** Spring Boot version-specific starters
**Source:** split 2 Step 03

---

### Q205. [Hard] [SINGLE CORRECT]

Suppose a Spring Boot application has Spring Web on the classpath but a developer also provides custom configuration for the web setup. What does the transcript suggest?

A. Boot's defaults can be overridden by the application's provided configuration
B. Boot ignores custom configuration
C. The starter is removed automatically
D. Actuator blocks startup

**Answer: A**

**Explanation:** The transcript explicitly states that default auto-configuration can be overridden.

**Topic:** Auto-configuration override
**Source:** split 2 Step 07

---

### Q206. [Hard] [SINGLE CORRECT]

A project has H2 but no web servlet class and the H2-console enable property is true. Based strictly on the transcript's H2-console example, which condition is missing?

A. The web servlet condition
B. The JPA entity condition
C. The Actuator health condition
D. The Maven parent condition

**Answer: A**

**Explanation:** The example says H2 console auto-configuration checks for a web servlet class in addition to H2 and the enabling property.

**Topic:** H2 console auto-configuration
**Source:** split 2 H2 auto-configuration

---

### Q207. [Hard] [SINGLE CORRECT]

A project has Spring Web and H2, and data source auto-configuration occurs. Which additional component is described as being auto-configured using that data source?

A. JdbcTemplate
B. JSP ViewResolver
C. MockMvc runner
D. Gradle task

**Answer: A**

**Explanation:** The transcript explicitly states that JdbcTemplate is auto-configured from the configured data source.

**Topic:** JDBC auto-configuration
**Source:** split 2 H2 auto-configuration

---

### Q208. [Medium] [SINGLE CORRECT]

A team wants operational monitoring but not automatic development restarts. Which Spring Boot feature should they focus on?

A. Actuator
B. DevTools
C. Starter Parent
D. Initializr

**Answer: A**

**Explanation:** Actuator is for production monitoring; DevTools is for development productivity.

**Topic:** Actuator vs DevTools
**Source:** split 2 Steps 08/12

---

### Q209. [Easy] [SINGLE CORRECT]

A team wants automatic source-change restarts but does not need production metrics. Which feature is the closest fit?

A. DevTools
B. Actuator
C. Profiles
D. Starter Parent

**Answer: A**

**Explanation:** DevTools is specifically presented as improving development productivity through automatic restarts.

**Topic:** Actuator vs DevTools
**Source:** split 2 Steps 08/12

---

### Q210. [Medium] [SINGLE CORRECT]

Which property file is treated as the baseline when a profile such as prod is active?

A. application.properties
B. application-prod.properties only
C. pom.xml
D. application-context.xml

**Answer: A**

**Explanation:** The transcript says the active profile values are merged with the defaults from application.properties.

**Topic:** Profiles
**Source:** split 2 Step 09

---

### Q211. [Medium] [SINGLE CORRECT]

What is the purpose of keeping configuration outside Java source according to the transcript?

A. To allow values such as service URLs to vary without rewriting application logic
B. To prevent the JVM from starting
C. To make HTML faster
D. To remove Maven dependencies

**Answer: A**

**Explanation:** Externalization is presented as a way to vary environment-specific values such as external-service URLs.

**Topic:** External configuration
**Source:** split 1 Step 26

---

### Q212. [Medium] [SINGLE CORRECT]

Which annotation-based mechanism is shown in split 1 for loading a custom app.properties file?

A. @PropertySource with a classpath location
B. @Autowired with a URL
C. @Profile with a file path
D. @WebServlet with a property name

**Answer: A**

**Explanation:** The example uses @PropertySource and classpath:app.properties.

**Topic:** External configuration
**Source:** split 1 Step 26

---

### Q213. [Medium] [SINGLE CORRECT]

Which annotation is used on the external-service class in split 1 so Spring can create and manage it?

A. @Component
B. @ConfigurationProperties only
C. @RequestParam
D. @Actuator

**Answer: A**

**Explanation:** The transcript adds @Component after the bean is initially missing.

**Topic:** External configuration
**Source:** split 1 Step 26

---

### Q214. [Hard] [SINGLE CORRECT]

What is the main reason the transcript gives for using JSP instead of printing lots of HTML from a servlet, and how does this relate to Spring Boot?

A. JSP makes dynamic HTML easier, while Spring Boot later simplifies the broader application setup around Spring technologies
B. JSP replaces Maven
C. Spring Boot compiles JSP into CSS
D. JSP provides Actuator metrics

**Answer: A**

**Explanation:** This is an integrated source distinction; the material separates presentation convenience from Boot's application setup role.

**Topic:** Spring Boot ecosystem context
**Source:** split 3 Servlets / split 2

---

### Q215. [Easy] [SINGLE CORRECT]

Which source file location is presented for application.properties in the Spring Boot project?

A. src/main/resources
B. src/main/java
C. src/test/java
D. WEB-INF/classes only

**Answer: A**

**Explanation:** The transcript shows application.properties under source main resources.

**Topic:** Boot project structure
**Source:** split 2 database demo

---

### Q216. [Medium] [SINGLE CORRECT]

A developer searches the debug log for 'configuration report'. What kind of information are they seeking?

A. Why Spring Boot's auto-configuration matched or did not match certain configurations
B. Which user logged in last
C. Which CSS rule won
D. Which Git branch is checked out

**Answer: A**

**Explanation:** The report provides matching and negative-match information for auto-configuration decisions.

**Topic:** Auto-configuration
**Source:** split 2 H2/auto-config

---

### Q217. [Hard] [SINGLE CORRECT]

Which statement about Spring Boot's automatic web setup is the most specific to the transcript?

A. The web starter can lead to an embedded servlet container, DispatcherServlet, default error pages, and JSON conversion
B. It only creates controllers
C. It only installs Java
D. It only adds logging

**Answer: A**

**Explanation:** The transcript lists these capabilities together.

**Topic:** Auto-configuration
**Source:** split 2 Step 07

---

### Q218. [Medium] [SINGLE CORRECT]

Which role is associated with default logging in Spring Boot according to the production-readiness discussion?

A. It helps provide production-ready operational behavior without requiring a logging framework setup from scratch
B. It replaces Actuator
C. It disables profiles
D. It converts Java to JSON

**Answer: A**

**Explanation:** Default logging is named as one of Boot's production-readiness conveniences.

**Topic:** Spring Boot goals
**Source:** split 2 Step 05

---

### Q219. [Medium] [SINGLE CORRECT]

Which choice is most aligned with the source's recommended setup when creating a Boot project for a REST API?

A. Use Spring Web, a released Spring Boot version, Java, and Jar packaging
B. Use only Actuator and WAR packaging
C. Use H2 without web support
D. Use a snapshot as the preferred stable release

**Answer: A**

**Explanation:** The Initializr example uses Java, a released Boot version, Spring Web, Jar packaging and properties.

**Topic:** Spring Initializr
**Source:** split 2 Step 03

---

### Q220. [Medium] [MULTIPLE CORRECT]

Which options are explicitly described as default or supported embedded servers in the material? [Select all that apply]

A. Tomcat
B. Jetty
C. Undertow
D. WebLogic as the default embedded server

**Answers: A, B, C**

**Explanation:** Tomcat is the default in the demonstrated setup; Jetty and Undertow are also mentioned as supported.

**Topic:** Embedded servers
**Source:** split 2 Step 11

---

### Q221. [Medium] [SINGLE CORRECT]

Which pairing is mismatched according to the transcript?

A. DevTools → production metrics
B. Actuator → production monitoring
C. Profiles → environment-specific configuration
D. ConfigurationProperties → grouped configuration

**Answer: A**

**Explanation:** Production metrics/monitoring belongs to Actuator, not DevTools.

**Topic:** Feature comparison
**Source:** split 2

---

### Q222. [Medium] [SINGLE CORRECT]

A developer sees spring-boot-starter-web in an old course screenshot but spring-boot-starter-webmvc in a newer Boot 4 project. Which explanation is source-faithful?

A. The transcript identifies these as version-era naming differences
B. One is for Angular and one for React
C. One is a database starter
D. They are unrelated to Spring MVC

**Answer: A**

**Explanation:** The transcript specifically warns that older examples may show the older starter names.

**Topic:** Spring Boot version-specific starters
**Source:** split 2 Step 03

---

### Q223. [Hard] [MULTIPLE CORRECT]

Which conditions or configuration elements are used in the source's examples to make automatic behavior occur? [Select all that apply]

A. Frameworks/classes present on the classpath
B. Existing application configuration
C. Profile activation
D. A CSS stylesheet being loaded

**Answers: A, B, C**

**Explanation:** Classpath, configuration and profiles influence different parts of Boot's automated behavior; CSS does not.

**Topic:** Integrated Boot configuration
**Source:** split 2

---

### Q224. [Hard] [MULTIPLE CORRECT]

Which statements about the source's deployment story are correct? [Select all that apply]

A. Jar packaging is demonstrated
B. Embedded Tomcat is used by default in the web example
C. Java alone is enough to launch the packaged application in the demonstrated model
D. An external Tomcat installation is mandatory

**Answers: A, B, C**

**Explanation:** The material emphasizes simplified deployment through an embedded server and a runnable JAR.

**Topic:** Embedded deployment
**Source:** split 2 Step 11

---

### Q225. [Medium] [MULTIPLE CORRECT]

Which behaviors are explicitly separated between development convenience and production readiness? [Select all that apply]

A. DevTools → faster development feedback
B. Actuator → production monitoring
C. Profiles/configuration → environment-specific settings
D. Starters → convenient dependency grouping

**Answers: A, B, C, D**

**Explanation:** Each feature is assigned a distinct role in the transcripts.

**Topic:** Integrated Spring Boot features
**Source:** split 2 Steps 05-14

---

### Q226. [Medium] [MULTIPLE CORRECT]

Which statements about @ConfigurationProperties from the transcript are correct? [Select all that apply]

A. A prefix can be assigned
B. Multiple related fields can be grouped
C. The class can be managed as a Spring component
D. It is used to define HTTP request mappings

**Answers: A, B, C**

**Explanation:** The first three describe the demonstrated currency-service configuration class; HTTP mappings belong elsewhere.

**Topic:** ConfigurationProperties
**Source:** split 2 Step 10

---
