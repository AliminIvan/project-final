### Description
JavaRush University final project template.
A project to develop a task board similar to Jira or Trello. The finished product will help track any activity.

As part of the project, I completed the following tasks:
- Understood the project structure;
- Delete social networks: vk, yandex;
- Extract sensitive information (login, database password, identifiers for OAuth registration/authorization, mail settings) 
into a separate property file;
- Implemented testing using testcontainers;
- Wrote tests for all public ProfileRestController methods;
- Refactored the com.javarush.jira.bugtracking.attachment.FileUtil#upload method so that it uses the modern one 
file system approach;
- Add new functionality: adding tags to a task (REST API + implementation on the service);
- Add a calculation of the time the task was in work and testing. Write 2 methods at the service level, 
which take a task as a parameter and return the elapsed time:
How long the task was in progress (ready_for_review minus in_progress),
How long the task was under testing (done minus ready_for_review);
- Wrote a Dockerfile for the main server;
- Add localization in at least two languages ​​for letter templates (mails) and the index.html start page.

### Stack
JDK17, Spring Boot 3.x, Caffeine Cache, Lombok, SpringDoc OpenApi 2.x, Thymeleaf, Postgresql, Liquibase, Mapstruct, Testcontainers
