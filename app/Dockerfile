FROM mcr.microsoft.com/dotnet/core/aspnet:2.2-alpine
LABEL AUTHOR="dalongrong"
LABEL EMAIL="1141591465@qq.com"
WORKDIR /app
COPY out /app/
EXPOSE 80
ENTRYPOINT [ "dotnet","/app/dotnetcore-docker.dll" ]