# JavaSpringPostgreSqlDocker
- Ejecutar la aplicación en terminal en el path:
	./mvnw spring-boot:run
-empaquetar todo:
	./mvnw clean package -DskipTests
-Generar el docker-compose (subir previamente docker)
	docker-compose build java_app
    docker-compose up -d	