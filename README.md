# ZipCodeService
A test REST API built in .NET Core utilizing Simple Maps data to return City/State information based off of ZipCode entry.

## Note:
This is just a sample service, not meant to be used in production. I utilized this project to play around with .NET Core and EF Core to figure out how migrations and auto-scaffolding work and also get used to the C# syntax a bit more. This uses a simple SQLite DB to store our data.

## Routes:

> api/cities

Returns all cities from the DB

> api/cities/{zipCode}

Returns city associated with that zipcode, if present in DB
