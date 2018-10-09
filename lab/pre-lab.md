# Getting Started

In this lab, you will create an Azure Cosmos DB account, database, and multiple collections. You will then populate the collections with sample data that will be used in various labs.

### Create Azure Cosmos DB Assets

*You will now create an Azure Cosmos DB account to use in the remaining labs.*

1. In a Internet browser navigate to the **Azure Portal** (<http://portal.azure.com>), and sign in.

1. On the top-left side of the portal, click the **Create a resource** button (big green "+").
	
    ![Create a resource](./media/CreateAzureCosmosDB.PNG)

1. In the new **Azure Cosmos DB** blade, perform the following actions:

    1. In the **ID** field, enter a globally unique value.

    1. In the **API** list, select the **SQL** option.

    1. Leave the **Subscription** field set to its default value.

    1. In the **Resource group** section, select the **Create new** option.

    1. In the **Resource group** section, enter the value **COSMOSLABS**  into the empty field.

    1. In the **Location** field, select the **West US** location.

    1. Ensure the **Enable geo-redundancy** option is selected.

        > This option creates a replicated version of your database in a second (paired) region.

    1. Ensure the **Enable Multi Master** option is not selected.

        > With Azure Cosmos DB multi-master support, you can perform writes on containers of data (for example, collections, graphs, tables) distributed anywhere in the world. You can update data in any region that is associated with your database account. These data updates can propagate asynchronously. 

    1. In the **Virtual networks** section, select the **Disabled** option.

        > Azure CosmosDB accounts can be configured to allow access only from specific subnet of an Azure Virtual Network. By enabling a Service Endpoint for Azure CosmosDB from a Virtual Network and its subnet, traffic is ensured an optimal and secure route to the Azure Cosmos DB.

    1. Click the **Review & Create** button.

1. Once the CosmoDB instance is created.

    ![Create Cosmos instance](./media/CreateNewDatabase.PNG)

    1. Select the CosmoDB instance. Click on the Resource groups, then the Resource group you just created and finally the CosmoDB.

    1. From the CosmoDB blade, in the left panel, select the Data Explorer.

    1. At the top of this section click the button *New Database*.
    
    1. Type the name of the database (ex: TwitterDB).

    1. Click the blue *OK* button at the bottom of the page.
    

1. Next, Create New Collection by right clicking on the Database. In the new **Add Collection** blade, perform the following actions:

	![Create Cosmos instance](./media/CreateCollection_2.PNG)

	1. In the **Databaase id** field, choose the recently created database.
	
	1. In the **Collection Id** field, enter the collection Name.
	
	1. Select the Fixed option for **Storage Capacity**
	
	1. In the **Throughput**, enter 1000 RU/sec
	
	1. Click OK.

1. Wait for the creation task to complete before completing this lab.
