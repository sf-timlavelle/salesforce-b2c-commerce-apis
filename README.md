# Salesforce B2C Commerce API Postman Collection

I've created this collection by exporting the API-Explorer JSON file and importing into Postman, as I couldn't find another location where all our B2C Commerce API's live. 

This is a Postman Collection cataloguing how to use the [B2C Commerce](https://www.salesforce.com/au/products/commerce-cloud/ecommerce/) REST API.
More information about the API can be found on [documentation.b2c.commercecloud.salesforce.com](https://documentation.b2c.commercecloud.salesforce.com/DOC2/index.jsp?topic=%2Fcom.demandware.dochelp%2FOCAPI%2Fcurrent%2Fdata%2FResources%2FCatalogs.html).

## Installation

To use the latest published version, click the following button to import the Salesforce B2C Commerce API as a collection:

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/1159937-d4af4505-c1e8-994e-32e8-4faf874f9956?action=collection%2Ffork&collection-url=entityId%3D1159937-d4af4505-c1e8-994e-32e8-4faf874f9956%26entityType%3Dcollection%26workspaceId%3D8340d571-c5a9-45ba-8f9d-a2222104932b#?env%5BSalesforce%20Cloud%5D=W3sia2V5Ijoic2FsZXNmb3JjZV91c2VyTmFtZSIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiJ0aW1vdGh5LmxhdmVsbGVAc2FsZXNmb3JjZS5jb20iLCJzZXNzaW9uSW5kZXgiOjB9LHsia2V5Ijoic2FsZXNmb3JjZV9sb2dpblVybCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoiaHR0cHM6Ly9sb2dpbi5zYWxlc2ZvcmNlLmNvbS9zZXJ2aWNlcy9vYXV0aDIvdG9rZW4iLCJzZXNzaW9uSW5kZXgiOjF9LHsia2V5IjoiY29yZV9kb21haW4iLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6InRoaXMtaXMtdGhlLXdheS5saWdodG5pbmcuZm9yY2UuY29tIiwic2Vzc2lvbkluZGV4IjoyfSx7ImtleSI6ImNvcmVfY29uc3VtZXJfa2V5IiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoic2VjcmV0Iiwic2Vzc2lvblZhbHVlIjoiM01WRzlwUnp2TWtqTWI2bjljRjN0UlpnUk5yWi5GYUdYRktUdy50dGZxUThodHQxU3AyRGFxWExUelVCNzEzcEwwOXJ5ZWJjQ1E3cWlrZVdXUThzSCIsInNlc3Npb25JbmRleCI6M30seyJrZXkiOiJjb3JlX2NvbnN1bWVyX3NlY3JldCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6InNlY3JldCIsInNlc3Npb25WYWx1ZSI6IjY1RTcwNUJDMkFCMTZBMzdGRkM1QUJBMkI4NEUzRDlENEJEM0M2QjUzMTA0NThBODdBNTVEMEY0QTM1M0M1QzEiLCJzZXNzaW9uSW5kZXgiOjR9LHsia2V5IjoiY29yZV91c2VybmFtZSIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoidGltb3RoeWxhdmVsbGVAdGltb3RoeWxhdmVsbGUtMjExMTI0LTU2NC5kZW1vIiwic2Vzc2lvbkluZGV4Ijo1fSx7ImtleSI6ImNvcmVfcGFzc3dvcmQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJzZWNyZXQiLCJzZXNzaW9uVmFsdWUiOiJCYXR0bGVGaWVsZDIwNDIhIiwic2Vzc2lvbkluZGV4Ijo2fSx7ImtleSI6ImNvcmVfQVBJX2FjY2Vzc190b2tlbiIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6InNlY3JldCIsInNlc3Npb25WYWx1ZSI6IjAwRDVqMDAwMDAxd3VoTSFBUkFBUU13SnQzMlluQWwxa01mcm5RLm9vcXFKcFZwMU9uaXlNaFVWTzV1RkVlY1hNQkJXbk9Za3hzVHp4bmNVQW80MnFzS3VtNXBkdmFOYUFONlhRZlJ3Mm1wN1NiRWUiLCJzZXNzaW9uSW5kZXgiOjd9LHsia2V5IjoiY29yZV9BUElfaW5zdGFuY2VfdXJsIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJodHRwczovL3RoaXMtaXMtdGhlLXdheS5teS5zYWxlc2ZvcmNlLmNvbSIsInNlc3Npb25JbmRleCI6OH0seyJrZXkiOiJjb3JlX0FQSV9zaWduYXR1cmUiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6ImtjSEJBSnNJNmQyVDdDMjR2aS9SNjNVbk95UC82Sm5teWN3ajNtT0VPcFU9Iiwic2Vzc2lvbkluZGV4Ijo5fSx7ImtleSI6ImNvcmVfQVBJX3ZlcnNpb24iLCJ2YWx1ZSI6IjUzLjAiLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiI1My4wIiwic2Vzc2lvbkluZGV4IjoxMH0seyJrZXkiOiJjb3JlX0FQSV9lbmRwb2ludCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoiaHR0cHM6Ly90aGlzLWlzLXRoZS13YXkubXkuc2FsZXNmb3JjZS5jb20iLCJzZXNzaW9uSW5kZXgiOjExfSx7ImtleSI6ImNvbW1lcmNlX2FjY291bnRNYW5hZ2VyX0hvc3QiLCJ2YWx1ZSI6Imh0dHBzOi8vYWNjb3VudC5kZW1hbmR3YXJlLmNvbSIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiaHR0cHM6Ly9hY2NvdW50LmRlbWFuZHdhcmUuY29tIiwic2Vzc2lvbkluZGV4IjoxMn0seyJrZXkiOiJjb21tZXJjZV9BTV9jbGllbnRJRCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiJlMThmYmEyNy0xODY3LTQ3ZDktYTljMy0xNDNjZGIwNTBlZDUiLCJzZXNzaW9uSW5kZXgiOjEzfSx7ImtleSI6ImNvbW1lcmNlX0FNX3Bhc3N3ZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6InNlY3JldCIsInNlc3Npb25WYWx1ZSI6IlBmVDBYRkhGMEZTMko1cTE1anpFSjZublJFRmw2QTdXIiwic2Vzc2lvbkluZGV4IjoxNH0seyJrZXkiOiJjb21tZXJjZV9yZWFsbUlEIiwidmFsdWUiOiJ6emFwIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiJ6emFwIiwic2Vzc2lvbkluZGV4IjoxNX0seyJrZXkiOiJjb21tZXJjZV9pbnN0YW5jZUlEIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IjE0MSIsInNlc3Npb25JbmRleCI6MTZ9LHsia2V5IjoiY29tbWVyY2VfU0NBUElfc2hvcnRDb2RlIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6Imt2N2t6bTc4Iiwic2Vzc2lvbkluZGV4IjoxN30seyJrZXkiOiJjb21tZXJjZV9zYW5kYm94X2hvc3QiLCJ2YWx1ZSI6InNhbmRib3gudXMwMi5keC5jb21tZXJjZWNsb3VkLnNhbGVzZm9yY2UuY29tIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiJzYW5kYm94LnVzMDIuZHguY29tbWVyY2VjbG91ZC5zYWxlc2ZvcmNlLmNvbSIsInNlc3Npb25JbmRleCI6MTh9LHsia2V5IjoiY29tbWVyY2Vfc2FuZGJveF9hY2Nlc3NDb2RlIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoic2VjcmV0Iiwic2Vzc2lvblZhbHVlIjoiM3lBLmYlKVlrSjV8R2l5VV9kYnxbM013MkY0UHJBJUkvOVpLaU8wVSIsInNlc3Npb25JbmRleCI6MTl9LHsia2V5IjoiY29tbWVyY2Vfc2FuZGJveF9FbmNvZGVkIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6ImRHbHRiM1JvZVM1c1lYWmxiR3hsUUhOaGJHVnpabTl5WTJVdVkyOXRPak41UVM1bUpTbFphMG8xZkVkcGVWVmZaR0o4V3pOTmR6SkdORkJ5UVNWSkx6bGFTMmxQTUZVNlVHWlVNRmhHU0VZd1JsTXlTalZ4TVRWcWVrVktObTV1VWtWR2JEWkJOMWM9Iiwic2Vzc2lvbkluZGV4IjoyMH0seyJrZXkiOiJjb21tZXJjZV9zYW5kYm94X2VuY29kZWRUaW1lU3RhbXAiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiMTY0NDI3MjU1NyIsInNlc3Npb25JbmRleCI6MjF9LHsia2V5IjoiY29tbWVyY2Vfc2FuZGJveF9iZWFyZXJUb2tlbiIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiJleUo2YVhBaU9pSk9UMDVGSWl3aWRIbHdJam9pU2xkVUlpd2lZV3huSWpvaVVsTXlOVFlpTENKcmFXUWlPaUpFTVdoUFVEZEVPRE40VGpCcVpXbHFhVEkzV1dGdlpGUmpYQzlCUFNKOS5leUp6WlhNaU9pSTJObGhhWWxsd1lsQmtRMWxOZEZCQy4uLiIsInNlc3Npb25JbmRleCI6MjJ9LHsia2V5IjoiY29tbWVyY2Vfc2FuZGJveF9leHBpcmVzSW4iLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiODk5Iiwic2Vzc2lvbkluZGV4IjoyM30seyJrZXkiOiJjb21tZXJjZV9zYW5kYm94X1NpdGVJRCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiJtd2F2ZSIsInNlc3Npb25JbmRleCI6MjR9LHsia2V5IjoiZXh0ZXJuYWxfcmF3ZyIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiJodHRwczovL2FwaS5yYXdnLmlvL2FwaSIsInNlc3Npb25JbmRleCI6MjV9LHsia2V5IjoiZXh0ZXJuYWxfcmF3Z19LRVkiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiODg1NjNlZjBmM2EzNDU1MTliMDJhZjI5OGZiZDczODQiLCJzZXNzaW9uSW5kZXgiOjI2fSx7ImtleSI6ImNvbW1lcmNlX2Jhc2VVcmwiLCJ2YWx1ZSI6Imh0dHBzOi8ve3tjb21tZXJjZV9yZWFsbUlEfX0te3tjb21tZXJjZV9pbnN0YW5jZUlEfX0ue3tjb21tZXJjZV9zYW5kYm94X2hvc3R9fS9zLy0vZHcvZGF0YS92MjFfMTAiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6Imh0dHBzOi8ve3tjb21tZXJjZV9yZWFsbUlEfX0te3tjb21tZXJjZV9pbnN0YW5jZUlEfX0ue3tjb21tZXJjZV9zYW5kYm94X2hvc3R9fS9zLy0vZHcvZGF0YS92MjFfMTAiLCJzZXNzaW9uSW5kZXgiOjI3fSx7ImtleSI6Im1hcmtldGluZ19JU19BUElLZXkiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiQUFDRTQ5MjUtNEJFNy00NTQ5LUFEQjMtNDU5QjMwMzA5M0NFIiwic2Vzc2lvbkluZGV4IjoyOH0seyJrZXkiOiJtYXJrdGluZ19JU19BUElTZWNyZXQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoib0xYSDgwZUZ2MzNEcjZfNmY3cW52NjBVVDVnaFRXVDJpeVRpalNIYlFZQSIsInNlc3Npb25JbmRleCI6Mjl9LHsia2V5IjoibWFya2V0aW5nX0lTX0FjY291bnROYW1lIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IiIsInNlc3Npb25JbmRleCI6MzB9LHsia2V5IjoibWFya2V0aW5nX0lTX0luc3RhbmNlTmFtZSIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjMxfSx7ImtleSI6Im1hcmtldGluZ19JU19EYXRhc2V0IiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IiIsInNlc3Npb25JbmRleCI6MzJ9XQ==)

You can also download the collection file from this repo, then import directly into Postman.

### Prerequisites

- *Postman* The collection is for use by the Postman app. Postman is a utility that allows you to quickly test and use REST APIs. More information can be found at [getpostman.com](https://www.getpostman.com/).
- *Account Manager API keys and Commerce Cloud Instance IDs* To use our API, you must have an API key with permissions enabled for which resource you want to use. For instance, for the Sandboxes endpoints, your API key must have the "Salesforce Commerce API" role.

## Usage

The collection is arranged in folders according to the API endpoints (OCAPI/SCAPI).

All requests require a valid Salesforce Account Manager API Client ID and Secret (Password). This should be set in your [Postman environment](https://learning.postman.com/docs/sending-requests/managing-environments/) i.e. outside the collection itself. This should help avoid accidental commits of API keys to repos.

A collection-scope variable `baseUrl` points to a collection of `environment-scope` variables to build your host. More information on managing Postman environments and variables can be found [here](https://learning.postman.com/docs/sending-requests/variables/).

## Postman Environment-scope variables

In order for the API's to work, below is the list of required fields you'll need to update before making your first API call

### Manual Variables to enter into the Salesforce Cloud evironment

|Variable  |Set in         |Description|
|----------|----------------------------|---------------|
|`commerce_AM_clientID` |Environment|Account Manager Client-ID|
|`commerce_AM_passwd`|Environment|Account Manager Password, generated in AM|
|`commerce_realmID` |Environment|Sandbox Realm you're working in:. Ex: `zzap`|
|`commerce_instanceID`|Environment|Your instance ID. Ex: `191`|
|`commerce_SCAPI_shortCode` |Environment|Found in Administration => Salesforce Commerce API Settings|
|`commerce_sandbox_host`|Environment|Your sandbox host. Ex: `sandbox.us02.dx.commercecloud.salesforce.com`|
|`commerce_sandbox_accessCode` |Environment|-|
|`commerce_sandbox_SiteID`|-Environment|The ID of the site you're working with|

### Dynamically Populated Environment-scope variables

The below list of variables are dynamically populated via Pre-Request scripts which are described later in this Readme. 

|Variable  |Set in|Description|
|----------|----------------------------|---------------|
|`baseUrl` |Collection|Creates the baseUrl variable which is used on all APIs. This is found in the Salesforce B2C Commerce Cloud Collection|
|`commerce_sandbox_Encoded`|Environment|Dynamically generated Base64 encoded sequence|
|`commerce_sandbox_encodedTimeStamp` |Environment|Timestamp of when the Token was generated|
|`commerce_sandbox_bearerToken`|Environment|API Bearer token for susequent API calls|
|`commerce_sandbox_expiresIn` |Environment|# of seconds API exires|


## Pre-Request Scripts

Inside this collection, there are two Pre-Request scripts which should not be touched as it handles core functionality needed for the APIs to run as smoothly and seemlessly as possible.

#### Base64 Encoded Generation

In order to help automate the Token generation process, I have included the Postman Crypto.js code to build the string required for encoding and then Base64 encode this string to use within the authentication process. 

### OCAPI Folder Pre-Request Script

As it is best practice to have different Roles and Permissions for the OCAPI Data and Shop API endpoints, I have configured **automatic token generation** and **automatic token refresh generation** on this folders Pre-Request Script. 

The Javascript in this folder is ran for every request in the OCAPI folder and checks if the current token is still valid and if it is not, it will generate a new token and store the values in the Environment file. If the current token is valid, it will skip token generation and execute the set API request. 

### OCAPI > Data & Shop Folder Pre-Request Script

To help with the API request in the Data and Shop Folders, I am dynamically adding two headers into each requests so API calls can be made successfully. In this pre-request script, I am dynamiclly inserting `Authorization` and `client_id` headers. 

## Contribute

Currently all the API's in this Collection are managed by [Tim Lavelle](mailto:timothy.lavelle@salesforce.com) within his Postman account and updates are automatically synced to this repo. Any changes you make locally will not update the main repo, but you can suggest changes and make a pull requst. 

I welcome your contributions!  Please speak to [Tim Lavelle](mailto:timothy.lavelle@salesforce.com) on how to become a contributor to this Collection

## TO-DO

1. Add OCAPI Meta APIs
2. Add SCAPI APIs
3. Add SCAPI Authentication Automation
4. Add Flows for common practices for setup: Category Creation, Product Taxonomy Creation, Product Imports, etc...

## Change Log

### 1.1 - 14 Feb, 2022

#### Updated Shop Pre-request script

- As `Shop` APIs generally require a siteId, I've updated the baseURl to allow a dynamically populated siteID. 

### 1.0 - 8 Feb, 2022

#### Initial Collection Distribution

- Imported OCAPI *21.9* APIs from API Explorer for **Data** and **Shop**
- Created Environment variables for Salesforce Clouds
- Created Pre-Request scripts to automate token generation and refresh
