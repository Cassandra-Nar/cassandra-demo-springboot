# cassandra-demo-springboot
<b>@SpringBootApplication</b>: equivalent to @EnableAutoConfiguration + @ComponentScan + @Configuration

<b>@EnableAutoConfiguration</b>: annotation tells Spring Boot to "guess" how you will want to configure Spring, based on the jar 
dependencies that you have added. For example, If HSQLDB is on your classpath, and you have not manually configured any 
database connection beans, then Spring will auto-configure an in-memory database.

<b>CommandLineRunner Interface:</b>Spring boot’s CommandLineRunner interface is used to run a code block only once in application’s 
lifetime – after application is initialized.
ApplicationRunner other choice

<b>SpringApplication Class:</b>SpringApplication Class that can be used to bootstrap and launch a Spring application from a 
Java main method. <br>
e.g. : SpringApplication.run(SpringDataCassandraApplication.class, args);
