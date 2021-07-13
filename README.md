# Introduction

Command-line client for the Creditcoin blockchain.

## Getting Started

The Creditcoin Client docker images are available on [Docker Hub](https://hub.docker.com/r/gluwa/creditcoin-client).

## Build and Test

Prerequisite: dotnet-sdk-3.1.

* Windows - See [Install .NET on Windows](https://docs.microsoft.com/en-us/dotnet/core/install/windows?tabs=netcore31) for more details.
* Ubuntu - See
[Install the .NET SDK or the .NET Runtime on Ubuntu](https://docs.microsoft.com/en-us/dotnet/core/install/linux-ubuntu)
for more details.
* For other OS options, see [Install .NET on Windows, Linux, and macOS](https://docs.microsoft.com/en-us/dotnet/core/install/)

```bash
dotnet restore
dotnet build
```

## Development Process

The master branch is regularly built and tested, but it is not guaranteed to be completely stable.
Tags are created regularly from release branches to indicate new official, stable release versions of Creditcoin Client.

## Contribute

See [Coding-Standards/C# Coding Standards.md](https://github.com/gluwa/Coding-Standards/blob/main/C%23%20Coding%20Standards.md) for our coding standards.

Issues and suggestions can be shared here.
