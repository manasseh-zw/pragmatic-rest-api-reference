# DevHabit

A developer habit tracking system, built with a pragmatic RESTful API.

## Reference snapshot

This repository contains the supplied .NET 10 DevHabit API and React client
snapshot used to study API behavior, background jobs, authentication, and testing.
The source is from Milan Jovanović's [Pragmatic REST APIs in ASP.NET Core](https://www.milanjovanovic.tech/pragmatic-rest-apis)
course, with modifications supplied by Manasseh. This repository is a reference
snapshot, not an official Milan Jovanović repository.

The API is under `DevHabit/DevHabit.Api`, with unit, integration, and functional
test projects beside it. The client is under `client/devhabit-ui`.

Local environment files and generated artifacts are excluded. Development
connection strings, signing/encryption keys, and the Docker database password
have been replaced with placeholders or an explicit environment variable.
Configure those values locally before running the example. The client environment
variable names are listed in `.env.example` with placeholder values.

Existing deployment workflows are retained as reference examples. GitHub Actions
is disabled for this reference repository.
