FROM mcr.microsoft.com/dotnet/sdk:3.1-focal AS build-env
WORKDIR /app

# Copy csproj and restore as distinct layers
COPY *.csproj ./
RUN dotnet restore

# Copy everything else and build
COPY . ./
RUN dotnet publish -c Release -o app-out

# Build runtime image
FROM mcr.microsoft.com/dotnet/sdk:3.1-focal
WORKDIR /home/Creditcoin/Client/

COPY --from=build-env /app/app-out /home/Creditcoin/Client/

HEALTHCHECK CMD ./ccclient
