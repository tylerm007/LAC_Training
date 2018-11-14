# Example using LAC Listeners and Connections
Listeners provide an event-driven architecture for executing a piece of code 
or triggering a transaction, based upon an incoming external event, 
or internal server events such as startup or shutdown.

Some listeners require a connection, which is a connection to an outside service of some sort, 
like an MQTT service. A connection holds the information required to connect to that outside 
service, like server names, credentials, etc... 


![Listners](../../../../images/use-integration.png)

## Installation
```aidl
1. Stop your LAC
2. Copy this examples folder to your ${LAC_REPOSITORY_HOME}/teamspaces/[teamspace_name]/apis
3. Start your LAC
4. Click on the Examples MQTT API project
```

