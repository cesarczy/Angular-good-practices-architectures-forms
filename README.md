# Angular-good-practices-architectures-forms


Angular: boas práticas em arquiteturas e formulários:

https://cursos.alura.com.br/course/angular-boas-praticas-arquiteturas-formularios

Projeto: gatitobook

>cd /api

>npm i

>npm start

>cd /gatitobook

>ng serve

login: cesar

senha: 123


Módulo 1:

* Começamos um projeto utilizando o angular/cli como ferramenta de apoio em todo nosso fluxo de trabalho. Utilizando a opção --strict, ligamos mais verificações de tipo no nosso projeto, melhorando logo na largada a nossa qualidade do nosso código.
* Aprendemos como configurar o Bootstrap como framework de CSS global para nossa aplicação.
* Começamos também a estruturar nossa aplicação utilizando o módulo Angular. Com a técnica do lazy loading, melhoramos o carregamento inicial da nossa aplicação.
* Estudamos também como é composto um componente Angular e quais são os arquivos que o angular/cli gera para nós.
* Começamos a desenvolver nossa primeira funcionalidade: o formulário de Login.

Módulo 2:

* Como interagir com nosso backend utilizando o serviço HttpClient do Angular.
* Como utilizar o mecanismo de Injeção de dependência do Angular para criar nossos próprios serviços e injetá-los nos nossos componentes.
* Vimos também como criar um formulário do tipo Template Driven, em que toda a montagem e a regra de negócio ficam no arquivo de template, e o Angular realiza o controle do modelo de dados utilizando o componente ngModel.
* Criamos um componente de mensagens genérico e aprendemos como receber parâmetros utilizando o @Input e como mostrar conteúdo dinâmico utilizando a interpolação do Angular.
* Por fim, implementamos as validações do nosso formulário HTML utilizando o ngModel para pegar a referência do campo para avaliar se ele está válido ou não.

Módulo 3:

* Como criar um formulário utilizando a técnica de formulários reativos, em que nós temos um pouco mais de configurações, mas ganhamos mais possibilidades e controle sobre o formulário.
* Estudamos a diretiva routerLink e como o Angular analisa o caminho passado, avaliando primeiro a rota do módulo do componente e depois a rota global.
* Criamos o serviço de cadastro de novo usuário e utilizamos a boa prática de criar uma interface para o retorno do backend e assim termos melhor produtividade e menos erros.

Módulo 4:

* Exploramos o tópico de validações em formulário reativos no Angular. e aprendemos como aplicar validações comuns e padronizadas no nosso componente do nosso formulário, além de usar a classe utilitária Validators, padrão do Angular.
* Criamos uma validação customizada para um campo e vimos quais são os requisitos para uma função ser reconhecida como validação no Angular.
* Também trabalhamos em uma função de validação que avaliava mais do que um campo do nosso formulário.
* Por fim, criamos uma validação que consulta o backend da nossa aplicação e aprendemos sobre os operadores RXJS, uma biblioteca poderosa que o Angular utiliza.

Módulo 5:

* Começamos a tratar as informações do nosso usuário que o backend nos retorna na forma de um token JWT (Json Web Token).
* Instalamos uma biblioteca que nos ajuda a trabalhar com esse tipo de dado e criamos um serviço exclusivamente para tratar a gravação e recuperação do token.
* Criamos também um serviço que representa as operações com o usuário logado e nesse serviço decodificamos e fazemos o uso do objeto Subject do RXJS para propagar as alterações das informações do usuário.
* Por fim, criamos o cabeçalho e rodapé da nossa interface interagindo com esse serviço de Usuário.

--------------------------------------------------------------------------------------------------------------

Angular: best practices in architectures and forms:

https://cursos.alura.com.br/course/angular-boas-praticas-arquiteturas-formularios

Project: gatitobook

>cd /api

>npm i

>npm start

>cd /gatitobook

>ng serve

user: cesar

password: 123

Module 1:

* We started a project using angular/cli as a support tool throughout our workflow. Using the --strict option, we turn on more type checking in our project, improving our code quality right from the start.
* We learned how to configure Bootstrap as the global CSS framework for our application.
* We also started to structure our application using the Angular module. With the lazy loading technique, we improve the initial loading of our application.
* We also studied how an Angular component is composed and what files angular/cli generates for us.
* We started to develop our first feature: the Login form.

Module 2:

* How to interact with our backend using Angular's HttpClient service.
* How to use Angular's Dependency Injection mechanism to create our own services and inject them into our components.
* We also saw how to create a Template Driven form, in which all the assembly and the business rule are in the template file, and Angular controls the data model using the ngModel component.
* We created a generic messaging component and learned how to receive parameters using @Input and how to display dynamic content using Angular's interpolation.
* Finally, we implement the validations of our HTML form using the ngModel to get the field reference to evaluate if it is valid or not.

Module 3:

* How to create a form using the reactive forms technique, in which we have a little more settings, but we gain more possibilities and control over the form.
* We studied the routerLink directive and how Angular parses the passed path, evaluating the component module route first and then the global route.
* We created the new user registration service and used the good practice of creating an interface for the return of the backend so that we have better productivity and fewer errors.

Module 4:

* We explored the topic of reactive form validations in Angular. and we learned how to apply common and standardized validations in our form component, in addition to using the Validators utility class, standard in Angular.
* We created a custom validation for a field and saw what are the requirements for a function to be recognized as validation in Angular.
* We also worked on a validation function that evaluated more than one field on our form.
* Finally, we created a validation that queries our application's backend and learned about RXJS operators, a powerful library that Angular uses.

Module 5:

* We started to treat our user information that the backend returns to us in the form of a JWT token (Json Web Token).
* We installed a library that helps us work with this type of data and created a service exclusively to handle the recording and recovery of the token.
* We also created a service that represents the operations with the user logged in and in this service we decode and make use of the Subject object of RXJS to propagate changes to the user's information.
* Finally, we create the header and footer of our interface interacting with this User service.
