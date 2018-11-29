"# spring-boot-jsp" 

#maven依赖

	<dependency>
			<groupId>org.apache.tomcat.embed</groupId>
			<artifactId>tomcat-embed-jasper</artifactId>
		</dependency>

		<dependency>
			<groupId>javax.servlet</groupId>
			<artifactId>jstl</artifactId>
		</dependency>
		
# application.properties

spring.mvc.view.suffix=.jsp
spring.mvc.view.prefix=/WEB-INF/jsp/
