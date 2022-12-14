##

Description:
"
The Azure resource you create when you want to build a workflow. There are multiple logic app resource types that run in different environments.
"

Term:

%

Logic app

##

Description:
"
A series of steps that defines a task, business process, or workload. Each workflow starts with a single trigger, after which you must add one or more actions.
"

Term:

%

Workflow

##

Description:
"
Always the first step in any workflow and specifies the condition for running any further steps in that workflow. For example, a trigger event might be getting an email in your inbox or detecting a new file in a storage account.
"

Term:

%

Trigger

##

Description:
"
Each subsequent step in a workflow that follows after the trigger. Every action runs some operation in a workflow.
"

Term:

%

Action

##

Description:
"
This connector type provides operations that run natively in Azure Logic Apps. For example, built-in operations provide ways for you to control your workflow's schedule or structure, run your own code, manage and manipulate data, send or receive requests to an endpoint, and complete other tasks in your workflow.

For example, you can start almost any workflow on a schedule when you use the Recurrence trigger. Or, you can have your workflow wait until called when you use the Request trigger. Such operations don't usually require that you create a connection from your workflow.

While most built-in operations aren't associated with any service or system, some built-in operations are available for specific services, such as Azure Functions or Azure App Service.
"

Term:

%

Built-in connector

##

Description:
"
This connector type is a prebuilt proxy or wrapper for a REST API that you can use to access a specific app, data, service, or system. Before you can use most managed connectors, you must first create a connection from your workflow and authenticate your identity. Managed connectors are published, hosted, and maintained by Microsoft.

For example, you can start your workflow with a trigger or run an action that works with a service such as Office 365, Salesforce, or file servers.
"

Term:

%

Managed connector

##

Description:
"
Create this Azure resource when you want to define and store B2B artifacts for use in your workflows. After you create and link an integration account to your logic app, your workflows can use these B2B artifacts. Your workflows can also exchange messages that follow Electronic Data Interchange (EDI) and Enterprise Application Integration (EAI) standards.

For example, you can define trading partners, agreements, schemas, maps, and other B2B artifacts. You can create workflows that use these artifacts and exchange messages over protocols such as AS2, EDIFACT, X12, and RosettaNet.
"

Term:

%

Integration account
