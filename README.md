## Exemple Spring Boot Swagger Open API 3
Dans ce projet, nous allons voir un exemple de la documentation des API REST Spring Boot à l'aide de Swagger Open API 3.

### Qu'est-ce que la spécification Swagger et Open API
---
La spécification OpenAPI, connue à l'origine sous le nom de spécification Swagger, est une spécification 
pour les fichiers d'interface lisibles par machine pour décrire, produire, consommer et visualiser des services Web RESTful.
<br />
Swagger est un ensemble d'outils open source construits autour de la spécification OpenAPI qui peut vous aider à concevoir, 
créer, documenter et utiliser des API REST.

### Qu'est-ce qu'une API REST
---
REST signifie REpresentational State Transfer, une approche standardisée de la création de services Web.
Une API REST est une interface de programmation d'application intermédiaire qui permet à deux applications 
de communiquer entre elles via HTTP, un peu comme la façon dont les serveurs communiquent avec les navigateurs.<br/>
	
RESTful est l'approche la plus courante pour créer des services Web en raison de sa facilité d'apprentissage et de création.

### Prérequis
---
Pour ce projet, vous auriez besoin des spécifications suivantes :
- Spring Boot v2.0+
- JDK v1.8+
- Maven 3+ ou Gradle 4+ - outil de construction
- Tout IDE prenant en charge Java et Spring Boot (Spring Tool Suite (STS), IntelliJ, VSC, NetBeans, etc.)

### Dependances Maven
---
Dans cet exemple nous allons utiliser les dependances Maven suivants :
- **Spring Web** - pour inclure Spring MVC et utilise le tomcat comme conteneur intégré par défaut.
- **Spring Data JPA** - API de persistance Java et Hibernate
- **Spring Boot DevTools** - dépendance pour les rechargements automatiques ou le rechargement en direct des applications
- Pilote **PostgreSQL** - pilote JDBC pour la base de données PostgreSQL
- **springdoc-openapi-ui** la dépendance est pour swagger Open API 3.

### Test
---
Pour tester la documentation API Swagger, ouvrez le navigateur et entrez l'URL suivante - `localhost:8080/swagger-ui.html` ou `http://localhost:8080/v3/api-docs` <br/>
Soit utilisez un client REST comme postman pour importer la collection des WS en utilisant url : `http://localhost:8080/v3/api-docs`
<br/> <br/>
![SwaggerOpenAPI3](https://user-images.githubusercontent.com/75081354/133271381-8896ba87-3c4d-4278-89d3-fcef081fa9b8.png)

### Installation
---
- git clone https://github.com/teq-niq/sample.git

### Conclusion
---
Chaque jour, des entreprises et des particuliers commencent à utiliser Swagger comme outil de choix pour exposer les API REST à des tiers.<br/>

En utilisant les outils de Swagger 3, vous pouvez générer du code basé sur la documentation d'une API, 
ainsi que créer une belle documentation interactive. Cela permet à la fois d'économiser du temps et des efforts et 
offre une norme avec laquelle les personnes peuvent travailler.

