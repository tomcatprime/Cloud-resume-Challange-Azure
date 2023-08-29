## Intro for project

Steps Involved:

- ✅ HTML: Write in HTML
- ✅ CSS: Style with CSS
- ✅ Static Website: Deploy online using Azure Storage
- ✅ HTTPS: URL should be HTTPS Azure CDN will help with this)
- ✅ DNS: Point custom DNS Domain to CDN endpoint
- ✅ JavaScript: Write JavaScript script to count visitors to site
- ✅ Database: Retrieve and update count with Azure CosmosDB (serverless)
- ✅ API: communicates with database | Azure Functions w/ HTTP trigger
- ✅ Node.JS: Explore Node.JS with Azure Functions
- [x] Test: Write test for Python Code
- [x] IAC: Define Infrestructure as Code in Azure Resource Manager ARM (Consumption Plan)
- [x] Source Control: Use GitHub Actions Workflows
- [x] CI/CD (Backend): GitHub Actions Workflows Backend
- [x] CI/CD (Frontend): GitHub Actions Workflows Frontend
- [x] Blog Post: Hashnode

## Azure Account

- ✅ Create Azure Account

## GitHub Repo

- ✅ Create Github Repo An connect to laptop (git init)

## HTML & CSS

- ✅ Structured site with files and folders
- ✅ Coded Site In HTML & CSS

## Azure Storage Account

- ✅ Used Azure command line interface (CLI)
- ✅ Storage account created successfully
- ✅ Deployed code to Azure static website

## HTTPS & CDN

- ✅ Created CDN endoint
- ✅ Turned on HTTPS for CDN endpoint

## DNS

- ✅ Connected custom Domain name to CDN endpoint
- ✅ Custom domain showing site successfully

## JavaScript on website

- ✅ Write a script that counts the number of visits to the site [script documentation](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) 


## Database

- ✅ Created a database with cosmosDB.
- ✅ Did a quick launch and added the database name and container.
- ✅ Items in database setup successful

## API

- ✅ HTTP trigger created in azure function via VSCode w/ NodeJS
- ✅ To access the Tables API Inside of CosmosDB selected create DB and select Table API
- ✅ added reference to access the Tables storage service through the code " using Microsoft.Azure.Cosmos.Table ";
- ✅ A connection string for AuthN can be retrieved from the portal.
- ✅ To store and retrieve the tables through a key we need URL for the Value of view count.
- ✅ The code connects and accesses thr Tables through the API package created and installed with CosmosDB

## Node.js - azure function - runtime V4

- ✅ Wrote js script for azure http trigger with runtime V4
- ✅ Configure function.json with binding to CosmosDB in/out.
- ✅ Wrote js script to trigger azure function and show output results - number of visitors on webpage.

## Backend and frontend integration
- ✅ Perform test if output is visible on website and if visitors number are properly added in CosmosDB.

## Test

- You should also include some tests for your Python code. Here are some resources on writing good Python tests.

## Infrastructure As Code (IaC)

- You should not be configuring your API resources – the Azure Function, the CosmosDB – manually, by clicking around in the Azure console. Instead, define them in an Azure Resource Manager (ARM) template on a Consumption plan. This is called “infrastructure as code” or IaC. It saves you time in the long run.

## Source Control

- You do not want to be updating either your back-end API or your front-end website by making calls from your laptop, though. You want them to update automatically whenever you make a change to the code. (This is called continuous integration and deployment, or CI/CD.) Create a GitHub repository for your backend code.

## CI/CD Backend

- Set up GitHub Actions such that when you push an update to your ARM template or Python code, your Python tests get run. If the tests pass, the ARM application should get packaged and deployed to Azure.

## CI/CD Frontend

- Create a second GitHub repository for your website code. Create GitHub Actions such that when you push new website code, the Azure Storage blob automatically gets updated. (You may need to purge your Azure CDN endpoint in the code as well.) Important note: DO NOT commit Azure credentials to source control! Bad hats will find them and use them against you!

## Blog Post

- Write about experience to Blog site dev.to

