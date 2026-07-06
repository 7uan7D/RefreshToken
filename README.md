# RefreshToken

ASP.NET MVC 5 sample application for requesting OAuth access tokens and storing token history for quick review.

## Overview

This project provides a simple web interface to:

- submit token requests using the Resource Owner Password flow
- inspect the returned access token, refresh token, scope, and raw JSON response
- store token records in a local database for later lookup and comparison

## Tech Stack

- ASP.NET MVC 5
- .NET Framework 4.5.2
- Entity Framework 6
- SQL Server LocalDB

## Notes

This repository is intended as a lightweight internal testing tool and portfolio sample for working with token-based authentication flows.

Restore NuGet packages before building the solution in Visual Studio.
