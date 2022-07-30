Dotnet Command:
1. dotnet new webapi -n PlatformService
2. code -r PlatformService
3. dotnet build
4. dotnet run

Add package:
1. dotnet add package AutoMapper.Extensions.Microsoft.DependencyInjection
2. dotnet add package Microsoft.EntityFrameworkCore 
3. dotnet add package Microsoft.EntityFrameworkCore.Design
4. dotnet add package Microsoft.EntityFrameworkCore.InMemory
5. dotnet add package Microsoft.EntityFrameworkCore.SqlServer

Docker Command:
1. docker --version
2. docker build -t maithedung/platformservice . 
|| docker build -t <docker hub id>/platformservice .
3. docker run -p 8080:80 -d maithedung/platformservice
|| docker run -p 8080:80 -d <docker hub id>/platformservice
4. docker ps
5. docker stop <container id>
6. docker start <container id>
7. docker push maithedung/platformservice
|| docker push <docker hub id>/platformservice

