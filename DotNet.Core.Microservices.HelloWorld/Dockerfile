FROM microsoft/aspnetcore:1.1
ARG source
WORKDIR /app
EXPOSE 9090
COPY ${source:-obj/Docker/publish} .
ENTRYPOINT ["dotnet", "DotNet.Core.Microservices.HelloWorld.dll"]
