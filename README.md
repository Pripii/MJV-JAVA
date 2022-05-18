**<h1>🎧 Projeto MJV School 🎧</h1>**

**Projeto final MJV School JAVA**

Foi desenvolvida uma Api em Java com Spring Boot para criação de Playlists de Músicas.

<h3>💻 Tecnologias 💻</h3>

- Java 18
- Maven
- [InteliJ](https://www.jetbrains.com/pt-br/idea/)
- [Spring Boot](https://spring.io/projects/spring-boot)
- [Diagrams](https://app.diagrams.net/) 
- [Swagger](https://swagger.io/) 
- [PostegresSQL](https://www.postgresql.org/)

<h3>📝Desenvolvimento do Projeto📝</h3>
O projeto foi desenvolvido com base no MVC (com pacotes model, controller e repository). O sistema foi configurado com base no Spring Framework, o JPA na persistência de dados e interface Swagger. O banco de dados foi feito no Postgres.


- Diagrama de classes (UML):

![umlPlaylist](https://user-images.githubusercontent.com/99191483/169071599-3d362b00-dc15-4254-a19f-5144ae368e4f.png)

- Para acessar a API documentada no Swagger foi utilizada a url : http://localhost:8080/swagger-ui/index.html


<h3>📂Apresentação📂</h3>

1.Criando usuário, playlist e música:
```
{
  "nomeUsuario": "Rubens",
  "email": "rubens@gmail.com",
  "playlist": {
    "nomePlaylist": "Hip hip uha",
    "musicas": [
      {
        "genero": "HIPHOP",
        "autores": "Post Malone",
        "titulo": "Congratulations",
        "duração": 3.12
}
```

2.Criando música:
```
{
 "genero": "HIPHOP",
  "autores": "Post Malone",
  "titulo": "Wow",
  "duração": 2.30
}
```

3.Deletando música:
```
{
  idMusica: 6
}
```
