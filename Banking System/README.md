# BANKING MANAGEMENT SYSTEM

Summary

## Overview

A C++ project is designed with an object-oriented approach, with classes for customers, accounts, transactions, and banking services.Features
included creating and managing customers, accounts, and transactions, as well as performing banking services such as withdrawals, deposits, and
transfers. It also allows customers to view their account information, including account balances, recent transactions, and other
details.Technologies Required: C++ programming language, OOPS, and MySQL.

### Deploy database locally

The database can be deployed locally using Docker. To do this, run the following command to deploy a PostgreSQL database via a Docker image.

```console
docker run --name <some_posgres_name> -p 5432:5432 -e POSTGRES_PASSWORD=<some_password> -d postgres
```
where <some_name> is to replace with the correct value


