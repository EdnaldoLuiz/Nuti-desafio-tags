 <h1 align="center"> Nuti-desafio-tags</h1>

<h2>Observaçoes:</h2>
<p>existem algumas tags que não são muito conhecidas, mas existem e fazem um conjunto com a tag de svg, alem de outras que so são possiveis com auxilio de frameworks.</p>

![imagem ilustrativa de algumas tags pouco conhecidas](src/main/resources/imgs/code.png)

<h2>Visao geral do Projeto:</h2>
<h3>Formulario de busca</h3>

![Alt text](src/main/resources/imgs/form.png)

<h3>Tabela de resultados</h3>

![Alt text](src/main/resources/imgs/result.png)

<h2>Principais Bibliotecas para a Solução:</h2>

### JSoup
Bilioteca usada para extrair a quantidade de tags e seus respectivos nomes das URLs informadas

```xml
<dependency>
	<groupId>org.jsoup</groupId>
	<artifactId>jsoup</artifactId>
	<version>1.16.1</version>
</dependency>
```

### Flyway
Bilioteca usada para criar as tabelas do banco de dados dentro da pasta db/migration
```xml
<dependency>
    <groupId>org.flywaydb</groupId>
    <artifactId>flyway-core</artifactId>
</dependency>

<dependency>
    <groupId>org.flywaydb</groupId>
    <artifactId>flyway-mysql</artifactId>
</dependency>
```
### MySQL-connector
Bilioteca usada para conectar o projeto ao MySQL

```xml
<dependency>
	<groupId>mysql</groupId>
	<artifactId>mysql-connector-java</artifactId>
	<version>8.0.33</version>
</dependency>
```

### JPA
Bilioteca usada para utilizar as interfaces e anotações ajudando a manipular os dados

```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-data-jpa</artifactId>
</dependency>
```

