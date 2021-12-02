# stacks-dotnet-packages-cosmosdb

A collection of common helpful cosmos database classes


# How to test locally

To run the tests you will need the [CosmosDB emulator](https://docs.microsoft.com/en-us/azure/cosmos-db/local-emulator) installed.

* Start the CosmosDB emulator
* Open the [CosmosDB emulator data explorer](https://localhost:8081/_explorer/index.html) and copy the `Primary Key` value
* Set the `COSMOSDB_KEY` environment variable with the value of the `Primary Key`
* In the `src/` folder run `dotnet test`
