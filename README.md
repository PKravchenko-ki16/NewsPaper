# NewsPaper
These are microservices based on ASP.NET Core 3.1, using RabbitMQ with MassTransit, EntityFramework Core with MS SQL Server, authentication and authorization with IdentityServer4, as well as Swagger, Bogus, AutoMapper, Bootstrap, etc.

## Objective

Show an example of interaction with several autonomous microservices, interaction between which occurs via the AMQP protocol and using Http as the communication protocol between client applications and the gateway, as well as authentication and authorization (using Claims) with IdentityServer4 using access and refresh token (JWT).

## Links to project repositories
- :white_check_mark:[NewsPaper.MassTransit.Configuration](https://github.com/PKravchenko-ki16/NewsPaper.MassTransit.Configuration)
- :white_check_mark:[NewsPaper.MassTransit.Contracts](https://github.com/PKravchenko-ki16/NewsPaper.MassTransit.Contracts)
- :white_check_mark:[NewsPaper.IdentityServer](https://github.com/PKravchenko-ki16/NewsPaper.IdentityServer)
- :white_check_mark:[Newspaper.GateWay](https://github.com/PKravchenko-ki16/Newspaper.GateWay)
- :white_check_mark:[NewsPaper.Accounts](https://github.com/PKravchenko-ki16/NewsPaper.Accounts)
- :white_check_mark:[NewsPaper.Articles](https://github.com/PKravchenko-ki16/NewsPaper.Articles)
- :white_check_mark:[NewsPaper.GatewayClientApi](https://github.com/PKravchenko-ki16/NewsPaper.GatewayClientApi)
- :white_check_mark:[NewsPaper.Client.Mvc](https://github.com/PKravchenko-ki16/NewsPaper.Client.Mvc)

## Quick Start

1. install RabbitMQ on a working machine.

2. Replace ConnectionStrings in appsettings on projects - [Articles](https://github.com/PKravchenko-ki16/NewsPaper.Articles),
[Accounts](https://github.com/PKravchenko-ki16/NewsPaper.Accounts), 
[IdentityServer](https://github.com/PKravchenko-ki16/NewsPaper.IdentityServer).

3. Uncomment DatabaseInitializer.Init in Program.cs && Apply Migration [IdentityServer](https://github.com/PKravchenko-ki16/NewsPaper.IdentityServer).

## Service interaction

![Alt-текст](https://user-images.githubusercontent.com/26356921/99260684-c5f87a80-282c-11eb-8c6e-6ad5b8d63bdb.png "Service interaction")

## Links to used libraries
- [EntityFrameworkCore](https://github.com/dotnet/efcore)
- [Bogus](https://github.com/bchavez/Bogus)
- [MassTransit](https://github.com/MassTransit/MassTransit)
- [IdentityModel](https://github.com/IdentityModel/IdentityModel)
- [IdentityServer4](https://github.com/IdentityServer/IdentityServer4)
- [AutoMapper](https://github.com/AutoMapper/AutoMapper)
- [Swagger-core](https://github.com/swagger-api/swagger-core)
- [OperationResultCore](https://www.nuget.org/packages/OperationResultCore)
- [Bootstrap](https://github.com/twbs/bootstrap)
