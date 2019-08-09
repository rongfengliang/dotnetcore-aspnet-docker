# dotnetcore aspnet docker-compose running demo

## how to running

* build aspnetcore application

```code
cd app

dotnet publish -c Release -o out
```

* start docker-compose service

```code
docker-compose up -d
```

## view webpage

```code
open http://localhost
```