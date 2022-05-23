
![thumbnail-Microsserviços com Java e Spring](https://user-images.githubusercontent.com/66698429/169815319-20640ad4-cda0-4868-9728-d380c5fcc799.png)



# 2545 - Microsserviços com Java e Spring


Curso de microsserviços com Java e Spring da Alura. Esse curso é o quarto da formação, tendo como pré-requisito a formação Spring Framework e os três primeiros cursos de Microsserviços, conforme links abaixo:

- [Formação Spring](https://cursos.alura.com.br/formacao-spring-framework)
- [Microsserviços: padrões de projeto](https://cursos.alura.com.br/course/microsservicos-padroes-projeto)
- [Fundamentos de Microsserviços: Se aprofundando nos conceitos](https://cursos.alura.com.br/course/fundamentos-microsservicos-aprofundando-conceitos)
- [Microsserviços na prática: entendendo a tomada de decisões](https://cursos.alura.com.br/course/Microsservicos-pratica-tomada-decisoes)


## 🔨 Objetivos do projeto

<p>  O projeto trabalhado no curso é o Alura Food, onde a ideia central é que o mesmo era um monolito e estamos iniciando a decomposição em microsserviços. Começamos implementando a API e projeto do microsserviço de pagamento, tendo um banco de dados próprio [MySQL](https://www.mysql.com).
</p>

<p>  Além disso, fazemos a implementação do Service Discovery utilizando o [Eureka](https://spring.io/projects/spring-cloud-netflix),   solução desenvolvida pela Netflix e que faz parte do [Spring Cloud](https://spring.io/projects/spring-cloud). Incluímos também à arquitetura um [API Gateway](https://spring.io/projects/spring-cloud-gateway), que vai atuar como ponto central para as nossas requisições. É feita a inclusão de um novo microsserviço, que é o de pedidos, onde praticamos a comunicação síncrona e o balanceamento de carga, quando há mais de uma instância do projeto em execução.</p>

<p>  Para fechar, tratamos os conceitos de circuit breaker e fallback, utilizando o [Resilience4J](https://resilience4j.readme.io/docs/getting-started-3) e promovendo uma alternativa quando um dos serviços está inoperante.</p>
