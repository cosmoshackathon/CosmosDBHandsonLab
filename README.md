# Prerequisites

Prior to starting these labs, you must have the following operating system and software configured on your local machine:

**Operating System**

- 64-bit Windows 10 Operating System
    - [download](https://www.microsoft.com/windows/get-windows-10)
- Microsoft .NET Framework 4.5.1 or higher <sup>1</sup>
    - [download](http://go.microsoft.com/fwlink/?LinkId=863262)

**Software**

| Software | Download Link |
| --- | --- |
| Git | [/git-scm.com/downloads](https://git-scm.com/downloads) |
| .NET Core 2.1 (or greater) SDK <sup>2</sup> | [/download.microsoft.com/dotnet-core-sdk-2.1](https://www.microsoft.com/net/download/dotnet-core/2.1) |
| Visual Studio Code | [/code.visualstudio.com/download](https://go.microsoft.com/fwlink/?Linkid=852157) |
| C# Extensions |
---

# Labs

*It is recommended to complete the labs in the order specified below:*

- [Pre-lab: Creating an Azure Cosmos DB account](./lab/pre-lab.md)
- [Lab 1: Querying an Azure Cosmos DB Database using the SQL API](./lab/QueryCosmos/ReadMe.md)
- [Lab 2: Change Feed Demo - Azure Function](./lab/ChangeFeed/AuditTweetsAzureFunc/README.md)
- [Lab 3: Change Feed Demo - Change Feed Processor Library](./lab/ChangeFeed/ChangeFeedDemo.md)
- [Lab 4: Spark Connector](./lab/SparkConnectionsDemo/readme.md)

# Notes

1. If you are unsure of what version of the .NET Framework you have installed on your local machine, you can visit the following link to view instructions on determining your installed version: <https://docs.microsoft.com/dotnet/framework/migration-guide/how-to-determine-which-versions-are-installed>.
2. If you already have .NET Core installed on your local machine, you should check the version of your .NET Core installation using the ``dotnet --version`` command.
