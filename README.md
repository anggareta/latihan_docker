# Latihan Docker
dotnet core inside docker

#### step
- docker build . -t ayus/net-web-app
- docker run -p 3000:5000 -d ayus/net-web-app

#### browse
- localhost:3000

#### reference
- https://andrewlock.net/why-isnt-my-aspnetcore-app-in-docker-working/
- https://stackoverflow.com/questions/60546843/aspnetcore-urls-not-being-applied-deploying-in-docker-container
- https://stackoverflow.com/questions/71044525/how-to-access-asp-net-core-web-server-from-another-device
