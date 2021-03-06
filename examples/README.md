Overview
====================

| Policy Name | What does it do?                                                               |
|:-----|:--------------------------------------------------------------------------------------|
| <a href="Add correlation id to inbound request.policy.xml">Add correlation id to inbound request</a>| Add Correlation Id for inbound requests |
| <a href="Authorize requests using external authorizer.policy.xml">Authorize requests using external authorizer</a>| Secure API access by using an external authorizer encapsulating custom authentication/authorization logic |
| <a href="Call out to an HTTP endpoint and cache the response.policy.xml">Call out to an HTTP endpoint and cache the response</a>| Enrich requests by calling HTTP endpoint before calling a backend service |
| <a href="Filter response content based on product name.policy.xml">Filter response content based on product name</a>| Filter data elements from the response payload based on the product associated with the request |
| <a href="Forward gateway hostname to backend for generating correct urls in responses.policy.xml">Forward gateway hostname to backend for generating correct urls in responses</a>| Add a Forwarded header in the inbound request to allow the backend API to construct proper URLs |
| <a href="Generate Shared Access Signature and forward request to Azure storage.policy.xml">Generate Shared Access Signature and forward request to Azure storage</a>| Generate Shared Access Signature and forward request to Azure Storage |
| <a href="Get OAuth2 access token from AAD and forward it to the backend.policy.xml">Get OAuth2 access token from AAD and forward it to the backend</a>| OAuth2 for authorization between the gateway and a backend |
| <a href="Get X-CSRF token from SAP gateway using send request.policy.xml">Get X-CSRF token from SAP gateway using send request</a>| Implement X-CSRF pattern, in this case SAP |
| <a href="Log errors to Stackify.policy.xml">Log errors to Stackify</a>| Error logging policy to send errors to Stackify |
| <a href="Mask async calls as synchronous.policy.xml">Mask async calls as synchronous</a>| Mask an asynchronous API endpoint as if it is an synchronous one |
| <a href="Perform basic authentication.policy.xml">Perform basic authentication</a>| Perform basic authentication in the inbound request |
| <a href="Pre-authorize requests based on HTTP method with validate-jwt.policy.xml">Pre-authorize requests based on HTTP method with validate-jwt</a>| Authorize access to specific HTTP methods on an API based on JWT claims |
| <a href="Query CosmosDB.policy.xml">Query CosmosDB</a>| Query CosmosDB |
| <a href="Random load balancer.policy.xml">Random load balancer</a>| Randomly routes (load balances) to one of the two backends |
| <a href="Route requests based on size.policy.xml">Route requests based on size</a>| Route requests based on the size of the message body |
| <a href="Send request context information to the backend service.policy.xml">Send request context information to the backend service</a>| Sends context information to the backend service for logging or processing |
| <a href="Set cache duration using response cache control header.policy.xml">Set cache duration using response cache control header</a>| Sets response cache duration using maxAge value in Cache-Control header sent by the backend |
| <a href="Simple Google OAuth validate-jwt.policy.xml">Simple Google OAuth validate-jwt</a>| Authorize access to your endpoints using Google as an OAuth token provider |
| <a href="Trigger Azure Data Factory Pipeline.policy.xml">Triggering an Azure Data Factory Pipeline</a> | Provide the capability to trigger a specific Azure Data Factory Pipeline without parameters. The authentication handshake with Azure Management REST API is handled in the policy itself so that consumers do not need to manage this |
| <a href="Trigger Azure Data Factory Pipeline With Parameters.policy.xml">Trigger Azure Data Factory Pipeline With Parameters</a> | Provide the capability to trigger a specific Azure Data Factory Pipeline with parameters. The authentication handshake with Azure Management REST API is handled in the policy itself so that consumers do not need to manage this |