# Azure Event Hub Reciever Application

This is a simple Azure Event Hub Listener, which will listen the meesage from already created Event hub in azure.

## Create an Event Hub in Azure

1.  Visit [Azure Portal](https://portal.azure.com/) and Create a new Azure Event Hub .
2.  Note down the Event Hub namespace connection string and keys 

-Note : Add *WindowsAzure.ServiceBus* Nuget Package in the solution
        Make sure to modify the connectionstrings from *App.config* file in the solution
