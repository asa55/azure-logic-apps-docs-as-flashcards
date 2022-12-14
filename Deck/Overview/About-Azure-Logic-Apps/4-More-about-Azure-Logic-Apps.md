##

Save time and simplify complex processes by using the visual design tools in Azure

%

Logic Apps

##

Create your workflows from start to finish by using the Azure Logic Apps workflow designer in

- `_____`
- `_____`
- `_____`

%

- the Azure portal
- Visual Studio Code
- or Visual Studio

##

If you're creating a multi-tenant based logic app, get started faster when you create a workflow from the `_____` gallery. These `_____` are available for common workflow patterns

%

If you're creating a multi-tenant based logic app, get started faster when you create a workflow from the **templates** gallery. These **templates** are available for common workflow patterns

##

Some patterns and processes are easy to describe but hard to implement in code. The Azure `_____` platform helps you seamlessly connect disparate systems across cloud, on-premises, and hybrid environments. For example, you can connect a cloud marketing solution to an on-premises billing system, or centralize messaging across APIs and systems using Azure Service Bus. Azure Logic Apps provides a fast, reliable, and consistent way to deliver reusable and reconfigurable solutions for these scenarios.

%

Some patterns and processes are easy to describe but hard to implement in code. The Azure **Logic Apps** platform helps you seamlessly connect disparate systems across cloud, on-premises, and hybrid environments. For example, you can connect a cloud marketing solution to an on-premises billing system, or centralize messaging across APIs and systems using Azure Service Bus. Azure Logic Apps provides a fast, reliable, and consistent way to deliver reusable and reconfigurable solutions for these scenarios.

##

Based on your scenario, solution requirements, and desired capabilities, you'll choose to create either a Consumption or Standard logic app workflow. Based on this choice, the workflow runs in either 

- `_____`

%

- multi-tenant Azure Logic Apps
- single-tenant Azure Logic Apps
- an App Service Environment (v3)
- or a dedicated integration service environment (ISE)

##

Running Logic Apps workflows in Single-tenant, ASEv3, and ISE have the following benefit over multi-tenant: your workflows can more easily access resources protected by Azure

%

virtual networks

##

If you create single tenant-based workflows using Azure Arc enabled Logic Apps, you can also run workflows in

%

containers

##

Logic App (Consumption) with host environment Multi-tenant Azure Logic Apps has the following benefits:

- `_____`
- `_____`
- `_____`

%

- Easiest to get started
- Pay-for-what-you-use
- Fully managed

##

Logic App (Consumption) with host environment Integration service environment (ISE) has the following benefits:

- `_____`
- `_____`
- `_____`

%

- Enterprise scale for large workloads
- 20+ ISE-specific connectors that connect directly to virtual networks
- Predictable pricing with included usage and customer-controlled scaling

##

Logic App (Standard) with host environment Single-tenant Azure Logic Apps has the following benefits:

- `_____`
- `_____`
- `_____`
- `_____`
- `_____`

%

- Run using the single-tenant Azure Logic Apps runtime. Deployment slots are currently not supported.
- More built-in connectors for higher throughput and lower costs at scale
- More control and fine-tuning capability around runtime and performance settings
- Integrated support for virtual networks and private endpoints.
- Create your own built-in connectors.

##

Logic App (Standard) with host environment App Service Environment v3 (ASEv3) - Windows plans only - has the following benefits:

Same capabilities as single-tenant plus the following benefits:

- `_____`
- `_____`
- `_____`
- `_____`
- `_____`

Note: If accessed from outside an internal ASE, run histories for workflows in that ASE can't access action inputs and outputs.

%

Same capabilities as single-tenant plus the following benefits:

- Fully isolate your logic apps.
- Create and run more logic apps than in single-tenant Azure Logic Apps.
- Pay only for the ASE App Service plan, no matter the number of logic apps that you create and run.
- Can enable autoscaling or manually scale with more virtual machine instances or a different App Service plan.
- Inherit the network setup from the selected ASEv3. For example, when deployed to an internal ASE, workflows can access the resources in a virtual network associated with the ASE and have internal access points.

Note: If accessed from outside an internal ASE, run histories for workflows in that ASE can't access action inputs and outputs.

##

Logic App (Consumption) with host environment Multi-tenant Azure Logic Apps has the following resource sharing and usage considerations:

- `_____`
- `_____`
- `_____`

%

- A single logic app can have only one workflow.
- Logic apps across Azure Active Directory tenants share the same processing (compute), storage, network, and so on.
- For high availability, geo-redundant storage (GRS) is enabled.

##

Logic App (Consumption) with host environment Integration service environment (ISE) has the following resource sharing and usage considerations:

- `_____`
- `_____`
- `_____`

%

- A single logic app can have only one workflow.
- Logic apps in the same environment share the same processing (compute), storage, network, and so on.
- Data stays in the same region where you deploy the ISE.

##

Logic App (Standard) with host environment Single-tenant Azure Logic Apps has the following resource sharing and usage considerations:

- `_____`
- `_____`
- `_____`

%

- A single logic app can have multiple stateful and stateless workflows.
- Workflows in a single logic app and tenant share the same processing (compute), storage, network, and so on.
- Data stays in the same region where you deploy your logic apps.

##

Logic App (Standard) with host environment App Service Environment v3 (ASEv3) - Windows plans only - has the following resource sharing and usage considerations:

- `_____`
- `_____`
- `_____`

%

- A single logic app can have multiple stateful and stateless workflows.
- Workflows in a single logic app and tenant share the same processing (compute), storage, network, and so on.
- Data stays in the same region where you deploy your logic apps.

##

Logic App (Consumption) with host environment Multi-tenant Azure Logic Apps has the following pricing and billing model:

- `_____`

%

- Consumption (pay-per-execution)

##

Logic App (Consumption) with host environment Integration service environment (ISE) has the following pricing and billing model:

- `_____`

%

- ISE (fixed)

##

Logic App (Standard) with host environment Single-tenant Azure Logic Apps has the following pricing and billing model:

- `_____`
- `_____`

%

- Standard, based on a hosting plan with a selected pricing tier.
- If you run stateful workflows, which use external storage, the Azure Logic Apps runtime makes storage transactions that follow Azure Storage pricing

##

Logic App (Standard) with host environment App Service Environment v3 (ASEv3) - Windows plans only - has the following pricing and billing model:

- `_____`

%

- App Service plan









##

Logic App (Consumption) with host environment Multi-tenant Azure Logic Apps has the following limits management considerations:

- `_____`

%

- Azure Logic Apps manages the default values for these limits, but you can change some of these values, if that option exists for a specific limit.

##

Logic App (Consumption) with host environment Integration service environment (ISE) has the following limits management considerations:

- `_____`

%

- Azure Logic Apps manages the default values for these limits, but you can change some of these values, if that option exists for a specific limit.

##

Logic App (Standard) with host environment Single-tenant Azure Logic Apps has the following limits management considerations:

- `_____`
- `_____`

%

- You can change the default values for many limits, based on your scenario's needs.
- Important: Some limits have hard upper maximums. In Visual Studio Code, the changes you make to the default limit values in your logic app project configuration files won't appear in the designer experience. For more information, see Edit app and environment settings for logic apps in single-tenant Azure Logic Apps.

##

Logic App (Standard) with host environment App Service Environment v3 (ASEv3) - Windows plans only - has the following limits management considerations:

- `_____`
- `_____`

%

- You can change the default values for many limits, based on your scenario's needs.
- Important: Some limits have hard upper maximums. In Visual Studio Code, the changes you make to the default limit values in your logic app project configuration files won't appear in the designer experience. For more information, see Edit app and environment settings for logic apps in single-tenant Azure Logic Apps.

##

Create your logic apps as Azure Resource Manager templates so that you can set up and automate deployments across multiple environments and 

%

regions

##

If no suitable connector is available to run the code you want, you can create and call your own code snippets from your workflow by using Azure Functions. Or, create your own APIs and custom connectors that you can call from

%

your workflows

##

Logic app workflows can access secured resources such as virtual machines (VMs), other services, and systems that are inside an Azure virtual network when you create an

%

integration service environment (ISE)

##

An ISE is a dedicated instance of the Azure Logic Apps service that uses dedicated resources and runs separately from

%

the global multi-tenant Azure Logic Apps service

##

Running logic apps in your own dedicated instance helps reduce the impact that other Azure tenants might have on app performance, also known as the

%

"noisy neighbors" effect

##

An ISE also provides these benefits:

- `_____`

%

- Note from the flashcard author, don't use ISEs. They're expensive, clunky, and difficult to maintain. Had discussions with Microsoft directly regarding this. This opinion obviously does not reflect what is in the docs. If you really need to know what the official advertised benefits of ISEs are, look at the tag on this card to help you navigate to the correct page of the offficial Logic Apps docs. They're listed there.
