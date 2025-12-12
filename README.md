# DataSource 설정 - mysql(local)
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver<br>
spring.datasource.url=jdbc:mysql://127.0.0.1:3306/bootdb?serverTime=Asia/Seoul<br>
spring.datasource.username=bootuser<br>
spring.datasource.hikari.password=pwboot<br>

# JPA 설정
spring.jpa.hibernate.ddl-auto=create<br>
spring.jpa.show-sql=true<br>
spring.jpa.properties.hibernate.format_sql=true<br>
spring.jpa.database-platform=org.hibernate.dialect.MySQLDialect<br>
