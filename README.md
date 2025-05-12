
This is edited in master branch Third  time:

Project title and description - Automated Insurance Claims:
 
Problem statement addressed : Filing car insurance claims is often a time-consuming and error-prone process that involves manual documentation, delays in damage assessment, and extended waiting periods for claim approval. 
Automated Insurance Claim is an end-to-end automated car insurance claim system that leverages computer vision, machine learning, and natural language processing to streamline the entire claim process. Users can upload images of the damaged vehicle via web portal. The system automatically detects and assesses the extent of damage using AI-powered image analysis, matches it with policy details and creates a Claim request.

Tech stack used:
	* Azure OpenAI Service (Utilize GPT-4o):  to analyze unstructured claim data and extract key information.
	* Azure Cognitive Services (Form Recognizer, Computer Vision): Extract structured data from claim forms and supporting documents 
	* Azure Logic Apps: Automate the claim processing workflow, including data validation, claim routing, and status updates
	* Insurance Claim Databases (Azure Cosmos DB, Azure BLOB Storage Account, Azure SQL Database)
	* Code Repo (Github): For version control and code storage.
 
Setup instructions (installation, dependencies):
	Install Python and dependencies like Azure Document Intelligence (Form Recognizer), Azure Computer Vision, Azure Cosmos DB, Azure SQL DB, Azure BLOB Storage Account etc.
 
How to run the project:
	After installation of azure components, keep the services like Azure SQL Server etc. up and running.
	Open the Azure Web App App Service, Copy and run the url in browser (URL: https://automated-insurance-claim-app.azurewebsites.net)
	The URL opens a Claim Submission Form, enter the details required, photos of incident, Insurance documents etc and Submit to see the results.
