#See https://aka.ms/customizecontainer to learn how to customize your debug container and how Visual Studio uses this Dockerfile to build your images for faster debugging.

FROM mcr.microsoft.com/dotnet/runtime:8.0 
WORKDIR /app
COPY bin/Release/net8.0/publish /app/
ENTRYPOINT ["dotnet","docker-console-app.dll"]

