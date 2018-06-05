# Voidwell.com

Voidwell.com leverages a few technology stacks to operate. The main being docker microservices that communicate with each other via HTTP/REST. They also depend on an OIDC implementation (Voidwell Auth) for token authentication and authorization.

#### Technologies used:

* .NET Core 2.x
  * ASP.NET Core Identity
  * IdentityServer4
* AngularJS 5.x (TypeScript/JavaScript)
* PostgreSQL (SQL)
* Docker
* Redis
* Nginx

#### Services

* [Voidwell.API](https://github.com/Lampjaw/Voidwell.API)
  * REST API gateway responsible for user authorization and internal route propagation.
* [Voidwell.Auth](https://github.com/Lampjaw/Voidwell.Auth)
  * OpenID Connect provider.
* [Voidwell.ClientUI](https://github.com/Lampjaw/Voidwell.ClientUI)
  * Front end interface for [Voidwell.com](https://voidwell.com).
* [Voidwell.DaybreakGames](https://github.com/Lampjaw/Voidwell.DaybreakGames)
  * Manages data and interactions regarding Daybreak Games Company properties (e.g. Planetside 2).
* [Voidwell](https://github.com/Lampjaw/Voidwell)
  * Manages data specifically belonging to Voidwell (e.g. the blog, event configurations, etc).
* [Voidwell.ReverseProxy](https://github.com/Lampjaw/Voidwell.ReverseProxy)
  * A simple reverse proxy implemenation for handling routing to the necessary public services.
* [Voidwell.UserManagement](https://github.com/Lampjaw/Voidwell.UserManagement)
  * Manages user data and authentication.
  
#### Setup
To get the application up and running you may want to use the docker-compose.yml file in this repository. Just make sure to fill in the required fields.
