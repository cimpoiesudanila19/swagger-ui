Совместимость Spring Boot 3.x и Springfox
Springfox (включая версии 3.x) может не работать корректно с Spring Boot 
версии 3.x из-за изменений в Spring Framework 6 и его зависимости от Jakarta EE 
вместо Java EE. В Spring Boot 3.x компоненты, такие как javax.servlet и 
другие классы из Java EE, были заменены на Jakarta EE (jakarta.servlet и т. д.).
А Springfox ещё не полностью поддерживает эти изменения.

Использование Springdoc вместо Springfox

http://localhost:8080/swagger-ui.html
http://localhost:8080/swagger-ui/index.html