# ZipCodeService
A test REST API built in .NET Core utilizing Simple Maps data to return City/State information based off of ZipCode entry.

Just playing around with .NET Core and EF Core to figure out how migrations and auto-scaffolding work. This uses a simple SQLite DB to store our data.

## Routes:

> api/cities

Returns all cities from the DB

> api/cities/{zipcode}

Returns city associated with that zipcode, if present in DB
