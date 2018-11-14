# Example using Resources

Custom Resources provide a data abstraction layer where you can choose and alias the data to be presented, and define nested documents that can join data from multiple databases.

At runtime, CA Live API Creator uses this information to drive the mapping process, which transforms resource rows to table rows, to automate business logic processing and persistence.
You can define the following different types of resources:
* Ⓣ Table-based Resource is the most common case. These are resources that join together one or more entities (tables or views), with the ability to alias the entity columns and specify joins and filters. SQL is fully automated.
* Ⓢ Free SQL Resource is for resources where you manually specify the SQL to execute. These resources are read-only, but they do give you full latitude to set up the SQL any way you want. You can pass filters, sorts, pagination to your custom SQL.
* Ⓙ JavaScript Resource resources are the most complex, and more advanced. They allow you to write server-side JavaScript code that will be executed whenever this resource is accessed. Your JavaScript code will be responsible for retrieving data, and for formatting it into JSON. The typical use for this resource type is to make a call to an outside REST service.

![Resources](../../../../images/use-integration.png)

## Installation
```aidl
1. Stop your LAC
2. Copy this examples folder to your ${LAC_REPOSITORY_HOME}/teamspaces/[teamspace_name]/apis
3. Start your LAC
4. Click on the Examples Resources API project
```

