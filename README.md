# CQRSTemplate

CQRSTemplate solution has a front end web app and a web api.

## Technologies

Asp.net core 7.0 LTS project created using CQRS

Others:

- ASP.NET Core

## Requirements

- https://www.microsoft.com/net/download/windows#/current the latest .NET Core 0.x SDK

### Running in Visual Studio

- Set Startup projects:
  - CQRSTemplate.Web
  - CQRSTemplate.Api

## EF Core & Data Access


  
### Database providers:

- 


## How to configure API & Swagger

- For development is running on url - `http://localhost:40767` and swagger UI is available on url - `https://localhost:7184/swagger`
- For swagger UI is configured an API


### Solution structure:

- CQRSTemplate.Web:

  - `CQRSTemplate.Web` - project that contains the blazor web UI

- CQRSTemplate.Api:

  - `CQRSTemplate.Api` - project that contains the web api

  ###Project folder structure
  - 'Domain': Core.Domain
  - contain entities, entity configurations, enums, exceptions,DbContext and Dependency injection setup
  
   - 'Application': Application
   - contains service definition and implementation,DTOs,Exceptions and  Dependency injection setup

    - 'Infrastructure': Infrastructure
    -contains the EventBus and repository  implementation 